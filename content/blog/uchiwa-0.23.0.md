+++
date = "2017-03-24T12:00:00-05:00"
draft = false
slug = "0-23-0"
title = "Uchiwa 0.23.0"
author = "Simon Plourde"
+++

We're happy to announce the release of Uchiwa 0.23.0, which introduces a brand
new interface for silencing and support of new Sensu features introduced with
0.28.

You can [download Uchiwa 0.23.0](https://uchiwa.io/#/download) right now and
[view the changelog](https://github.com/sensu/uchiwa/blob/master/CHANGELOG.md#0230-2017-03-24).

## Silencing
The silencing modal window has been completely redesigned to let you fully take
advantage of the new built-in silencing capabilities.

![](/images/0-23-0-silencing.gif)

## Editing the client registry
[Sensu proxy clients](https://sensuapp.org/docs/latest/reference/clients.html#proxy-clients)
can now be edited directly from Uchiwa. Please note that it only applies to
clients with `keepalives:false`.

![](/images/0-23-0-client-registry.png)

## Sensu servers information
Additional information about your Sensu servers is now available in the new
datacenter view, accessible from the datacenters view. Please note that this
feature requires at least Sensu 0.28.

![](/images/0-23-0-server-info.png)

## Conclusion
These are just some of the new changes, we invite you to consult the
[changelog](https://github.com/sensu/uchiwa/blob/master/CHANGELOG.md) for the
complete list and we hope you enjoy this new release!
