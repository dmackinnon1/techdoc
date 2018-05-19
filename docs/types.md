---
title: Documentation Types
permalink: types.html
---

# Identify Documentation Types and their Relation to Code

One way of understanding different documentation processes and products is to consider the relationship between the documentation and the software. In this overview we assume three core concepts of software development:

*software release management and versioning.* Software is released according to a staged process and is versioned following practices similar to the [semantic versioning guidelines](https://semver.org/spec/v2.0.0.html).

*source code repository.* Source code is persisted in a repository that supports management and version control (ex: git/github)

*continuous integration.* Source code goes through an iterative build/test/deploy process to produce distributable artifacts. These processes can be configured to run automatically on changes to codebase or be triggered as required. (ex: Jenkins, Hudson, etc.)

The table below summarizes how various types of documentation may be embedded in the code base itself, may live alongside the code, may be in a distinct repository that is kept in sync with the code repo, or it may be detached from the code development and release cycle. 

|Embedded | Parallel | Synchronized |Decoupled|
|----------|--------|----------|---------|

