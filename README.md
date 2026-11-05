# Vybe

> Production-grade, resilient URL shortener with distributed metrics, tracing, and incident response.

```bash
git clone https://github.com/Luxion-Labs/Vybe.git && cd Vybe && docker compose up --build
```

![Vybe Banner](assets/images/banner.svg)

[![Live Demo](https://img.shields.io/badge/Demo-Live_Preview-00F2FE?style=flat-square)](https://vybe.luxionlabs.com) [![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE) [![SLA](https://img.shields.io/badge/Response_SLA-24_Hours-4FACFE?style=flat-square)](CONTRIBUTING.md)

## Overview
Production-grade, resilient URL shortener with distributed metrics, tracing, and incident response. Built by Luxion Labs as part of our high-velocity open-source engineering ecosystem.

## Features
- Sub-millisecond URL redirection backed by distributed Redis caching.
- Prometheus metrics exporter with preconfigured Grafana dashboards.
- Resilient rate limiting and automated incident response runbooks.
- 100% Dockerized development and production deployment manifests.

## Architecture and Stack
Python, Flask, PostgreSQL, Redis, Prometheus, Grafana, and Docker Compose.

## Quickstart
```bash
git clone https://github.com/Luxion-Labs/Vybe.git && cd Vybe && docker compose up --build
```

## Maintainer Response SLA
Luxion Labs enforces a strict 24-hour response SLA on all community issues, feature proposals, and pull requests. See [CONTRIBUTING.md](CONTRIBUTING.md) for full development guidelines.

## License
Distributed under the MIT License. See [LICENSE](LICENSE) for more details.
