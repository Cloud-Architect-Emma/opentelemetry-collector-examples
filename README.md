# OpenTelemetry Collector Examples

Ready-to-run OpenTelemetry Collector configurations for the most common observability backends. Copy, paste, and go.

## Examples

| Backend | Signals | Docker Compose |
|---------|---------|----------------|
| [Debug](configs/debug/) | Metrics, Logs, Traces | Yes |
| [Prometheus](configs/prometheus/) | Metrics | Yes |
| [Jaeger](configs/jaeger/) | Traces | Yes |
| [Grafana Loki](configs/loki/) | Logs | Yes |
| [Dynatrace](configs/dynatrace/) | Metrics, Logs, Traces | Yes |
| [Datadog](configs/datadog/) | Metrics, Logs, Traces | Yes |
| [Kubernetes Operator](configs/kubernetes/) | Metrics, Logs, Traces | No |

## Quick Start

    git clone https://github.com/Cloud-Architect-Emma/opentelemetry-collector-examples.git
    cd opentelemetry-collector-examples
    docker compose -f docker-compose/debug.yml up

## Contributing

PRs welcome! See CONTRIBUTING.md.

## License

MIT