# Contributing

This is the default guide for every repository of Lixali Studio, for the team and for anyone outside it who contributes to a public project. When a project has its own `CONTRIBUTING.md`, follow that one: it has the set-up, commands and conventions specific to the project.

## Before you start

- Read the [code of conduct](CODE_OF_CONDUCT.md). It applies to issues, pull requests, reviews and every other project space.
- **Security issues are never reported publicly.** See the [security policy](SECURITY.md).
- Search the existing issues and pull requests: the work may already be planned or in progress.
- For anything larger than a small fix, open an issue first and describe the problem. Agreeing on the approach before you write the code saves you time.

## Reporting a bug

Use the _Bug report_ form and give us:

- the version, release tag or commit you run;
- the steps to reproduce, as short as you can make them;
- what you expected, and what happened instead: status code, error message, logs.

Remove every secret and every piece of personal data before you post: API keys, passwords, encryption keys, real email addresses, client data.

## Suggesting a feature

Use the _Feature request_ form. Start with the problem you are trying to solve, then the solution you have in mind and the alternatives you considered. A clear problem gets a faster answer than a detailed solution.

## Making a pull request

1. Create a branch from the default branch (fork first if you are outside the team), named after the change: `feat/contact-form`, `fix/starttls-timeout`, `docs/install-steps`.
2. Keep one change per pull request. Unrelated refactors and formatting go in their own pull request.
3. Add or update the tests that cover your change, and run the project's lint, type check and tests before you push.
4. Update the documentation (README, guides, `AGENTS.md`) when the behavior, the configuration or the structure changes.
5. Write commits in [Conventional Commits](https://www.conventionalcommits.org/) form: `feat(api): accept attachments`, `fix(smtp): retry on 421`, `docs: clarify install`.
6. Open the pull request against the default branch and fill in the template, in English: what changed, why, and how you checked it. Link the issue it closes.
7. Deploy through the repository's CI only, never from your machine.

A maintainer reviews it. We may ask for changes: that is normal, not a rejection. Once CI passes and the review is approved, a maintainer merges it.

## AI-assisted contributions

You may use coding agents and AI tools. You remain the author: read and understand every line you submit, check that it runs, and say in the pull request description which parts were generated. Do not paste secrets or private code into these tools.

## License

Unless the repository states otherwise, by submitting a contribution you agree that it is licensed under the license of the repository you contribute to, and you confirm that you have the right to submit it.
