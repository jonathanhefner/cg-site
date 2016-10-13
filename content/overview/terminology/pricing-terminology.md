---
menu:
  main:
    parent: terminology
title: Terms We Use in Pricing
weight: 20
---

We use these terms among others to define a number of products and services we offer. Our billing structure is built around them. We will add additional terms if confusion about them comes up frequently in questions from partner agencies or the public.

## System

A "System" roughly corresponds to a product or project team, including all the individual spaces, apps, and services necessary to realize their service, across as many environments as needed.

A system maps to an [“org” in Cloud Foundry](http://docs.cloudfoundry.org/concepts/roles.html#orgs).

## Support {#support}

“Support” is support to use the platform as intended, on a best-effort basis. We have no existing service-level agreement. We plan to always publish metrics that give agencies the ability to make an informed choice about whether to use cloud.gov or an alternative PaaS solution based on our actual track record.

## Consulting

“Consulting” is advice, development, documentation, etc. that is custom or specific the context of your application, system, or organization. If the outcome of the activity will not be reusable for our entire community of users, it’s consulting. Base platform fees for cloud.gov do not include consulting, and 18F does not offer cloud-focused consulting outside of projects directly undertaken by 18F for delivery or consulting on behalf of a partner agency.

## Access package

The "access package" component covers access to the cloud.gov Platform as a Service (PaaS) and [support]({{< relref "#support" >}}) for it to stay up and available in its current form, as well as expanded over time. The access package component is paid 12 months at a time, and scales along with the number of systems being hosted and the impact level of the systems being launched on the platform, as defined by [Federal Information Processing Standard (FIPS) 199](http://csrc.nist.gov/publications/fips/fips199/FIPS-PUB-199-final.pdf).

The access package component is "non-severable" and therefore non-refundable. As a result, a payment in one fiscal year does not expire regardless of the status of the underlying appropriation.

## Resource usage

To support tenant applications and managed service instances, cloud.gov allocates resources (like compute nodes and memory) from an underlying IaaS. What we charge for this component covers the costs for the resources that cloud.gov allocates to hosted systems and teams. It also includes a small margin that covers our labor in managing those resources.

Resource usage fees on-demand are understood to be “severable” as they can be controlled in a self-service manner by provisioning more or fewer apps, and therefore must be treated accordingly.

Agencies can purchase reserved capacity via 18F as well, which is understood to be “non-severable”.

## Managed services

"Managed services" are commodity services (databases, caches, message queues, storage, etc.) which cloud.gov will spin up (or down) instantly on your behalf. These services reduce the ops responsibility for your application team so they can concentrate on their application rather than plumbing. 

Each managed service incurs some resource usage and platform support overhead. The managed service fees ensure we can cover our costs to provide them to you. The fee varies among services. In some cases managed services include alternative “plans” can be selected that reflect resilience, performance, and cost trade-offs.

In many cases, the pricing for managed services is not yet available. This is because we are measuring their initial usage to determine what we will need to charge. We are doing more analysis of the costs we’re observing (both the cost of the IaaS layer and the cost of our support), and aim to set explicit prices for all managed services by the end of March 2016.

