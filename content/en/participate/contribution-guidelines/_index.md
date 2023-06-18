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

## Contributing to an existing specification

Here's a quick guide on providing a suggestion to a specification by way of Pull Request.

1. Fork the appropriate specification, for instance the [CDR Plus: Security Baseline](https://github.com/cdrplus/cdrplus-infosec-baseline) on GitHub.
1. Make your changes and send a pull request (PR).
1. If you're not yet ready for a review, add "WIP" to the PR name to indicate it's a work in progress. **Don't** alter front matter.
1. Wait for the automated PR workflow to complete successfully. 
1. Continue updating your doc and pushing your changes until you're happy with the content.
1. When you're ready for a review, add a comment to the PR, and remove any "WIP" markers.

## Creating a new specification

## Updating a single page

If you've just spotted something you'd like to change while using the docs, Docsy has a shortcut for you:

1. Click **Edit this page** in the top right hand corner of the page.
1. If you don't already have an up to date fork of the project repo, you are prompted to get one - click **Fork this repository and propose changes** or **Update your Fork** to get an up to date version of the project to edit. The appropriate page in your fork is displayed in edit mode.
1. Follow the rest of the [Managing the Documentation](#managing-the-documentation) process above to make, preview, and propose your changes.

## Previewing your changes locally

If you want to run your own local Hugo server to preview your changes as you work:

1. Install Hugo and any other tools you need. You'll need at least **Hugo version 0.97.3** (we recommend using the most recent available version), and it must be the **extended** version, which supports SCSS.
1. Fork the [CDR+ Website repo](https://github.com/bizaio/cdrplus-website) repo into your own project, then create a local copy using `git clone`. Don’t forget to use `--recurse-submodules` or you won’t pull down some of the code you need to generate a working site.

    ```
    git clone --recurse-submodules --depth 1 https://github.com/bizaio/cdrplus-website.git
    ```

1. Run `hugo server` in the site root directory. By default your site will be available at http://localhost:1313/. Now that you're serving your site locally, Hugo will watch for changes to the content and automatically refresh your site.
1. Continue with the usual GitHub workflow to edit files, commit them, push the
  changes up to your fork, and create a pull request.

## Creating an issue

If you've found a problem in the docs, but you're not sure how to fix it yourself, please create an issue in the [CDR+ Website repo](https://github.com/bizaio/cdrplus-website/issues). You can also create an issue about a specific page by clicking the **Create Issue** button in the top right hand corner of the page.

## Useful resources

* [Docsy user guide](https://www.docsy.dev/docs/): All about Docsy, including how it manages navigation, look and feel, and multi-language support.
* [Hugo documentation](https://gohugo.io/documentation/): Comprehensive reference for Hugo.
* [Github Hello World!](https://guides.github.com/activities/hello-world/): A basic introduction to GitHub concepts and workflow.


