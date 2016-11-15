+++
date = "2015-06-09T00:00:00-05:00"
draft = false
slug = "0-9-0"
title = "Uchiwa 0.9.0"
+++

We're happy to announce the release of Uchiwa 0.9.0. This new version introduces some new features and a lot of improvements behind the scene.

You can [download Uchiwa 0.9.0](https://uchiwa.io/#/download) right now and [view the changelog](https://github.com/sensu/uchiwa/blob/master/CHANGELOG.md#090-2015-06-09). It will be available for download on the Sensu repositories soon.

### Vendoring dependencies
This will mainly impact the users that are running Uchiwa from the source. Uchiwa now uses [Godep](https://github.com/tools/godep) to manage the project dependencies. We highly recommend you to use *godep* to run Uchiwa or build your own packages in order to make sure you are using the right dependencies at any time. The [Uchiwa documentation](http://docs.uchiwa.io/en/latest/getting-started/#from-source) has been updated to reflect this new change.

### The search inbox now display a result count
A gif is worth a thousand words.

![](/images/0-9-0-result_count.gif)

### Filter events by check
A new filter is now available on the *events* view, which allow you to display all events related to a specific check.

### Display the output for all checks
This is a change that was introduced with Sensu 0.18.0 and Uchiwa users can now take advantage of it. You will now be able to see the last output of a successful check, which was previously only possible with checks associated to an event.

Go [see the changelog](https://github.com/sensu/uchiwa/blob/master/CHANGELOG.md#090-2015-06-09) for more changes!
