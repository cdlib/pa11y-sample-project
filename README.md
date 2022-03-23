# Pa11y Sample Project

[![Accessibility](https://github.com/cdlib/pa11y-sample-project/actions/workflows/accessibility.yml/badge.svg)](https://github.com/cdlib/pa11y-sample-project/actions/workflows/accessibility.yml)

A demonstration of the [Pa11y](https://github.com/pa11y/pa11y) accessibility tool, including sample web pages with and without accessibility errors to test with Pa11y.

View at: https://cdlib.github.io/pa11y-sample-project

## Installation

Requires Node, npm.

Run `npm install`

## Developing

Run `npm run serve`

This will watch and compile **.pug** and **/styles/.scss** files as you work on them.

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
