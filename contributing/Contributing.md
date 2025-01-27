# Contributing to the JustServe documentation

By participating in this project, you agree to abide by our [code of conduct](./CODE_OF_CONDUCT.md) and [community guidelines](https://www.justserve.org/about#community-guidelines). 

The JustServe documentation is written in [Asciidoc](https://docs.asciidoctor.org/asciidoc/latest/), and we use Gradle to compile that into whatever format is needed.

If you're not familiar with Asciidoc, it's easy to pick up and there are many resources available to help you learn. See [the resources section below](#resources). You dont need any familiarity with Gradle to contribute. 

## Text Editor

When writing Asciidoc, it's best to use a text editor that supports syntax highlighting and formatting. A great text editor to use is [Visual Studio Code](https://code.visualstudio.com/). You can also just write them here in the browser on GitHub! 

> [!WARNING]
> **Do not use Microsoft Word or any other word processor to edit the documentation.**
>
> Asciidoc files are not word documents and are not compatible with that editor.

## Git Best Practices

When contributing to the JustServe documentation, please follow these best practices:

<ul><li> <strong>Use feature branches</strong><br>
Create a new branch for each feature or bug fix you're working on. This keeps your changes separate from the main development branch and makes it easier to review and merge your changes.
<br><br></li>
<li><strong>Use meaningful commit messages</strong> <br>
Write a descriptive commit message that explains what you're changing and why. This helps others understand the changes you're making and makes it easier to debug issues later on.
Commit messages should conform to <a href="https://www.conventionalcommits.org">Conventional Commits</a>
<br><br></li>
<li><strong>Keep your commits small and focused to one purpose</strong> <br>
Try to keep each commit focused on a single change or feature. This makes it easier to review and test your changes.
<br><br></li>
<li><strong>Use pull requests</strong><br> When you're ready to merge your changes, create a pull request. This allows others to review and comment on your changes before they're merged into the main development branch.<br><br>

Similar to commits being focused on small, pull requests should fill a single need. i.e. refactoring existing whitespace should not be included in a pull request meant to add a new feature.
<br><br>

Changes will be merged using [rebase](https://git-scm.com/docs/git-rebase). Squash your commits prior to submitting your pull request if you want your PR squashed prior to merging.
</li>
</ul>


## Resources

If you're new to Asciidoc, here are some resources to help you get started:

* [Asciidoc Quick Reference](https://docs.asciidoctor.org/asciidoc/latest/syntax-quick-reference/)
* [Asciidoc User Manual](https://docs.asciidoctor.org/asciidoc/latest/user-manual/)
* [Asciidoc Syntax Guide](https://asciidoctor.org/docs/asciidoc-syntax-quick-reference/)
