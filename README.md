# Enhancements Tracking and Backlog

Enhancement tracking repository for OKD.

This repository provides a rally point to discuss, debate, and reach consensus
for how [enhancements](./enhancements) are introduced into OKD.  OKD combines
Kubernetes container orchestration services with a broad set of ecosystem
components in order to provide an enterprise ready Kubernetes distribution built
for extension.  OKD assembles innovation across a wide array of repositories and
upstream communities.  Given the breadth of the distribution, it is useful to
have a centralized place to describe how OKD introduces enhancements via an
actionable design proposal.

Enhancements may take multiple releases to ultimately complete.  Enhancements
may be filed from anyone in the community, but requires consensus from domain
specific project maintainers in order to implement and accept into the release.

## Is My Thing and Enhancement?

A rough heuristic for an enhancement is anything that:

- a blog post or documentation would get authored to describe
- requires consensus across multiple domains and repositories to complete
- iterates through various maturity phases (developer preview, technical
  preview, GA)
- requires significant long term effort to complete (many weeks, redesigns a
  core component, introduces or deprecates API)
- impacts how a cluster is operated

It is unlikely to require an enhancement if:

- fixes a bug
- adds more testing
- internally refactors a code or component only visible to that components
  domain
- minimal impact to distribution as a whole

If you are not sure if the proposed work requires an enhancement, file an issue
and ask!

## When to Create a New Enhancement Issue

Create an issue here once you:

- have circulated your idea to see if there is interest
   - through Community Meetings, SIG meetings, or mailing lists
- (optionally) have done a prototype in your own fork
- have identified people who agree to work on the enhancement
  - many enhancements will take several releases to complete  

## Why are Enhancements Tracked

As the project evolves, its important that the community understands how
enhancements with broad are built, tested, and documented prior to jumping right
to implementation.  Individually it is hard to understand how all parts of the
system interact, but as a community we can lean on each other to build the right
design and approach.

## When to Comment on an Enhancement Issue

Please comment on the enhancement issue to:
- request a review or clarification on the process
- update status of the enhancement effort
- link to relevant issues in other repos

Please do not comment on the enhancement issue to:
- discuss a detail of the design, code or docs. Use a linked-to-issue or PR
  design for that