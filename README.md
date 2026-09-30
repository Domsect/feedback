# DomSect Feedback

This is where the DomSect Extract API gets better — with your input.
Bug reports, feature requests, and roadmap discussions live here.
We read everything.

**Looking for code?** → [domsect/examples](https://github.com/domsect/examples)
**Looking for docs?** → [domsect.io/docs](https://domsect.io/docs)

## Where to post

| You want to… | Post here |
|---|---|
| Report a bug (wrong data, error, outage) | [Issues](../../issues) → *Bug report* |
| Request a feature | [Issues](../../issues) → *Feature request* |
| Ask "how do I…?" / share a use case / discuss the roadmap | [Discussions](../../discussions) |

## What makes a good bug report

- The **target URL** (or a minimal one that reproduces it)
- The `schema_definition` you sent and the `engine` used
- What you got vs. what you expected (paste the `data` block, trimmed)
- `latency_ms` and HTTP status if it errored
- Your SDK / language (e.g. "SDK prototype v0.1.0", "raw curl")

The [bug report template](.github/ISSUE_TEMPLATE/bug_report.md) asks for all of this —
using it gets your issue triaged fastest.

## What makes a good feature request

- The problem you're solving (not just the API shape you want)
- Rough scale: pages/day, engines you use, latency sensitivity
- Whether you'd accept it as a paid add-on — helps us prioritize

## Ground rules

- **Never post a real API key.** Not in issues, discussions, or pasted code.
  If one leaks, revoke it in the [dashboard](https://domsect.io/dashboard) immediately.
- **Security vulnerabilities** don't belong here — email `support@domsect.io`
  privately and we'll respond within 2 business days.
- Only public web data: the API extracts public pages (no login, paywall,
  or PII targets). Requests to bypass access controls will be closed.
- Be kind. Terse is fine; rude is not.

## What to expect from us

- Every issue gets read and labeled (bug / feature / question / wontfix-with-reason).
- We can't promise a fix date on everything — small team, public roadmap.
  Things with a clear problem statement and reproduction get priority.
- If email suits you better: `support@domsect.io`.
