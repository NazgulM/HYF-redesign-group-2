# Hack Your Future Rebuild

A website to anyone who wants to know and learn about coding

## Table of contents

- [Hack Your Future Rebuild](#hack-your-future-rebuild)
  - [Table of contents](#table-of-contents)
  - [General info](#general-info)
  - [Screenshots](#screenshots)
  - [Technologies](#technologies)
  - [Setup](#setup)
  - [Code Examples](#code-examples)
  - [Features](#features)
  - [Status](#status)
  - [Inspiration](#inspiration)
  - [Collaboration](#collaboration)
  - [Coaches](#coaches)
  - [Instructions for use](#instructions-for-use)
  - [Code Quality Checks](#code-quality-checks)
  - [Continuous Integration (CI)](#continuous-integration-ci)
  - [Repo Setup](#repo-setup)

## General info

A rebuild website of Hack Your Future by using CSS and HTMl. Recreate the
website with our own code, and modify some stuff as a preference.

## Screenshots

![Example screenshot](./assets/homepage.png)

## Technologies

- HTML
- CSS
- VSC code
- [Bootstrap 5](https://getbootstrap.com/docs/5.0/getting-started/introduction/)

## Setup

- `npm run start`

## Code Examples

![Example screenshot](./assets/code-example.png)

## Features

- Responsive Website
- CSS Grid
- Flexbox

## Status

Project is: _in progress_

## Inspiration

Project by [Hack Your Future Belgium](https://hackyourfuture.be/)

## Collaboration

- [Carsiti](https://github.com/Carsiti)
- [Cristobal_lopez](https://github.com/cristobal-lopez)
- [Ha](https://github.com/hadoan149)
- [Madhu](https://github.com/MadhuMNG)
- [Ricardo](https://github.com/TheRick88)
- [Swapna](https://github.com/SWAPNACHEMBOTH)
  
## Coaches

- [Bermarte](https://github.com/bermarte)
- [Tamer](https://github.com/talmurshidi)
  
## Instructions for use

<details>
  <summary>Getting Started</summary>

<!-- a guide to using this repository -->

1. `git clone git@github.com:HackYourFutureBelgium/template-markdown.git`
2. `cd template-markdown`
3. `npm install`

## Code Quality Checks

- `npm run format`: Makes sure all the code in this repository is well-formatted
  (looks good).
- `npm run lint:ls`: Checks to make sure all folder and file names match the
  repository conventions.
- `npm run lint:md`: Will lint all of the Markdown files in this repository.
- `npm run lint:css`: Will lint all of the CSS files in this repository.
- `npm run validate:html`: Validates all HTML files in your project.
- `npm run spell-check`: Goes through all the files in this repository looking
  for words it doesn't recognize. Just because it says something is a mistake
  doesn't mean it is! It doesn't know every word in the world. You can add new
  correct words to the [./.cspell.json](./.cspell.json) file so they won't cause
  an error.
- `npm run accessibility -- ./path/to/file.html`: Runs an accessibility analysis
  on all HTML files in the given path and writes the report to
  `/accessibility_report`

## Continuous Integration (CI)

When you open a PR to `main`/`master` in your repository, GitHub will
automatically do a linting check on the code in this repository, you can see
this in the[./.github/workflows/lint.yml](./.github/workflows/lint.yml) file.

If the linting fails, you will not be able to merge the PR. You can double check
that your code will pass before pushing by running the code quality scripts
locally.

## Repo Setup

- Give each member _write_ access to the repo (if it's a group project)
- Turn on GitHub Pages and put a link to your website in the repo's description
- Turn on GitHub Actions
- in the _Branches_ section of your repo's settings make sure:
  - The repository
    [requires a review](https://github.blog/2018-03-23-require-multiple-reviewers/)
    before pull requests can be merged.
  - The `master`/`main` branch must "_Require status checks to pass before
    merging_"
  - The `master`/`main` branch must "_Require require branches to be up to date
    before merging_"

</details>
