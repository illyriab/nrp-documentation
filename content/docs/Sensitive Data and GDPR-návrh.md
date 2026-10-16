---
title: Sensitive Data and GDPR
---

Not everything can be open. Even where research data should be as open as possible, ethical,
legal and security limits mean that some of it cannot be — and the FAIR principles
acknowledge this.

How the NRP treats sensitive data is set out in two documents: the **Charter of the EOSC CZ
Working Group Sensitive Data** and the **Initial AAI architecture for sensitive data in NRP**.
This page is an overview of both.

## What makes data sensitive

- they are intended strictly for a precisely defined group of people;
- they require special regulation because of their nature — protected by law, or by trade
  secrets, contracts or licences;
- access outside that group is likely to cause significant or damaging consequences —
  financial, moral, legal, or to health and life.

The category is decided by the **data owner**, unless the law says otherwise. In practical
terms, ordinary protection measures are not enough, and the effort put into protection should
be proportionate to the harm disclosure would cause.

## Levels of sensitivity

| Level | What it covers |
|---|---|
| **Low** | Public information and internal data — open research data, method descriptions, unpublished reports |
| **Medium** | Data under a contractual obligation of protection — donor or student records, intellectual property, contact information |
| **High** | Data protected by law or an equivalent principle — health, genetic and biometric data, trade secrets, data affecting state security |

## What it means for a repository

- **Access** is governed by agreements — data access request, data use agreement, data
  transfer agreement — and enforced through the AAI. Sensitive data require multi-factor
  authentication, and may require identity vetting.
- **Processing** may have to happen inside a **trusted research environment**, not by
  downloading the data.
- **Metadata** — a record hidden at the metadata level cannot carry a DOI.
- **Policy** — the repository has to state the retention rules and the conditions for removal.

## Where it is decided

Whether a repository will hold personal or otherwise sensitive data should be decided
**before the repository is built**. It affects the metadata model, access control and storage.

## Personal data and GDPR

**Personal data** are any information relating to an identified or identifiable natural
person — by reference to a name, an identification number, location data, an online
identifier, or factors specific to their physical, physiological, genetic, mental, economic,
cultural or social identity. They are protected under **GDPR** and the **Act on the
Processing of Personal Data**.

Categories the Working Group treats as sensitive personal data: racial or ethnic origin,
political opinions, religious or philosophical beliefs, trade union membership, genetic data,
biometric data used to identify a person, data concerning health, and data concerning sex
life or sexual orientation.

## Related

- **Licences and Legal** — the licence, and the agreements a depositor and a user enter
- **Persistent Identifiers (PID)** — why a record hidden at the metadata level cannot carry a DOI
- **Metadata and CCMM** — what restricted metadata means for the metadata profile
- **User Management System (AAI)** — authentication, roles and access across the NRP

## References

- **[Charter of Working Group Sensitive Data](https://www.eosc.cz/media/3680820/charta_ps_sensi.pdf)** (EOSC CZ, v1.0, 22 January 2024) — the definition and levels of sensitivity
- **[Initial AAI architecture for sensitive data in NRP](https://www.eosc.cz/media/4126476/initial-aai-architecture-for-sensitive-data-in-nrp-1.pdf)** (NRP, deliverable 15, v1.0, 31 December 2025, CC BY 4.0) — the use cases, actors, agreements and requirements