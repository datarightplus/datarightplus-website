# CDR+ Website

We use [Hugo](https://gohugo.io/) to format and generate our website, the
[Docsy](https://github.com/google/docsy) theme for styling and site structure,
and [Cloudflare Pages](https://pages.cloudflare.com/) to manage the deployment of the site.
Hugo is an open-source static site generator that provides us with templates,
content organisation in a standard directory structure, and a website generation
engine. You write the pages in Markdown (or HTML if you want), and Hugo wraps them up into a website.

All submissions, including submissions by project members, require review. We
use GitHub pull requests for this purpose. Consult
[GitHub Help](https://help.github.com/articles/about-pull-requests/) for more
information on using pull requests.

## Managing the Documentation

Here's a quick guide to updating the docs.

1. Fork the [CDR+ Website repo](https://github.com/bizaio/cdrplus-website) on GitHub.
1. Make your changes and send a pull request (PR).
1. If you're not yet ready for a review, add "WIP" to the PR name to indicate
   it's a work in progress. (**Don't** add the Hugo property
   "draft = true" to the page front matter, because that prevents the
   auto-deployment of the content preview described in the next point.)
1. Wait for the automated PR workflow to complete successfully.
1. Continue updating your doc and pushing your changes until you're happy with
   the content.
1. When you're ready for a review, add a comment to the PR, and remove any
   "WIP" markers.

## Updating a single page

If you've just spotted something you'd like to change while using the docs, Docsy has a shortcut for you:

1. Click **Edit this page** in the top right hand corner of the page.
1. If you don't already have an up to date fork of the project repo, you are prompted to get one - click **Fork this repository and propose changes** or **Update your Fork** to get an up to date version of the project to edit. The appropriate page in your fork is displayed in edit mode.
1. Follow the rest of the [Managing the Documentation](#managing-the-documentation) process above to make, preview, and propose your changes.

## Previewing your changes locally

If you want to run your own local Hugo server to preview your changes as you work:

1. [Install Hugo](https://gohugo.io/categories/installation/) and any other tools you need. You'll need at least **Hugo version 0.97.3** (we recommend using the most recent available version), and it must be the **extended** version, which supports SCSS.
1. Fork the [CDR+ Website repo](https://github.com/bizaio/cdrplus-website) repo into your own project, then create a local copy using `git clone`. Don’t forget to use `--recurse-submodules` or you won’t pull down some of the code you need to generate a working site.

    ```
    git clone --recurse-submodules --depth 1 https://github.com/bizaio/cdrplus-website.git
    ```

1. Run `hugo server` in the site root directory. By default your site will be available at http://localhost:1313/. Now that you're serving your site locally, Hugo will watch for changes to the content and automatically refresh your site.
1. Continue with the usual GitHub workflow to edit files, commit them, push the
   changes up to your fork, and create a pull request.

