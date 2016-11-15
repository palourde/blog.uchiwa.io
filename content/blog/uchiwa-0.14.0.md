+++
date = "2016-01-07T00:00:00-05:00"
draft = false
slug = "0-14-0"
title = "Uchiwa 0.14.0"
+++

We're happy to announce the release of Uchiwa 0.14.0, which introduces two new Sensu features and configuration directories.

You can [download Uchiwa 0.14.0](https://uchiwa.io/#/download) right now and [view the changelog](https://github.com/sensu/uchiwa/blob/master/CHANGELOG.md#0140-2016-01-05).

### Configuration Directories

The Uchiwa configuration can now be loaded partially or fully from configuration snippets located within one or multiple directories. If you upgrade using the Uchiwa packages, you can already start using the `/etc/sensu/dashboard.d/` directory.

The full documentation is available in the [Uchiwa docs](http://docs.uchiwa.io/en/latest/configuration/overview/#configuration-directories).

### Deleting Check Results

This new Sensu feature was introduced with [Sensu 0.21.0](https://github.com/sensu/sensu/blob/master/CHANGELOG.md#features).

> This feature allows users to clean up "stale" check result data for checks that have been removed.

Learn how to delete a check result by heading to the [Uchiwa docs](http://docs.uchiwa.io/en/latest/features/deleting-check-results/).

### Issuing Check Requests

This Sensu feature has been around for a long time and is finally available directly from Uchiwa.

You can now manually issue a check request from the dashboard, which is particularly helpful for checks that are not scheduled to run frequently.

Learn how to issue a check request by heading to the [Uchiwa docs](http://docs.uchiwa.io/en/latest/features/issuing-check-requests/).
