---
sidebar_label: 'init'
sidebar_position: 1
---

# sg init

`sg init`

## Description

Configure the tool.

## Examples
### Enable conventional commits

You can enable [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) by selecting `conventional_commits` option. This setting will ask for a commit type every time you use `sg commit`.

### Ticket integration

If you want your commits to reference a ticket based on the brach name, select `ticket_suffix` option. This setting will append ticket inside parentheses to the end of your commits while using `sg commit`.

Using `sg commit` to create `docs: add readme file` commit message on `feature/TEST-123-demo-setup` branch will result in the following message: `docs: add readme file (TEST-123)`. 