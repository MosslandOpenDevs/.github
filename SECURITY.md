# Security Policy

## Scope

This is the default security policy for repositories in the MosslandOpenDevs
organization. It applies to any organization repository that does not publish
its own `SECURITY.md`. Individual repositories may override this default with
a policy of their own — trust-critical projects in particular are expected to
do so — and a repository-level `SECURITY.md` always takes precedence over this
document.

## Reporting a vulnerability

**Do not open a public GitHub Issue for a suspected vulnerability.**

Use GitHub's **Report a vulnerability** function under the affected
repository's Security tab (Private Vulnerability Reporting). Report the issue
to the repository where the weakness lives, not to the organization.

If private vulnerability reporting is unavailable on the affected repository,
or you prefer email, write to **[contact@moss.land](mailto:contact@moss.land)**
— the organization's published security contact. Never put reproduction steps,
secrets, logs, user data, exploit code, or an actionable attack path in a
public Issue.

A useful private report includes:

- the affected repository, version, and commit;
- impact and plausible abuse scenario;
- reproduction steps or proof-of-concept;
- suggested mitigation, when available;
- disclosure constraints and credit preference.

## Handling expectations

Maintainers of the affected repository should:

1. acknowledge and triage the report privately;
2. create or accept a draft GitHub Security Advisory;
3. reproduce and bound the issue;
4. prepare and verify a fix in a private working area when necessary;
5. release the fix;
6. publish an advisory and a sanitized public update when coordinated
   disclosure is appropriate.

Until authorized disclosure, public updates must not include proof-of-concept
exploit code, exact control-bypass conditions, secrets, personal data, or
private reporter information.

## See also

Some organization repositories document their assurance practices through the
[OpenDevs Agentic Assurance Profile](https://github.com/MosslandOpenDevs/agentic-assurance-profile).
Adoption is per-repository and does not change the reporting path described
above.
