# Contributing to The Art of Tech: Not playing with a Full Tech

We love your input! We want to make contributing to this project as easy and transparent as possible, whether it's:

- Reporting a bug
- Discussing the current state of the code
- Submitting a fix
- Proposing new features
- Becoming a maintainer

When contributing to this repository, please first discuss the change you wish to make with any maintainer of this repository via Issue,
Discussions before requesting a change via Pull Request (PR).

## We Develop with GitHub
We use GitHub to host code, to track issues and feature requests, as well as accept pull requests.  All changes to our code and documentation happen through [Github Flow](https://guides.github.com/introduction/flow/index.html), 

Pull requests are the best way to propose changes to the codebase (we use [Github Flow](https://guides.github.com/introduction/flow/index.html)). We actively welcome your pull requests:

1. Fork the repo and create your branch from `master`.
2. If you've added code that should be tested, add tests and or workflows.
3. If you've changed APIs, update the documentation.
4. Ensure the test suite passes.
5. Make sure your code lints.
6. Issue that pull request!

## Branches

We use the following branches:

- main (working branch)
- master (permanent & for production release)
- test (Untested code ready for review and QC/QA)
- feature (new features)
- bugfix (for patching small bugs)
- hotfix (for fixes needed ASAP)
- user (specifically user assigned tasks)

## Editors & IDE's

We allow the use of any IDE or editor you wish.  There are some configurations and settings files in [Config](https://github.com/taotnpwaft/projects/configs)
If you find any issues with the configuration.

## Language Support

We normally work with:

- Ajax
- CSS3
- HTML5
- JavaScript
- jQuery
- PHP
- Markdown
- XML
- C#

So your editor or IDE should be set up to work with these languages according to their style guides.

## Code Review Process

During the code review process we will look for the following cases

- Are there any obvious typographical and logic errors in the code?
- Looking at the requirements, are all cases fully implemented?
- Does the new code conform to existing style guidelines?
- Has the code been tested? 
- It is not suggested to review more than 200-400 lines of code at once.  

## Report bugs using Github's Issues tab

We use GitHub issues to track public bugs. Report a bug by opening an issue it's that easy! 
To open an issue in the project you are working on, Click on the `Issues` tab in the repository.

## Bug Reports

A bug is a _demonstrable problem_ that is caused by the code in the repository.
Good bug reports are extremely helpful, so thanks!

Bug Reports tend to have:

- A quick summary and/or background
- Steps to reproduce
- Be specific!
- Give sample code if you can. 
- What you expected would happen
- What actually happens
- Notes (possibly including why you think this might be happening, or stuff you tried that didn't work)

People *love* thorough bug reports. I'm not even kidding.

## License

By contributing, you agree that your contributions will be licensed under its GPL v3.0 License.

## Testing your code

[TODO] Insert documentation for code QA/QC workflows, unit tests and testing frameworks.

## Pull Request Process

1. Update the CHANGELOG.md with details of changes


The versioning scheme we use is [SemVer](http://semver.org/).

Some things to think about:

1. Respect peoples' time.

2. Provide constructive feedback.

3. State exactly what needs to be improved.

4. Don't just pray or hope that the code works.

5. Be reasonable about `Temporary` code, it may or may not make it to final.

6. Big Picture your request. Remember, Code is not the line you write, but how the line integrates with and provides benefit to the application itself.

7. Review the code in chunks of 200-400 lines at the most.

8. Add comments on your pull request to help guide the reviewer

9. Make it visual if possible. Add some screenshots if you believe that will help.

## Issues and labels

Our GitHub Project management utilizes several labels to help organize and identify issues. Here's what they represent and how we use them:

- `documentation` - Issues for improving or updating our documentation.
- `help wanted` - Issues we need or would love help from the community to resolve.

## Feature requests

Feature requests are welcome. But take a moment to find out whether your idea
fits with the scope and aims of the project. It's up to *you* to make a strong
case to convince the project's developers of the merits of this feature. Please
provide as much detail and context as possible.


**Please ask first** before embarking on any **significant** pull request (e.g.
implementing features, refactoring code, porting to a different language), etc.
You risk spending a lot of time working on something that the
project's developers might not want to merge into the project. For trivial
things, or things that don't require a lot of your time, you can go ahead and
make a PR.

Please adhere to the [coding guidelines](#code-guidelines) used throughout the
project (indentation, accurate comments, etc.) and any other requirements
(such as test coverage).

Adhering to the following process is the best way to get your work
included in the project:

1. [Fork](https://help.github.com/articles/fork-a-repo/) the project, clone your fork,
   and configure the remotes:

   ```bash
   # Clone your fork of the repo into the current directory
   git clone https://github.com/<your-username>/taotnpwaft.git
   # Navigate to the newly cloned directory
   cd taotnpwaft
   # Assign the original repo to a remote called "upstream"
   git remote add upstream https://github.com/twbs/bootstrap.git
   ```

2. If you cloned a while ago, get the latest changes from upstream:

   ```bash
   git checkout main
   git pull upstream main
   ```

3. Create a new topic branch (off the main project development branch) to
   contain your feature, change, or fix:

   ```bash
   git checkout -b <topic-branch-name>
   ```

4. Commit your changes in logical chunks. Please adhere to these [git commit
   message guidelines](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
   or your code is unlikely be merged into the main project. Use Git's
   [interactive rebase](https://help.github.com/articles/about-git-rebase/)
   feature to tidy up your commits before making them public.

5. Locally merge (or rebase) the upstream development branch into your topic branch:

   ```bash
   git pull [--rebase] upstream main
   ```

6. Push your topic branch up to your fork:

   ```bash
   git push origin <topic-branch-name>
   ```

7. [Open a Pull Request](https://help.github.com/articles/about-pull-requests/)
    with a clear title and description against the `main` branch.

## Community Support Policy

Project maintainers will aim to respond within 3 business days to get a meaningful response for any new issues.

We have fully adopted the use of the Contributor Covenant guidelines.  Please review the latest Contributor Covenant.

