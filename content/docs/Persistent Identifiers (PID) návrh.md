A repository must be able to assign persistent identifiers to its records. Citations point to them, and they are expected to keep resolving for as long as the record exists.

This is a condition, not a choice. What is a choice is **which identifier**.

| Repository system | Default | Also supported                                            |
| ----------------- | ------- | --------------------------------------------------------- |
| CESNET Invenio    | DOI     | other schemes, through a configurable identifier provider |
| CLARIN DSpace     | Handle  | DOI                                                       |
| ASEP/ARL          | Handle  | DOI                                                       |

**For an existing repository integrated into the NRP**, the requirement is stated as a capability: the repository must be able to assign identifiers itself. The NRP does not assign them on its behalf.

## Which identifier to use

**DOI** is the practical default. It is what DataCite indexes and what external services expect. Along with the identifier, metadata describing the object is registered — the DOI resolves to a landing page carrying that metadata, and keeps resolving even if the object is moved.

DOI is registered individually for each record, which is why it is not always the right fit:

- **Volume.** Each record needs an identifier registered for it, a landing page that  resolves, and metadata kept in sync with the registration agency. With a large number of records that is a great deal to maintain — and the cost grows once registration stops being free.
- **Records that cannot be public at the metadata level.** No DOI can be assigned to these at all — see below.

Where either applies, a different scheme may be more suitable. Which one is available depends on what the repository system supports.


An overview of persistent identifiers and of the national services behind them, including a decision tree for choosing a registration agency, is at **[identifikatory.cz](https://identifikatory.cz/cs/identifikatory/)** *(in Czech)*.

## Where DOI registration comes from

DOI is registered through a **registration agency** under the International DOI Foundation. For research data the relevant one is **DataCite** — Crossref, the other major agency, serves publishers and publication processes.

A DOI consists of a prefix identifying the organisation that assigns it, and a suffix identifying the object. Repositories are encouraged to join the [Czech National DOI Centre](https://identifikatory.cz/en/services/nc-doi/), which provides registration through DataCite and issues the prefix.

Registration is free of charge while the CARDS project runs. That is tied to the project, not to the platform — if no follow-up project continues it, registration becomes a cost the repository carries.


Czech National DOI Centre also provides methodological support: **doi@techlib.cz**.

## When an identifier is assigned

**DOI is assigned at publication.** It has to resolve to a publicly reachable landing page, so it cannot be assigned to a draft.

It also cannot be assigned to a record whose **metadata** are restricted. A record restricted at the file level, or one where access goes through approval or roles, can carry a DOI — its metadata are public even though its content is not. Only a record hidden at the metadata level cannot.

For these records, and where an identifier is needed before publication, a scheme that does not require a publicly reachable landing page can be used — if the repository system supports one.

> [!NOTE]
> Which identifier is registered for a given record, and at what point in the deposit workflow, is described in your repository's user documentation.

## Related

- **Establishment and Deployment Checklists** — step 2.7, where the identifier is specified
- **National Catalogue of Repositories (NKR)** — where the repository and its roles are registered
- **Czech National DOI Centre** *(link)*