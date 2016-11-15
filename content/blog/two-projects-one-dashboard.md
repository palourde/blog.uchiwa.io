+++
date = "2015-01-25T00:00:00-05:00"
draft = false
slug = "two-projects-one-dashboard"
title = "Two Projects, One Dashboard"
+++

In order to improve Uchiwa's modularity and isolate two softwares written in different languages, the dashboard is now divided into two distinct repositories.

### [Uchiwa](https://github.com/sensu/uchiwa)

The Uchiwa repository now contains the backend of Uchiwa, which consists of a Go web server that queries every Sensu API and exposes the results through its own API.

### [Uchiwa-web](https://github.com/sensu/uchiwa-web)

The new Uchiwa-web repository is hosting the web dashboard, which is written with the AngularJS framework. Its job is to query the backend API and present the information in the most useful way possible.

### What's the impact?

Unless you want to contribute to Uchiwa, it does not affect you since Uchiwa-web is now included as a bower component. Make sure to run <code>npm install --production</code> after pulling the last changes, if you installed Uchiwa from the source.

If you wish to start contributing and improving Uchiwa, we invite you to consult the [Uchiwa documentation](https://uchiwa.io/#/docs/contributing) in order to properly setup your environment.
