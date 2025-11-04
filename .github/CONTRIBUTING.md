# Contributing

## Issues and Discussions

### When to use issues

Use issues to:

* Report bugs
* Report security vulnerabilities (see [SECURITY.md](./SECURITY.md))
* Report issues with documentation (Missing links, inconsistent naming, suggest rewording)

### When to use Discussions

Use discussions to:

* View announcements
* Ask questions
* Suggest new features
* Respond to polls

## Pull Requests

If you have a good idea for an addition to the code or documentation, please create a new fork of the repository and submit a pull request.

Usually, pull requests made to this repository by outside contributors won't be merged, but if we think it's a good addition or something we missed in documentation, there is a possibility that it will be merged.

Below is more information about the workflow for submitting pull request, and guidelines for code and documentation.

### Workflow

1. Fork and clone this repository.
2. Create a new branch in your fork based off the **main** branch.
3. Make your changes.
4. Commit your changes, and push them.
5. Submit a pull request.

### Documentation

#### Changes

##### Wanted Changes

1. Fixes to incorrect statements or inaccuracies within the documenation.
2. Rewording or extending documentation to clarify unclear wording or complicated explanations.
3. Additions that fill gaps or missing pieces in the current documentation.
4. Fixing of spelling and grammatical errors in the documentation.

##### Unwanted Changes

1. Whitespace or formatting changes.
2. Subjective wording changes.
3. Modifications to the overall structure and format of the documentation.
4. Additions that replicate or needlessly restructure current documentation.
5. Additions that document unreleased product functionality.

#### Guidelines

Below are a few guidelines considered by us when reviewing pull requests:

* Links in the documentation work.
* H6 headings are above all tables and code blocks, so they can be referenced in links.
* There are no unused images in the pull request.

### Code

#### Changes

##### Wanted Changes

1. Small bug fixes

##### Unwanted Changes

1. Whitespace or formatting changes.
2. Subjective changes.
3. Modifications to the overall structure of the code.
4. Additions that replicate existing features.

#### Guidelines

Below are a few guidelines considered by us when reviewing pull requests:

* Everything should follow our linter rules as closely as possible and linting tests must pass. If it's not possible for a line of code to follow a linter rule, that rule should be disabled for that line of code only.
