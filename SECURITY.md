# Security policy

## Reporting a vulnerability

Do **not** open a public issue, discussion or pull request for a security problem.

Report it privately through GitHub: open the affected repository, go to **Security → Report a vulnerability**, and fill in the form. If that button is not available, email **hello@lixalistudio.tech** with the subject `Security: <project>`.

Please include:

- the project and the affected version, release tag or commit;
- the steps to reproduce, or a proof of concept;
- the impact you see: what an attacker can read, change or run;
- whether the issue is already public or known to others.

Never send real secrets (API keys, SMTP passwords, encryption keys) or other people's personal data. Redact them, or use values you generated for the test.

## What happens next

- We acknowledge the report within **3 business days**.
- We confirm or dismiss it, and give a first assessment, within **10 business days**.
- We keep you informed while we work on the fix, and agree a disclosure date with you. We aim to release a fix within **90 days** for confirmed issues, sooner for severe ones.
- Once the fix is released, we publish a GitHub security advisory and credit you, unless you prefer to stay anonymous.

## Supported versions

Fixes go into the latest release of each project, and into what we run in production. Older releases are not patched.

## Scope

In scope: the code in the repositories of [lixalistudio](https://github.com/lixalistudio), and the websites and services we run from them, such as [lixalistudio.tech](https://lixalistudio.tech).

Itaja has its own [security policy](https://github.com/itaja/.github/blob/main/SECURITY.md), and our open source projects follow the [lixalistudio-oss policy](https://github.com/lixalistudio-oss/.github/blob/main/SECURITY.md).

Out of scope:

- vulnerabilities in third-party services (Cloudflare, GitHub, SMTP providers): report them to the vendor;
- findings that need a compromised device or account, social engineering, or physical access;
- denial of service by sheer volume, and reports from automated scanners without a demonstrated impact.

## Safe harbor

We will not take legal action against research done in good faith under this policy: test only against your own deployments or accounts, stop as soon as you have shown the issue, do not access, keep or alter other people's data, and give us reasonable time to fix the issue before disclosing it.
