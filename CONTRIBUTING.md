# Contributing Guide

Welcome! We are glad that you want to contribute to our project!

As you get started, you are in the best position to give us feedback on areas of
our project that we need help with including:

* Problems found during setting up a new developer environment
* Gaps in our Quickstart Guide or documentation
* Bugs in our automation scripts

If anything doesn't make sense, or doesn't work when you run it, please open a
bug report and let us know!

## Ways to Contribute

We welcome many different types of contributions including:

* New features
* Builds, CI/CD
* Bug fixes
* Documentation
* Issue Triage
* Answering questions on Slack/Mailing List
* Web design
* Communications / Social Media / Blog Posts
* Release management

Not everything happens through a GitHub pull request. Please contact us and let's 
discuss how we can work together. 

## Find an Issue

We have good first issues for new contributors and help wanted issues suitable
for any contributor. a `good first issue` has extra information to
help you make your first contribution. `help wanted` are issues
suitable for someone who isn't a core maintainer and is good to move onto after
your first pull request.

Sometimes there won’t be any issues with these labels. That’s ok! There is
likely still something for you to work on. If you want to contribute but you
don’t know where to start or can't find a suitable issue, you can contact us.

Once you see an issue that you'd like to work on, please post a comment saying
that you want to work on it. Something like "I want to work on this" is fine.

## Ask for Help

The best way to reach us with a question when contributing is to ask on:

* The original github issue
* The developer email

## Pull Request Lifecycle

Instead of a fixed template, use the questions below as an exercise to uncover the unwritten rules and norms your project has for both reviewers and contributors. Using your answers, write a description of what a contributor can expect during their pull request.

* When should contributors start to submit a PR - when it’s ready for review or as a work-in-progress?
* How do contributors signal that a PR is ready for review or that it’s not complete and still a work-in-progress?
* When should the contributor should expect initial review? The follow-up reviews?
* When and how should the author ping/bump when the pull request is ready for further review or appears stalled?
* How to handle stuck pull requests that you can’t seem to get reviewed?
* How to handle follow-up issues and pull requests?
* What kind of pull requests do you prefer: small scope, incremental value or feature complete?
* Do you use feature branches?
* What should contributors do if they no longer want to follow-through with the PR? Do maintainers sometimes commit to the PR directly to help get it merged? Or do maintainers close a PR if the contributor hasn’t responded in a specific time frame?
* Once a PR is merged, what is the process for it getting into the next release?
* When does a merged pull request end up in a release?


## Development Environment Setup

Provide enough information so that someone can find your project on the weekend and get set up, build the code, test it, and submit a pull request successfully without having to ask any questions. If there is a one-off tool they need to install, common error people run into, or useful script they should run, document that here.

Document any necessary tools, such as linters, or recommended IDE extensions. You don’t have to document the beginner’s guide to these tools, but how they are used within the scope of your project. This is a great place to include links to new user documentation videos and examples to get people started and understanding how to use the project

You should explain how to do at least these basic tasks:

* Get the source code
* Retrieve any dependencies
* Build the source code
* Run the project locally
* Test the source code, unit and “integration” or “end-to-end”
* Generate and preview the documentation locally

## Sign Your Commits



### DCO
Licensing is important to open source projects. It provides some assurances that
the software will continue to be available based under the terms that the
author(s) desired. We require that contributors sign off on commits submitted to
our project's repositories. The [Developer Certificate of Origin
(DCO)](https://probot.github.io/apps/dco/) is a way to certify that you wrote and
have the right to contribute the code you are submitting to the project.

You sign-off by adding the following to your commit messages. Your sign-off must
match the git user and email associated with the commit.

```
    This is my commit message

    Signed-off-by: Your Name <your.name@example.com>
```

Git has a `-s` command line option to do this automatically:

```
    git commit -s -m 'This is my commit message'
```

If you forgot to do this and have not yet pushed your changes to the remote
repository, you can amend your commit with the sign-off by running 
```
    git commit --amend -s 
```

## Pull Request Checklist

Give contributors an idea of how their pull request is evaluated and how to run those checks locally before submitting the pull request. Include both the automated and any manual checks performed by reviewers.

Providing a script in the repository and instructions for how to validate a pull request before submitting is extremely helpful to all contributors.

Below is an example project checklist and we encourage you to not only document the checklist in the CONTRIBUTING.md file but also in the GitHub pull request template.

* It passes tests: run the following command to run all of the tests locally: make build test lint
* Impacted code has new or updated tests
* Documentation created/updated
* All tests succeed when run by the CI build on a pull request before it is merged
