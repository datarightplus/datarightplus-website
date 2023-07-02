---
title: "Contribution Guidelines"
linkTitle: "Contribution Guidelines"
type: docs
url: /docs/contribution-guidelines
description: >
 The CDR+ initiative welcomes and encourages contributions from any member of the public on an open, transparent and collegiate basis.
---

## Ground Rules

We use [IETF Internet-Draft](https://authors.ietf.org/en/home) format to publish our standards. 

All specifications must be hosted on GitHub and be based on the [martinthomson/internet-draft-template](https://github.com/martinthomson/internet-draft-template) I-D template. All specifications must have an assigned and active repository maintainer, abandoned specifications will be delisted.

All submissions, by any contributor, without regard to any commercial obligation are considered to be on a royalty-free, obligation-free and MIT license aligned basis.

All submissions, including submissions by project members, require review. We use GitHub pull requests for this purpose. Consult [GitHub Help](https://help.github.com/articles/about-pull-requests/) for more information on using pull requests.

Issues can be raised in the appropriate specification repository and will be triaged by the assigned repository maintainer. Consult [GitHub Help](https://docs.github.com/en/issues/tracking-your-work-with-issues/quickstart) for more information on using issues.

## Recommendations

When making suggestions the following considerations are recommended:
1. Use markdown for specification format. Some of the early specifications were produced for `mmark` but the general recommendation is `kramdown-rfc`
1. Avoid swathes of large change, focus on small, specific contributions
1. Avoid duplicating upstream specifications, particularly those already in IETF format as it can cause more problems than it solves
1. Contact the author of the specification to discuss the proposed change. An ideal way of doing this is through the Slack community documented on <a href="/participate">Participate</a>.

## Building Specifications

Because specifications use the I-D template from upstream they come with "batteries included" which means after cloning a specification you can use `make` and it will handle things such as setting a python virtualenv and compiling the specification locally.

## Contributing to an existing specification

Here's a quick guide on providing a suggestion to a specification by way of Pull Request.

1. Fork the appropriate specification, for instance the [CDR Plus: Security Baseline](https://github.com/cdrplus/cdrplus-infosec-baseline) on GitHub.
1. Make your changes and send a pull request (PR).
1. If you're not yet ready for a review, add "WIP" to the PR name to indicate it's a work in progress. **Don't** alter front matter.
1. Wait for the automated PR workflow to complete successfully. 
1. Continue updating your doc and pushing your changes until you're happy with the content.
1. When you're ready for a review, add a comment to the PR, and remove any "WIP" markers.

## Improving the website

This website is statically generated using Hugo+Docsy. If you identify corrections or improvements please contact the CDR Plus coordinators on either Slack or via Email (see [Participate](/participate)).

## Creating a new specification

Here's a quick guide on creating a new specification

1. From [martinthomson/internet-draft-template](https://github.com/martinthomson/internet-draft-template) click *Use this template* > *Create a new repository*
1. Introduce your specification and get the CI/CD working so that it is automatically deployed\
1. Contact CDR Plus coordinators on either Slack or via Email (see [Participate](/participate)) 
