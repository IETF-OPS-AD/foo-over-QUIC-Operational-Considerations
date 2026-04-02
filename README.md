# foo-over-QUIC Operational-Considerations
Placeholder for operational considerations related to foo-over-QUIC proposals in operator networks

The use of QUIC as underlying transport (in addition to legacy ones) is being promoted by many applications. The goal is to understand what are the operational benefits and also the challenges (e.g., troubleshooting, diagnostic, etc.). Some of these deployments rely on stable/long sessions, where the use 0-RTT/1-RTT QUIC features may not bring much value.

Putting aside whether there are transport services specific for each of a protocol, there is a need to have a common understanding of the benefits, explore whether there is common operational guidance that can inform most of these extensions (and similar), but also to understand the underlying challenges that can be inherited (e.g., troubleshooting, diagnostic, etc.) especially when the connection endpoints are not adjacent to each others. 

Examples of work in progress specifications, covering various operator uses, are:

* [draft-ietf-regext-epp-quic](https://datatracker.ietf.org/doc/draft-ietf-regext-epp-quic/): Extensible Provisioning Protocol (EPP) Transport over QUIC
* [draft-ietf-netconf-over-quic](https://datatracker.ietf.org/doc/draft-ietf-netconf-over-quic/): NETCONF over QUIC
* [draft-liu-grow-bmp-over-quic](https://datatracker.ietf.org/doc/draft-liu-grow-bmp-over-quic/): Using BMP over QUIC connection
* [draft-liu-sidrops-rpki-rtr-over-quic](https://datatracker.ietf.org/doc/draft-liu-sidrops-rpki-rtr-over-quic/): RPKI to Router Protocol over QUIC
* [draft-llg-opsawg-ipfix-over-quic](https://datatracker.ietf.org/doc/draft-llg-opsawg-ipfix-over-quic/): IPFIX Protocol over QUIC
* [draft-retana-idr-bgp-quic](https://datatracker.ietf.org/doc/draft-retana-idr-bgp-quic/): BGP over QUIC
* [draft-yl-radext-quic-transport](https://datatracker.ietf.org/doc/draft-yl-radext-quic-transport/): RADIUS over QUIC
* [draft-yang-pce-pcep-over-quic](https://datatracker.ietf.org/doc/draft-yang-pce-pcep-over-quic/): PCEP over QUIC
* [draft-cel-nfsv4-rpc-over-quicv1](https://datatracker.ietf.org/doc/draft-cel-nfsv4-rpc-over-quicv1/): Remote Procedure Call over QUIC Version 1

"[Considerations around Transport Header Confidentiality, Network Operations, and the Evolution of Internet Transport Protocols](https://datatracker.ietf.org/doc/rfc9065/)" (RFC 9065) identifies some network operation challenges. Assessing how porting some widely deployed protocols within operator networks would provide required operational needs and whether there is impact on how these protocols are managed. 

# Secure Transport with a focus on Routing

Some of the same OPS considerations would also be common to other secure transport:

* [Foo-Over-QUIC: Challenges when using QUIC for Control Plane Protocols](https://datatracker.ietf.org/meeting/122/materials/slides-122-rtgarea-3-lessons-learned-from-foo-over-quick-00 ) (IETF 122)
* [Benefits of routing over secure transport](https://datatracker.ietf.org/meeting/123/materials/slides-123-rtgarea-routing-over-secure-transport-protocols-00 ) (IETF 123)
* [Using TLS for Routing Protocols](https://datatracker.ietf.org/meeting/123/materials/slides-123-rtgarea-tls-for-routing-protocols-focusing-on-bgp-00) (Specifically BGP) (IETF 123)
 
