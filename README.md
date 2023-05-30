# BCHN Prometheus Exporter

A [Prometheus] exporter for BCHN written in python and packaged for running as a container.

A rudimentary Grafana [dashboard] is available in the [`dashboard/bitcoin-grafana.json`](dashboard/bitcoin-grafana.json)
file.

The main script is a modified version of [`bitcoin-monitor.py`][source-gist], updated to remove the need for the
`bitcoin-cli` binary, packaged into a [Docker image][docker-image], and expanded to export additional metrics.

[Prometheus]: https://github.com/prometheus/prometheus

[source-gist]: https://gist.github.com/ageis/a0623ae6ec9cfc72e5cb6bde5754ab1f
[python-bitcoinlib]: https://github.com/petertodd/python-bitcoinlib
[dashboard]: https://grafana.com/grafana/dashboards/11274


