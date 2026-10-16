
Security and monitoring are a condition of running a repository in the NRP, not an option. What differs is **who carries them** — and that follows from how the repository joins the NRP environment.

## How the responsibility divides

| | On a core system | Your own system on NRP resources | An existing repository, integrated |
|---|---|---|---|
| **Cybersecurity monitoring** (CESNET-CERTS, FTAS) | inclusion provided by the NRP | established by the repository | the repository must have appropriate cybersecurity infrastructure |
| **Penetration testing** | performed by the NRP | collaboration with the cybersecurity team | collaboration with the cybersecurity team |
| **Incident handling** | handled, with collaboration of the repository | handled, with collaboration of the repository | handled, with collaboration of the repository |
| **Reporting incidents** | by the repository administrator | by the repository administrator — mandatory | by the repository administrator |
| **Central logging** | the NRP configures the repository system's logging into the central system | the repository configures logging into the NRP central system | the repository must be logged |
| **Operational monitoring** | provided by the NRP | the repository's responsibility | at least a basic level, required |
| **Statistics on operation and usage** | collected by the NRP | collected by the repository | for data collection and statistical purposes |

## Security baseline

> [!NOTE] **To be added**
> Every repository must meet a security baseline. The document that defines it will be linked here.
>
> *(placeholder — awaiting confirmation)*

## Logging

The repository must be logged. Logging is what makes it possible to analyse a cybersecurity incident — without it there is nothing to analyse.

For a repository on a core system, the NRP configures the repository system's logging into the central logging system. Where the repository runs its own system, configuring that logging is the repository's task.

## Reporting an incident

Reporting a cybersecurity incident is the repository's obligation, and it is the repository administrator who reports it. In the second case above it is stated explicitly as mandatory.

The administrator also collaborates with the cybersecurity team — during the incident and in handling it afterwards. The same obligation covers security and penetration testing: where testing is not performed by the NRP, the repository takes part.

> [!WARNING]
> Report a security incident through the channel for it. Do not open a public issue and > do not discuss it in a community channel.
>
> *(contact for reporting — awaiting confirmation)*


## Related

- **Formal Documents Governing NRP Operations** — the CESNET cybersecurity principles, available in Czech and in English, and `legal@eosc.cz` for legal consultations
- **User Support** — the queues and mail aliases
- **Establishment and Deployment Checklists** — where the security baseline and monitoring are specified