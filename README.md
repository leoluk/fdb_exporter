# fdb_exporter
FoundationDB Prometheus exporter

Work in progress. Basic metrics implemented (read/write operations, transaction metrics).

Added bytes, latency, status metrics.

Dependencies:

    pip install prometheus_client foundationdb

Refer to [this document](https://github.com/apple/foundationdb/blob/master/documentation/sphinx/source/mr-status.rst) for details on FoundationDB's metrics and how to access them.
