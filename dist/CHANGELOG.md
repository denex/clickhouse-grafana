# 1.3.1 (2018-02-12)

## Fixes

* support array indexing int AST


# 1.3.0 (2018-02-07)

## New Features
* columns autocompletion in ace-editor

# 1.2.7 (2018-01-05)

## Fixes

* properly format query with reserved names
* fix #31


# 1.2.6 (2017-12-13)

## Fixes
* allow rounding with `round` option both time filters: $from and $to


# 1.2.5 (2017-12-05)

## Fixes
* support template variables with different `text` and `value` values [#27](https://github.com/Vertamedia/clickhouse-grafana/issues/27)
* fix visual glitches [#29](https://github.com/Vertamedia/clickhouse-grafana/issues/29)


# 1.2.4 (2017-11-22)

## Fixes
* apply proper value formatting for table format


# 1.2.3 (2017-11-20)

## Fixes
* commit generated files


# 1.2.2 (2017-11-20)

## Fixes
* fix error with absent `getCollapsedText` [#24](https://github.com/Vertamedia/clickhouse-grafana/issues/24)
* suppress errors while parsing AST [#24](https://github.com/Vertamedia/clickhouse-grafana/issues/24)
* show generated SQL in textarea [#24](https://github.com/Vertamedia/clickhouse-grafana/issues/24)
* do not round timestamp after converting [#25](https://github.com/Vertamedia/clickhouse-grafana/issues/25)
* increase max-height of query editor


# 1.2.1 (2017-11-17)

## Fixes
* add forgotten completions
* process NULL values [#19](https://github.com/Vertamedia/clickhouse-grafana/issues/19)
* sort by key value in `$columns` macro [#16](https://github.com/Vertamedia/clickhouse-grafana/issues/16)


# 1.2.0 (2017-11-15)

## New Features
* Ace editor
* ClickHouse function completion (thx to https://github.com/smi2/tabix.ui)


# 1.1.0 (2017-11-13)

## New Features
* Allow `UInt32` as Timestamp column [#15](https://github.com/Vertamedia/clickhouse-grafana/issues/15)
* Add `Format as Table` format [#17](https://github.com/Vertamedia/clickhouse-grafana/issues/17)