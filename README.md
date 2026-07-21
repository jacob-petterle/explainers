# Explainers — A Field Guide to the Stack

A personal, growing collection of technical explainers. Each one is a self-contained
HTML page that works out a technology from first principles until it actually makes
sense — written to be re-read, not skimmed once.

**Live site:** https://jacob-petterle.github.io/explainers/

## Contents

### Networking & the Fabric
- [Hedgehog Open Network Fabric](hedgehog-fabric-explainer.html)
- [Hedgehog & Tenant Isolation](hedgehog-tenant-isolation.html)
- [K8s & the Packet](k8s-and-the-packet.html)
- [RoCE & the Switch](roce-and-the-switch.html)

### Bare Metal & Provisioning
- [BMC & Redfish](bmc-redfish-explainer.html)
- [Metal³](metal3-explainer.html)
- [Fleet Management](fleet-management-explainer.html)
- [NetBox](netbox-explainer.html)

### Observability
- [Prometheus](prometheus-explainer.html)
- [Grafana](grafana-explainer.html)

### Data & Workflow
- [Kafka + Iceberg](kafka-iceberg-explainer.html)
- [Temporal](temporal-explainer.html)

## Adding a new explainer

1. Drop the self-contained `<name>-explainer.html` in the repo root.
2. Add a card for it in `index.html` under the right section.
3. Commit and push — GitHub Pages redeploys automatically.

The `.nojekyll` file tells Pages to serve the HTML as-is without Jekyll processing.
