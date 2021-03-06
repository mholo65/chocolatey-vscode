---
Order: 40
Title: Invalid URL Provided
Description: One of the urls in the nuspec file does not go to a valid webpage.
Category: Requirements
---

:::{.alert .alert-warning}
**Preliminary Notice**
This rule is not yet available in chocolatey-vscode.
It is a planned rule for 0.8.0.
:::

## Issue

In the nuspec, one of the URLs provided is invalid.
Usually this means that the URL does not actually go to a website.

## Recommended Solution

Please update the incorrect field(s) so that it results in a valid URL.

## Reasoning

We expect that URLs actually go to an existing URL.

## See also

- [Package validator rule](https://github.com/chocolatey/package-validator/wiki/InvalidUrlProvided)
- [SSL capable Guideline](choco1002)
