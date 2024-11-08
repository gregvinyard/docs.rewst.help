# Incoming & Outgoing Domains & IPs

## Outgoing IP Addresses

Rewst uses static NAT Gateway IPs for outbound connections from our services hosted in AWS. These IPs should be included in any necessary allow lists for outbound connections:

* North America:&#x20;
  * US
    * `13.58.15.14`
    * `18.218.107.198`
    * `3.139.170.31`
  * PDX
    * `44.230.172.45`
    * `44.233.44.83`
    * `50.112.50.172`
* Europe:
  * UK
    * `18.132.221.226`
    * `18.171.196.2`
    * `3.9.62.134`
  * DE
    * `3.67.166.23`
    * `3.69.14.222`
    * `3.76.128.23`
* Asia
  * `13.210.158.91`
  * `13.237.143.171`
  * `52.65.55.149`

## Hostnames with Dynamic IPs

For the following services, Rewst employs application load balancers, resulting in dynamic IP addresses. We recommend using DNS names when adding these services to your allow list.

### North America

* `app.rewst.io`: Front-end web application for user logins.
* `engine.rewst.io`: Back-end application handling workflow execution, including webhooks.
* `api.rewst.io`: API for app and engine communication.

### Europe

* `app.eu.rewst.io`: Front-end web application for user logins.
* `engine.eu.rewst.io`: Back-end application handling workflow execution, including webhooks.
* `api.eu.rewst.io`: API for app and engine communication.

### Third-Party Services

* `featureassets.org`: A Statsig API for feature flagging
* `prodregistryv2.org`: A Statsig API for feature flagging

## Wildcard Domains

Rewst customers may create subdomains (`*.rew.st`) to host their apps. These should also be considered in your allow lists based on your integration needs.
