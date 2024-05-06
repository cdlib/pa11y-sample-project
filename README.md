# Pa11y Sample Project

**This repository is no longer used or maintained and is now archived.**

[![Accessibility](https://github.com/cdlib/pa11y-sample-project/actions/workflows/accessibility.yml/badge.svg)](https://github.com/cdlib/pa11y-sample-project/actions/workflows/accessibility.yml)

A demonstration of the [Pa11y](https://github.com/pa11y/pa11y) accessibility tool, including sample web pages with and without accessibility errors to test with Pa11y.

View at: https://cdlib.github.io/pa11y-sample-project

## Installation

Requires Node, npm and Font Awesome Pro token

1. Add the Font Awesome Pro token as a [GitHub Actions secret](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/GitHub-Actions-Secrets-Example-Token-Tutorial) named `FONTAWESOME_TOKEN`.

2. Add a **.npmrc** file within the project root using the [Per-Project](https://fontawesome.com/v5/docs/web/setup/use-package-managers#per-project) settings for Font Awesome Pro, including your token. This file is automatically ignored by Git and should not be committed.

3. Run `npm install`

## Developing

Run `npm run serve`

This will watch and compile **.pug** and **/styles/.css** files as you work on them.

This project's website will be served locally at http://localhost:1234.

## Building

Run `npm run build`

This will create a finished build of all components and pages to **/dist/**

## Publishing to GitHub Pages

This requires [GitHub Pages](https://pages.github.com) to be configured.

Run `npm run publish` to publish a finished build of this project to GitHub Pages.

## Running Pa11y-ci Manually on Sample Pages

1. Run `npm run test-pa11y`

2. Pa11y-ci test results will be logged to your CLI.

## Running Pa11y-ci Automatically on Push to GitHub

Pa11y-ci will automatically run as part of [this GitHub Actions workflow](https://github.com/cdlib/pa11y-sample-project/blob/main/.github/workflows/accessibility.yml) with a code push to any branch within the repository.
