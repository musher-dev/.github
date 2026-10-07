# Contributing

This is the default contributing guide for `musher-dev` repositories. A
repository's own `CONTRIBUTING.md` or `AGENTS.md` adds to it and takes
precedence where they differ. Engineering rules shared across repositories live
in [musher-dev/engineering-conventions](https://github.com/musher-dev/engineering-conventions).

## Start with an issue

Every change starts from an issue. Open one with a form:

- **Bug:** something that used to work stopped working.
- **Feature Request:** someone asked for a capability that does not exist yet.
- **Task:** a slice of work you scoped yourself, sized to 1-3 days.

Issues land on the
[Product Delivery board](https://github.com/orgs/musher-dev/projects/1) and are
triaged there before work starts.

## Make the change

1. Branch from `main`.
2. Keep the change to one concern, and run the repository's checks before you
   push (`task check` where a `Taskfile.yml` exists).
3. Open a pull request and fill in the template, including the AI Usage
   section. Link the issue with `Fixes #<number>`.

## Pull request titles

Pull requests are squash-merged, and the title becomes the commit subject on
`main`. Write it as a [Conventional Commit](https://www.conventionalcommits.org/)
with a scope and a lowercase subject:

```text
fix(api): reject an empty stack name
docs(readme): link the security policy
```

## Review

A code owner reviews every pull request. Agents may open pull requests; people
merge them.

## Conduct and security

Everyone taking part follows the [Code of Conduct](CODE_OF_CONDUCT.md). Report
vulnerabilities privately as the [security policy](SECURITY.md) describes,
never in an issue or pull request.
