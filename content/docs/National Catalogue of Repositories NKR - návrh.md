The **National Catalogue of Repositories (NKR)** is where repositories in the NRP are registered, together with the entities they relate to — organisations, projects, and the NRP services themselves.

Registration is a condition, not an option. The NRP does not register a repository on its behalf.

> [!NOTE]
> The catalogue lists **entities**. It does not list records — metadata for individual
> records goes to the National Metadata Directory.

## What the catalogue holds

| Object type | What it is |
|---|---|
| **Repository** | a repository running in the NRP, or being built for it, kept as a versioned record |
| **Organization** | an institution involved in a repository or in the platform |
| **Project** | a project a repository or an entity belongs to |
| **Schema** | definitions of the object types above, including NRP services such as AAI or the support queues |

Each object has its own persistent identifier.

## What you supply

**The repository** — its record has two levels, described below.

**Two roles**, each as a natural person, recorded against the repository:

| Role | Recorded as |
|---|---|
| Repository administrator | first name, last name, e-mail |
| Data curator | first name, last name, e-mail |

Both people must already exist in Perun. Verifying that the record is linked to that account is part of the step.

## How it is registered

**The public record** is inserted for you, from the input you provide. It happens at the time the roles are recorded — step 3.11 of the *Establishment and Deployment Checklists* — and it is what makes the repository visible in the catalogue while it is still being built.

**The record is completed later**, in step 4.5, before the repository is handed over to production.

**The repository then maintains its own record.** The repository administrator signs in to the catalogue and keeps it up to date. Where direct integration between a repository and the catalogue exists, this would happen automatically instead.

## The record

### Public record

| Group              | Fields                                                                 |
| ------------------ | ---------------------------------------------------------------------- |
| **Identification** | Repository identifier · Repository name · Repository name in English   |
| **Description**    | Description in Czech · Description in English · Keywords in Czech      |
| **Classification** | Repository type · Repository status · Subject classification           |
| **Lifecycle**      | Start of production phase · End of production phase                    |
| **Relations**      | Main contact · Funding project · Organization · Link to another record |

### Detailed record

| Group | Fields |
|---|---|
| **Access** | Main repository URL · Contact list for the repository administrator |
| **Policies** | Repository policies · Supported licences |
| **Organisation** | Relevant working group |
| **Platform** | NRP infrastructure — whether the repository runs on NRP infrastructure |
| **Capabilities** | Versioning support · Support of related publications and objects |

> [!NOTE]
> **To be confirmed**
> The field lists above are a working draft and may change.

## Related

- **Establishment and Deployment Checklists** — steps 3.11, 3.12 and 4.5
- **Conditions for Creating New and Modifying Existing Domain Repositories in the National Repository Platform** — where registration is stated as a requirement
- **National Metadata Directory for Service Administrators** — where metadata for records goes