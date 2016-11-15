+++
date = "2016-11-15T12:00:00-05:00"
draft = false
slug = "0-20-0"
title = "Uchiwa 0.20.0"
author = "Simon Plourde"
+++

We're happy to announce the release of Uchiwa 0.20.0, which introduces some
interesting features and important behind the scenes changes.

You can [download Uchiwa 0.20.0](https://uchiwa.io/#/download) right now and
[view the changelog](https://github.com/sensu/uchiwa/blob/master/CHANGELOG.md#0200-2016-11-14).

Here's a quick overview of some of the new features:

## Users-level configuration
Uchiwa can now be further customized, from the **date format** to the **default
theme**. These are some of the most requested features we received.

Head over to the
[Uchiwa documentation](https://docs.uchiwa.io/getting-started/configuration/#users-options)
to learn how to get started with these new options.

## Regular Expressions and key:value search queries
Filtering in Uchiwa just got smarter, because we understand that no two Sensu installations
are alike and we hope to bring more flexibility in Uchiwa to support that fact.

Starting with 0.20, you can now use regexes in your searches and also optionally
specify a field against which a value should be matched.

We added some examples in the
[Uchiwa documentation](https://docs.uchiwa.io/guides/search-queries/).

## Conclusion
These are just some of the new changes, we invite you to consult the
[changelog](https://github.com/sensu/uchiwa/blob/master/CHANGELOG.md) for the
complete list and we hope you enjoy this new release!
