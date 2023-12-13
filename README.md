# google-cloud-certifications
Learning resources to study for [Google Cloud Certifications](https://cloud.google.com/learn/certification).

The idea of this repo is to aggregate good resources to pass those certifications. Good resources mean:

* time efficient: I rather have 10 hours of good quality videos rather than a 900 pages book.
* relevant: the content is aligned with the needs of the exam.
* accessible: the content is easily accessible: either free or at a reasonable price.

general material relevant for all certifications
* review & understand the [Security foundations blueprint](https://cloud.google.com/architecture/security-foundations) (PDF document). It unpacks a lot of valuable information.
* [Google Skills Boost](https://www.cloudskillsboost.google/paths) offers learning paths for each certifications. Good content with a mix of videos and labs.

# Tools

handy webtool for subnetting:
* https://visualsubnetcalc.com/
* https://next.lightmesh.com/planner
* https://www.davidc.net/sites/default/subnets/subnets.html

# Cloud Architect
homepage: https://cloud.google.com/learn/certification/cloud-architect


# Cloud Network Engineer
homepage: https://cloud.google.com/certification/cloud-network-engineer

review fundamental knowledge
* Youtuble playlist [Subnetting Mastery](https://www.youtube.com/playlist?list=PLIFyRwBY_4bQUE4IB5c4VPRyDoLgOdExE) from the channel 
[Practical Networking](https://www.youtube.com/@PracticalNetworking)
* Youtuble playlist [Networking Fundamentals](https://www.youtube.com/playlist?list=PLIFyRwBY_4bRLmKfP1KnZA6rZbRHtxmXi) from the channel 
[Practical Networking](https://www.youtube.com/@PracticalNetworking)
* Youtube video [Pod networking for Kubernetes on Google Cloud](https://www.youtube.com/watch?v=sDsWmdMniNs)

Must know resources
* [compare interconnect solutions](https://cloud.google.com/network-connectivity/docs/how-to/choose-product#compare-interconnect-solutions)

Connect to Google Cloud
* Cloud VPN
  * HA VPN is a high-availability (HA) Cloud VPN solution that lets you securely connect your on-premises network to your VPC network through an IPsec VPN connection in a single region. HA VPN provides an SLA of 99.99% service availability.
  * Classic VPN: provides 99.9% availability. It also requires extra configuration and maintenance for the static routes, compared to dynamic routing with BGP utilizing the Cloud Router (HA VPN)
* Cloud Interconnect ([summary](https://cloud.google.com/network-connectivity/docs/how-to/choose-product#compare-interconnect-solutions))
  * Dedicated Interconnect: one or more 10-Gbps or 100-Gbps Ethernet circuits, with a maximum of 8 x 10-Gbps (80 Gbps) circuits, or 2 x 100-Gbps (200 Gbps) circuits for each Dedicated Interconnect connection.
  * Partner Interconnect: Pay only for the capacity you need, with options of 50 Mbps to 50 Gbps for each VLAN attachment
  * Cross-Cloud Interconnect: dedicated physical connection between Google Cloud and your other cloud service provider
* Cloud Router
* [Network Connectivity Center](https://cloud.google.com/network-connectivity/docs/how-to/choose-product#network-connectivity-center): Network Connectivity Center supports connecting different enterprise sites outside of Google Cloud by using Google's network as a wide area network (WAN). On-premises networks can consist of on-premises data centers and branch or remote offices. Network Connectivity Center is a hub-and-spoke model for network connectivity management in Google Cloud. The hub resource reduces operational complexity through a simple, centralized connectivity management model. The hub is paired with Google's network to deliver reliable connectivity on demand.

Connect to Google Workspace and Google APIs
* [Direct peering](https://cloud.google.com/network-connectivity/docs/how-to/choose-product#direct-peering):
* [Carrier peering](https://cloud.google.com/network-connectivity/docs/how-to/choose-product#carrier-peering):

Connect to CDN providers
* [CDN Interconnect](https://cloud.google.com/network-connectivity/docs/how-to/choose-product#what-is-cdn-interconnect): CDN Interconnect enables select third-party Content Delivery Network (CDN) providers to establish direct peering links with Google's edge network at various locations, which enables you to direct your traffic from your Virtual Private Cloud (VPC) networks to a provider's network.


Dedicated Interconnect
* 10 GBS to 100 GBS
* direct physical L2 connection to Google

Career (partner) Interconnect

Cloud VPN

Private Service Connect

Private Google Access
