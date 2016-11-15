+++
date = "2015-11-22T00:00:00-05:00"
draft = false
slug = "0-13-0"
title = "Uchiwa 0.13.0"
+++

We're happy to announce the release of Uchiwa 0.13.0. This new version introduces two important features designed for high availability.

You can [download Uchiwa 0.13.0](https://uchiwa.io/#/download) right now and [view the changelog](https://github.com/sensu/uchiwa/blob/master/CHANGELOG.md#0130-2015-11-22). It will be available for download on the Sensu repositories soon.

### Datacenters high availability
You can now define multiple Sensu APIs by datacenter in order to provide failover and rudimentary load balancing between these APIs, which eliminates the latest single point of failure in Uchiwa for a truly redundant environment.

Learn how to get started with the datacenter high availability by heading to the [Uchiwa docs](http://docs.uchiwa.io/en/latest/configuration/sensu/#datacenters-high-availability).

### Static RSA keys
It's now possible to use your own 2048-bit RSA key for generating and validating the signatures of the JSON Web Tokens (JWT) used by the authentication module.

By default, Uchiwa generates a temporary key during its launch, which is later destroyed once the process is stopped or restarted. This behavior is problematic when multiple instances of Uchiwa are used behind a load balancer or if the Uchiwa process needs to be frequently restarted.

To start using your own keys, consult the [Uchiwa docs](http://docs.uchiwa.io/en/latest/configuration/sensu/#datacenters-high-availability).

Go [see the changelog](https://github.com/sensu/uchiwa/blob/master/CHANGELOG.md#0130-2015-11-22) for more changes!
