# Public CD of SMPTE RP 2129

## General

_This repository is *public*._

Please consult [CONTRIBUTING.md](./CONTRIBUTING.md), [CONFIDENTIALITY.md](./CONFIDENTIALITY.md), [LICENSE.md](./LICENSE.md) and
[PATENTS.md](./PATENTS.md) for important notices.

Your feedback is welcome at https://github.com/SMPTE/rp2129/issues or at [32nf-chair@smpte.org](mailto:32nf-chair@smpte.org).

## Public Committee Draft (PCD) Notice

The following elements are made available for a public review period ending no earlier than 2022-10-28, and no later than 2023-03-31:

* [RP-2129](https://github.com/SMPTE/rp2129/blob/main/32NF-PCD-RP-2129-Inter%20Entity%20Trust%20Boundary-2022-01-14.pdf)

## Trust Boundaries

For years, Broadcasters and Media Operators (Entities) have been handing off the final composite broadcast channel output via unidirectional co-axial connections using SDI and ASI. Recently they have been migrating this traffic to IP-based network interconnections, typically using newer SMPTE standardized IP protocols such as ST 2022. Entities are learning that there are additional security and routing challenges that must be overcome when utilizing IP networking.  

There are two main areas of concern for Entities  when inter-connecting with others via IP networks: Security and Address space.   

The document introduces the concept of a Trust Boundary, which is a security function at the edge(s) of an Entity’s IP network for broadcast composite channel delivery. 

It also describes some of the security, address space and firewalling challenges and makes some recommendations to address these challenges. 

 

Trust Boundary is a security-focused function deployed at an Entity’s edge that will enable all desired linear media flows in and out, while blocking all other traffic. The location of a Trust Boundary within the workflow from production to consumer is shown in 4 (Trust Boundary Concepts).  Trust boundaries could be considered as media-specific firewalls.
