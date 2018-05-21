# fdb_exporter
FoundationDB Prometheus exporter

Work in progress. Basic metrics implemented (read/write operations, transaction metrics).

Everything else is missing.

Dependencies:

    pip install prometheus_client foundationdb

Refer to [this document](https://github.com/apple/foundationdb/blob/master/documentation/sphinx/source/mr-status.rst) for details on FoundationDB's metrics and how to access them. 
