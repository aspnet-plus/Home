# How to contribute

One of the easiest ways to contribute is to participate in discussions and discuss issues. You can also contribute by submitting pull requests with code changes.


## General feedback and discussions?
Please start a discussion on the [Home repo issue tracker](https://github.com/aspnet-plus/Home/issues).


## Bugs and feature requests?
Please log a new issue in the appropriate GitHub repo. 

Here are some common repos:

* [AspNet.Plus.Infrastructure](https://github.com/aspnet-plus/AspNet.Plus.Infrastructure)

Or browse the full list of repos in the [aspnet-plus](https://github.com/aspnet-plus/) organization.


## Other discussions
Our team members also monitor several other discussion forums via Gitter:

* [Gitter AspNet.Plus.Infrastructure](https://gitter.im/aspnet-plus/AspNet.Plus.Infrastructure) 


## Filing issues
The best way to get your bug fixed is to be as detailed as you can be about the problem.
Providing a minimal project with steps to reproduce the problem is ideal.
Here are questions you can answer before you file a bug to make sure you're not missing any important information.

1. Did you read the [documentation](https://github.com/aspnet-plus/home/wiki)?
2. Did you include the snippet of broken code in the issue?
3. What are the *EXACT* steps to reproduce this problem?
4. What package versions are you using (you can see these in the `project.json` file)?
5. What operating system are you using?
6. What version of IIS are you using?

GitHub supports [markdown](https://help.github.com/articles/github-flavored-markdown/), so when filing bugs make sure you check the formatting before clicking submit.


## Contributing code and content
Before contributing, make sure you can build the code. Familiarize yourself with the project workflow and our coding conventions. If you don't know what a pull request is read this article: [Using Pull Request](https://help.github.com/articles/using-pull-requests).

Here's a few things you should always do when making changes to the code base:

**Engineering guidelines**

The coding, style, and general engineering guidelines are published on the [Engineering guidelines](https://github.com/aspnet-plus/Home/wiki/Engineering-guidelines) page.

**Commit/Pull Request Format**

```
Summary of the changes (Less than 80 chars)
 - Detail 1
 - Detail 2

Addresses #bugnumber (in this specific format)
```

**Tests**

-  Tests need to be provided for every bug/feature that is completed.
-  Tests only need to be present for issues that need to be verified by QA (e.g. not tasks)
-  If there is a scenario that is far too hard to test there does not need to be a test for it.
  - "Too hard" is determined by the team as a whole.
