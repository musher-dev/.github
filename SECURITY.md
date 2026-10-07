# Security Policy

This is the default security policy for every `musher-dev` repository that does
not publish its own, and for the services Musher runs under `musher.dev` and
`musher.io`. A repository's own `SECURITY.md` takes precedence over this one.

## Reporting a vulnerability

Report a suspected vulnerability privately, in either of these ways:

- Through GitHub's private vulnerability reporting: open the affected
  repository's **Security** tab and choose **Report a vulnerability**.
- By email to [security@musher.dev](mailto:security@musher.dev).

Do **not** open a public issue, discussion or pull request for a security
report.

Include what you can of the following:

- The affected repository, service or URL, and the version or commit.
- What an attacker could do, and the steps or proof of concept that show it.
- Any logs, requests or screenshots that help reproduce it.

## What to expect

We aim to acknowledge a report within **2 business days** and to ship a fix or
workaround for a confirmed vulnerability within **30 days** of that
acknowledgement, depending on severity and complexity. We keep you informed
while we investigate, and agree a disclosure timeline with you case by case.
We credit reporters in the advisory unless you ask us not to.

## Scope

In scope:

- Code, workflows and release artifacts in any `musher-dev` repository.
- Musher's hosted services: the website, console, API and documentation under
  `musher.dev`, and tenant traffic routing under `musher.io`.

Out of scope:

- Applications that customers deploy onto Musher. Report those to their
  owners.
- Upstream open-source projects Musher depends on or lists in its catalog.
  Report those to the upstream project, and tell us if Musher is affected.
- Denial-of-service testing, social engineering and physical attacks.

## Safe harbor

We will not pursue action against anyone who reports in good faith under this
policy, avoids privacy violations and service disruption, and gives us
reasonable time to respond before any disclosure.
