
> [!WARNING] If you have any questions, or find errors or missing pieces, please contact us at [support@eosc.cz](mailto:support@eosc.cz).
> 
> If you are an end-user of a repository, this section is not for you — we have [documentation for end-users](https://claude.ai/en/docs/end_users/end_users) as well.

This section collects technical documentation for **building, running and operating repositories in the National Repository Platform** — the repository systems, the services the platform provides, supporting tools, how-tos and policies, and guidance for user support. It is a reference and a collection of links to detailed resources rather than a guide.

It is intended for repository administrators, operators of services in the NRP, and software developers — **for everyone involved in building, running and operating a repository**.

## Where to start

If you are establishing a repository, start with the [**Establishment and Deployment Checklist**](https://claude.ai/%E2%80%A6). It lists steps by phase (preparation, specification, development, going live) and links the document for each one. It is also used at every promotion between environments. A separate checklist for updates and new releases is planned but not yet available.

For everything else, find what you need below.

|I want to…|Read|
|---|---|
|Know who is responsible for what|[**Operating Repositories and Services in the NRP**](https://claude.ai/%E2%80%A6)|
|Learn how a repository on a core system (ASEP/ARL, CESNET-Invenio, CLARIN-DSpace) is operated|[**Running Core Repositories in the NRP**](https://claude.ai/%E2%80%A6)|
|Find out which rules are in force|[**Formal Documents Governing NRP Operations**](https://claude.ai/%E2%80%A6)|
|Understand metadata and CCMM, FAIR, licences, sensitive data, certification|[**General Topics**](https://claude.ai/%E2%80%A6)|
|Ask for help and find out where a request goes|[**User Support**](https://claude.ai/%E2%80%A6)|

### What you need to take care of

What you arrange depends on how your repository uses the NRP.

| Your situation                                    | The NRP provides                                                                | You take care of                                                                               |
| ------------------------------------------------- | ------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| **Core implementation, highly customised**        | test and staging environments, production operation, notice of upcoming changes | your custom code in git, its compatibility and maintenance, and asking for releases            |
| **Your own repository system, joined to the NRP** | shared services: AAI, metadata directory, NKR, identifiers                      | the system itself, its updates and compatibility, and the integration with the shared services |
| **NRP environment only**                          | storage, Kubernetes, PostgreSQL                                                 | your application, its deployment, security baseline and monitoring                             |

For the core implementations, see [**Running Core Repositories in the NRP**](https://claude.ai/%E2%80%A6). For the other two situations, the documents are listed under Services you will need below. Whether a repository that uses only the NRP environment must also integrate with AAI, the metadata directory, NKR and identifiers depends on the conditions that apply to it: see [**Conditions for Creating New and Modifying Existing Domain Repositories…**](https://claude.ai/%E2%80%A6).

### Services you will need

The platform provides shared services for storage, Kubernetes, AAI, metadata, identifiers and security. Each document below also says what you supply to the service. An overview is in [**Shared Services**](https://claude.ai/%E2%80%A6).

|You need|Read|
|---|---|
|Data and file storage|[**Storage and Containers**](https://claude.ai/%E2%80%A6)|
|Kubernetes project, resource quotas, Rancher, `kubectl`, PostgreSQL|[**Running Repositories and Applications in the NRP**](https://claude.ai/%E2%80%A6)|
|Accounts, virtual organisations, Perun, roles|[**User Management System (AAI)**](https://claude.ai/%E2%80%A6)|
|Metadata mapped to CCMM, exports, RIV|[**National Metadata Directory for Service Administrators**](https://claude.ai/%E2%80%A6)|
|Registering the repository|[**National Catalogue of Repositories (NKR)**](https://claude.ai/%E2%80%A6)|
|Assigning identifiers and DOIs|[**Persistent Identifiers (PID)**](https://claude.ai/%E2%80%A6)|
|Security baseline, logging, incidents|[**Security and Monitoring**](https://claude.ai/%E2%80%A6)|

## Resources and community

### Community and documentation

- [**RepoBuilders Community**](https://claude.ai/en/docs/repo_admins/community/repobuilders) — an informal channel for sharing experience, with meeting notes, templates and methodologies. **For a question that needs an answer, use User Support.**
- [**FAQs**](https://claude.ai/en/docs/repo_admins/faq) — answers that do not belong to any single page yet: Ceph/S3 and pre-signed URLs, how granular datasets should be, what a repository needs to assign DOIs
- [**How to Contribute to This Documentation**](https://claude.ai/en/docs/repo_admins/documentation-contribution) — where the source lives, and how to report a correction or open a pull request

### Materials for getting started

- **[Recommendations for Creating Repositories in the NRP Environment](https://www.eosc.cz/media/4117266/recommendations_1-0-1.pdf)** / **[Doporučení pro zakládání repozitářů v NRP](https://www.eosc.cz/media/4117265/doporuceni_0-9-3-1.pdf)** — how to keep an overview of the whole process of establishing and operating a repository, and how not to overlook any essential aspect.
- How to figure out what users actually need from a data repository — watch the recording of the webinar **[Repozitář očima uživatelů: Od potřeb k funkčnímu řešení](https://www.eosc.cz/en/news-and-events/conference-2025/workshops)** or read the EOSC UX Team's **[document with practical tips](https://doi.org/10.71495/x3e9-mf73)**.
