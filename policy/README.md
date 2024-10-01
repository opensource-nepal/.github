# OpenSource Nepal Policy

---

#### **Repository Management**

- **New Repository Creation**:
  - All new repository ideas must be discussed in the organization's Discord channel.
  - Any member can create a public repository. Admins must review the repository later and decide whether it should remain or be archived/deleted.
  - Creation of empty repositories (without code or README) is not allowed.
  - All repositories must follow a basic structure: `README.md`, `LICENSE`, and `.gitignore` as a minimum.
- **Discussions**: All members can create discussions in any repository to propose ideas, report issues, or provide feedback.

---

#### **Pull Requests**

- **Minimum number of approvals for merging a PR**:
  - **Contributors ≥ 10**: 2 approvals
  - **Contributors < 10**: 1 approval
- **Admin Overrides**: The repository admin can merge PRs with 1 approval if necessary for urgent fixes or progress.
- **Stale PRs**: PRs without updates for more than 30 days will be marked as stale and closed after an additional 14 days if no activity is resumed.

---

#### **Admins & Maintainers**

- **Minimum number of active owners in the organization**: 3
- **Minimum number of active admins/maintainers in a repository (if contributors ≥ 10)**: 2
- **Minimum number of maintainers for packages (PyPI, npm, etc.)**: 2
- **Active Admin/Maintainer Criteria**: To be considered "active," admins/maintainers must have contributed code, reviewed PRs, or been involved in significant discussions within the last 6 months.
- **Replacing Inactive Admins/Maintainers**: If an admin or maintainer has been inactive for 1 year, they should be replaced through a nomination and consensus-based voting system among active members.

---

#### **Security and Dependency Management**

- **Dependency Reviews**: Before merging a PR that introduces new dependencies (e.g., npm or PyPI packages), maintainers should ensure the dependency is secure, well-maintained, and does not introduce known vulnerabilities.
- **Security Patches**: If a security vulnerability is discovered, the responsible repository maintainers must issue a patch within 7 days, or sooner, for critical vulnerabilities.
- **Automated Dependency Management**: Use tools like [Dependabot](https://github.com/dependabot) to automatically monitor and update outdated or vulnerable dependencies.

---

#### **General Governance**

- **Code of Conduct**: The organization must adhere to a standard Code of Conduct, such as the [Contributor Covenant](https://www.contributor-covenant.org/), to ensure respectful and inclusive interactions among contributors.
- **Conflict Resolution**:
  - **Technical Disputes**: If there is a technical disagreement, members should first attempt to resolve it through discussions. If the conversation on GitHub becomes lengthy, members should continue the discussion in the relevant Discord channel. If no agreement is reached, admins may mediate or call for a majority vote.
  - **Personal/Interpersonal Conflicts**: Any personal conflicts should be reported to admins, who will mediate and ensure a resolution that aligns with the organization’s Code of Conduct.
