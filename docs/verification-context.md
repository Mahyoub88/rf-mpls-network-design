# Network Engineering — Verification Context

The three implementations have separate source previews and functional diagrams. The new diagrams explain responsibilities; node counts, terrain shape and grouping are illustrative. No invented customer addressing or router configuration is published.

## Enterprise infrastructure

Trace wireless/wired access, routing, VPN transport and the surveillance/access-control services separately. A useful deployment record connects each service requirement to its device, interface, route and acceptance observation. The public release does not contain the as-built address plan or device configuration exports.

## Wireless coverage

The path illustration distinguishes direct visibility from surrounding Fresnel clearance. Geometry and alignment support planning, while actual service quality requires the site survey, operating frequency, radio settings and field measurements. The terrain drawn is illustrative.

## MPLS backbone

The conceptual figure distinguishes customer-site routes, provider-edge VRFs, MPLS transport and MP-BGP route exchange. It is not the recovered Cisco 7200/GNS3 topology or configuration; the original source preview remains in `docs/overview/mpls-backbone.jpg`. Technical context: [Cisco MPLS VPN overview and sample configuration](https://www.cisco.com/c/en/us/support/docs/multiprotocol-label-switching-mpls/mpls/13733-mpls-vpn-basic.html).

| Verification boundary | Useful record | Publication state |
|---|---|---|
| Access and addressing | Interface and address plan | Not included |
| Underlay | Routing neighbor/state evidence | Not included |
| VPN control plane | Intended VRF and VPN route tables | Not included |
| Forwarding | Customer-path traffic test with source/destination context | Not included |
| Failure recovery | Fault condition, observation and recovery record | Not included |

These are evidence requirements, not claimed test passes. [Independent case studies](PROJECTS.md).
