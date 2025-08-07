---
sidebar_label: 'checkout'
sidebar_position: 4
---

# sg checkout

`sg checkout [OPTIONS]`

## Description

Switch branches or restore working tree files.

## Options

| Option | Description |
| - | - |
| `-b, --branch` | Interactively create a branch |

## Examples
### Branch input

When using `sg checkout -b` to create a branch, you can use spaces in the branch name. The tool automatically converts any amount of spaces to a hyphen.

When you provide `update package  references` as an input, the formatted branch name will become `update-package-references`.
