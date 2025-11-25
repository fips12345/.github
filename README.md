# .github

This repository serves as the central configuration hub for Probot apps and community health files for the organization. It contains configuration files for various GitHub Apps that automate repository management tasks, as well as templates for issues and pull requests.

## Configuration Files

This repository contains the following configuration files:

### `stale.yml`

This file configures the [probot-stale](https://github.com/probot/stale) app, which automatically marks and closes stale issues and pull requests. The configuration options are as follows:

- `daysUntilStale`: The number of days of inactivity before an issue or pull request is marked as stale.
- `daysUntilClose`: The number of days of inactivity before a stale issue or pull request is closed.
- `onlyLabels`: A list of labels that an issue or pull request must have to be considered for staleness.
- `exemptLabels`: A list of labels that will prevent an issue or pull request from being marked as stale.
- `staleLabel`: The label to apply to stale issues and pull requests.
- `markComment`: The comment to post when an issue or pull request is marked as stale.
- `closeComment`: The comment to post when a stale issue or pull request is closed.

### `first-timers.yml`

This file configures the [first-timers-bot](https://github.com/hoodiehq/first-timers-bot) app, which helps new contributors get started. The configuration options are as follows:

- `labels`: The labels to apply to the issues created by the bot.
- `template`: The path to the issue template to use for first-timer issues.

### `toc.yml`

This file configures the table of contents (TOC) generator. The configuration options are as follows:

- `bullets`: The character to use for bullet points in the TOC.

## Issue Templates

This repository contains the following issue templates:

### `first-timers-issue-template.md`

This is a template for issues that are suitable for first-time contributors. It provides a step-by-step guide to making a contribution and is used by the `first-timers-bot`.

## Contributing

Contributions to this repository are welcome. If you have any suggestions for improving the configuration or templates, please open an issue or a pull request.
