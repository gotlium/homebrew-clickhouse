# Homebrew ClickHouse Tap

Builds of [ClickHouse](https://clickhouse.yandex) for MacOS.

Build without ICU, support for collations and charset conversion functions disabled

## Installation

### Add homebrew tap

```bash
brew tap ernestp/clickhouse
```

### Install ClickHouse
```bash
brew upgrade
brew install clickhouse
```


## Build bottle
```bash
brew install --build-bottle --cc=gcc-9 --devel clickhouse
brew bottle --json clickhouse
```
