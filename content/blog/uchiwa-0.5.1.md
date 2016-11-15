+++
date = "2015-02-21T00:00:00-05:00"
draft = false
slug = "0-5-1"
title = "Uchiwa 0.5.1"
+++

We're happy to announce the release of Uchiwa 0.5.1! This is a small bug fix release but since Uchiwa 0.5.0  was never officially released due to some build issues, it also contains a lot of new exciting features.

You can [download Uchiwa 0.5.1](https://uchiwa.io/#/download) right now and [view the changelog](https://github.com/sensu/uchiwa/blob/master/CHANGELOG.md#051-2015-02-21). It should also be available for download on the Sensu repositories soon.


Please [report](https://github.com/sensu/uchiwa/issues) any issue you may find.

#### Two projects, one dashboard

With the 0.5.0 release, Uchiwa has been divided into two distinct repositories. For more information, read the [blog post](http://blog.uchiwa.io/two-projects-one-dashboard/).

#### Contribute to the Uchiwa docs
All documentation regarding Uchiwa has been moved to [docs.uchiwa.io](http://docs.uchiwa.io/en/latest/). You can now start contributing to the documentation by forking the [uchiwa-docs repository](https://github.com/palourde/uchiwa-docs).

#### Improved authentication
The basic http authentication method previously used has been replaced with JSON Web Tokens (JWT), which allows us to implement a login page instead of a dialog box.

![](/images/0-5-1-login.png)

#### Aggregates
You can now list your aggregate checks directly from Uchiwa, using the *Aggregates* view. You can also preview the result of a particular aggregate check that ran at a specific time within the same view.

![](/images/0-5-1-aggregates.png)

#### Custom date for stashes
A fifth option is now available during stash creation in order to allow a custom expiration date by manually entering the desired value.

![](/images/0-5-1-expiration.png)

#### Silenced clients filter
The option *Silenced Clients* has been added to the *Hide*  dropdown menu on the *Events* view, which will hide any events associated to a client that has already been silenced. In addition to this change, the client acknowledgment status is now also shown beside the source name.
