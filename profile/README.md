# SecOpsCore

SecOpsCore is a security monitoring platform, a small SIEM. It receives security events, stores and indexes them, detects threats and anomalies, and turns alerts into incidents that an analyst can triage.

It is a solo portfolio project. It practises and demonstrates backend engineering with Java and Spring Boot, microservices and event-driven design, DevOps on Docker and Kubernetes, observability, secure development, and machine learning with Python.

## Status

The documentation baseline is released as `v0.1.0`. No service code exists yet. The next steps are the roadmap and the event catalog, followed by the first service.

## Repositories

- `anomaly-service`: ML-based anomaly detection in Python. Planned.
- `api-gateway`: the single HTTP entry point. Planned.
- `docs`: architecture, requirements and decisions. Released as `v0.1.0`.
- `contracts`: OpenAPI specifications and event schemas. Planned.
- `dashboard`: Angular web interface. Planned.
- `detection-service`: rule-based threat detection. Planned.
- `incident-service`: alerts and incident management. Planned.
- `ingestion-service`: receives and validates security events. Planned.
- `notification-service`: alert delivery. Planned.
- `platform`: Helm charts, Argo CD and observability configuration. Planned.
- `search-service`: event storage, search and analytics. Planned.
- `simulator`: normal and attack traffic for demos, tests and training data. Planned.

Start with the [documentation repository](https://github.com/SecOpsCore/docs), which explains the architecture and the reasons behind each decision.
