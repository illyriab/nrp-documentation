The NRP provides a set of services that repositories use. Some of them you receive; others are interfaces you supply data to. Which of them apply to your repository depends on how it joins the NRP environment.

## What the platform provides

| Service                                                                                                           | What it is                                                                                                                     |
| ----------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| [**Storage and Containers**](/en/docs/repo_admins/shared-services/storage-and-containers)                         | Where repository data and files live — S3 storage and Kubernetes clusters                                                      |
| [**Running Repositories and Applications in the NRP**](/en/docs/repo_admins/shared-services/running-applications) | Running your own application or repository system on the platform — Kubernetes project, quotas, Rancher, `kubectl`, PostgreSQL |
| [**User Management System (AAI)**](/en/docs/repo_admins/shared-services/user_management_system/aai)               | Accounts, virtual organisations and roles through e-infra AAI and Perun                                                        |
| [**Security and Monitoring**](/en/docs/repo_admins/shared-services/security-and-monitoring)                       | Baseline requirements, logging, and where incidents go                                                                         |

## What you supply

These are interfaces the platform harvests from, lists you in, or expects you to assign from. Each page says what you provide to it.

| Interface | What you supply |
|---|---|
| [**National Metadata Directory for Service Administrators**](/en/docs/repo_admins/shared-services/national-metadata-directory/exports-to-nma) | Metadata mapped to CCMM, exposed for harvesting |
| [**National Catalogue of Repositories (NKR)**](/en/docs/repo_admins/shared-services/nkr) | Registration of the repository and of its administrator and curator roles, kept up to date |
| [**Persistent Identifiers (PID)**](/en/docs/repo_admins/shared-services/pid) | Identifiers assigned to records — DOI, Handle, or both |

> [!IMPORTANT]
> For a repository integrated into the NRP, the three interfaces above are conditions, not options. The scope for each way of joining is set out in **Conditions for Creating New and Modifying Existing Domain Repositories in the National Repository Platform**.

## When you use them

You configure these services while the repository is being built, and keep using them afterwards. What changes is what you need from them:

- **While building** — choosing the metadata profile and the identifiers, setting up roles and access, arranging storage quota and a Kubernetes project.
- **In operation** — raising quota, checking metadata exports, reporting an incident, adding or removing users if not managed via repository.

## Related

- **Establishment and Deployment Checklists** — where each service is needed, by phase
- **General Topics** — metadata, FAIR, licences, sensitive data, certification