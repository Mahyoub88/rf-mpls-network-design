# Network Engineering — Independent Implementations

[Browse project collection](https://mahyoub88.github.io/projects/proj-rf-network/) · [Project index](docs/PROJECTS.md) · [Engineering guide](docs/engineering-guide.md)

## Independent implementations

Three independent network implementations: enterprise access, wireless planning and an MPLS backbone. Their original project media remain associated with the correct implementation.

Each section below is a separate project. Images are existing source project media; the architecture and workflow figures are explanatory diagrams.

### Enterprise Wireless & Network Infrastructure Architecture

Multi-zone wireless and LAN infrastructure using MikroTik and Ubiquiti, with secure routing, VPN connectivity, traffic management and surveillance/access-control integration.

![Enterprise Wireless & Network Infrastructure Architecture — original project media](docs/overview/network-architecture.jpg)

The source architecture documents how access and site services fit together. Coverage, routing and security are separate responsibilities; the explanatory diagram preserves those boundaries without inventing customer locations or an undocumented equipment schedule.

![Explanatory architecture — Enterprise Wireless & Network Infrastructure Architecture](docs/projects/proj-enterprise-network/architecture.svg)

![Explanatory workflow — Enterprise Wireless & Network Infrastructure Architecture](docs/projects/proj-enterprise-network/workflow.svg)

[Full project walkthrough](https://mahyoub88.github.io/projects/proj-enterprise-network/)

### Wireless Coverage & Point-to-Point Network Planning

Coverage modelling and point-to-point connectivity, considering antenna alignment, capacity and site coverage.

![Wireless Coverage & Point-to-Point Network Planning — original project media](docs/overview/network-coverage.jpg)

Planning combines the coverage view with the radio path and capacity requirement. The source image records the engineering planning work; no unrecorded throughput or field measurement is added.

![Explanatory architecture — Wireless Coverage & Point-to-Point Network Planning](docs/projects/proj-wireless-coverage/architecture.svg)

![Explanatory workflow — Wireless Coverage & Point-to-Point Network Planning](docs/projects/proj-wireless-coverage/workflow.svg)

[Full project walkthrough](https://mahyoub88.github.io/projects/proj-wireless-coverage/)

### Network Infrastructure Design — MPLS Backbone

A Cisco 7200 backbone built and validated in GNS3 using OSPF, MPLS traffic engineering, VRF/MPLS VPN and MP-BGP.

![Network Infrastructure Design — MPLS Backbone — original project media](docs/overview/mpls-backbone.jpg)

The original topology preview documents the configured network environment. This project is separate from the wireless deployments. Its GNS3 implementation is identified accurately rather than presented as a photograph of a physical carrier network.

![Explanatory architecture — Network Infrastructure Design — MPLS Backbone](docs/projects/proj-mpls-backbone/architecture.svg)

![Explanatory workflow — Network Infrastructure Design — MPLS Backbone](docs/projects/proj-mpls-backbone/workflow.svg)

[Full project walkthrough](https://mahyoub88.github.io/projects/proj-mpls-backbone/)

[Verification context and public evidence boundaries](docs/verification-context.md).
