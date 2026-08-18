# Contributing to Lumen

Contributions to Lumen projects are welcome, whether they involve code, documentation, bug reports, testing, or design.

Before contributing, please read our [Code of Conduct](https://github.com/lumen-rsg/.github/blob/main/CODE_OF_CONDUCT.md).

## Getting started

If you're looking for something to work on:

1. Check the issue tracker for the project you're interested in.
2. Look for issues marked `good first issue` or `help wanted`.
3. Read the repository's README and any project-specific development documentation.
4. If the task is unclear or involves a significant change, open an issue or discussion before starting work.

For lumina, issues can be found in the [lumina issue tracker](https://github.com/lumen-rsg/lumina/issues).

## Reporting bugs

Before opening a new bug report, search existing issues to make sure the problem has not already been reported.

A useful bug report should include:

- a clear description of the problem;
- steps to reproduce it;
- what you expected to happen;
- what actually happened;
- relevant logs, error messages, or screenshots;
- information about your environment when relevant.

Try to include enough information for someone else to reproduce the problem.

## Suggesting features

Feature suggestions are welcome.

Before opening a request, check the existing issues and the [roadmap](https://github.com/lumen-rsg/.github/blob/main/ROADMAP.md) to see whether the idea is already planned or being discussed.

When proposing a feature, explain the problem it solves and why it would be useful. Implementation ideas are welcome, but they are not required.

Large changes should generally be discussed before substantial development begins.

## Contributing code

The usual workflow is:

1. Fork the repository.
2. Create a branch for your changes.
3. Make the changes.
4. Build and test the project.
5. Commit your work.
6. Open a pull request.

Use descriptive branch names where practical, for example:

```text
feature/dock-animations
fix/installer-crash
docs/build-instructions
```

Follow any build or test instructions provided by the repository.

## Pull requests

Keep pull requests focused on a single change or closely related set of changes.

A pull request should explain:

- what changed;
- why the change was made;
- any important implementation details;
- how the change was tested;
- any known limitations or unfinished work.

Avoid including unrelated formatting changes or refactors unless they are necessary for the contribution.

Large changes may be easier to review when split into several smaller pull requests.

## Documentation

Documentation changes are contributions too.

Useful improvements include:

- correcting inaccurate or outdated information;
- improving explanations;
- adding examples;
- documenting missing behavior;
- fixing broken links or commands;
- correcting spelling and grammar.

Documentation should favor clarity over formality.

## Code style

Follow the existing style and structure of the project you are contributing to.

Consistency with the surrounding code is generally more important than introducing a different personal style.

If a repository contains formatting, linting, or static-analysis configuration, use it before submitting your changes.

## Commits

Lumen projects use [Conventional Commits](https://www.conventionalcommits.org/) where practical.

Examples:

```text
feat: add dock animation
fix: handle missing configuration file
docs: update build instructions
refactor: simplify package resolver
```

Keep commit messages short but descriptive.

For larger changes, additional context can be included in the commit body.

## Reviews

Pull requests may receive requests for changes before they are merged. This is a normal part of development.

Review comments should focus on the code and the project rather than the contributor.

When updating a pull request after review, avoid resolving comments until the relevant issue has been addressed or discussed.

## Licensing

By contributing to a Lumen project, you agree that your contribution may be distributed under the license used by that project.

For projects licensed under the GNU General Public License version 3, contributions are made under the terms of the GPL-3.0 unless explicitly stated otherwise in that repository.
