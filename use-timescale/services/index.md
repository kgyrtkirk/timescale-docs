---
title: Timescale services
excerpt: Learn more about Timescale services
products: [cloud]
keywords: [services]
cloud_ui:
    path:
        - [services]
    priority: 1
---

import CloudIntro from "versionContent/_partials/_cloud-intro.mdx";

# Timescale services

<CloudIntro />

## Timescale Terraform provider

The [Timescale Terraform provider][terraform-provider] provides configuration
management resources for Timescale. You can use it to create, rename, resize,
delete, and import service. For more information about the supported service
configurations and operations, see
[Timescale Terraform provider documentation][terraform-provider-docs].

### Learn more about Timescale

Read about Timescale features in the documentation:

*   Create your first [hypertable][hypertable-info].
*   Run your first query using [time_bucket()][time-bucket-info].
*   Trying more advanced time-series functions, starting with
    [gap filling][gap-filling-info] or [real-time aggregates][aggregates-info].

### Keep testing during your free trial

You're now on your way to a great start with Timescale.

You have an unthrottled, 30-day free trial with Timescale to continue to
test your use case. Before the end of your trial, make sure you add your credit
card information. This ensures a smooth transition after your trial period
concludes.

If you have any questions, you can
[join our community Slack group][slack-info]
or [contact us][contact-timescale] directly.

## Advanced configuration

Timescale is a versatile hosting service that provides a growing list of
advanced features for your PostgreSQL and time-series data workloads.

For additional documentation on how to:

*   [Resize compute and storage][resize] at any time
*   [Customize your database configuration][configuration] easily

[aggregates-info]: /getting-started/:currentVersion:/create-cagg
[configuration]: /use-timescale/:currentVersion:/configuration/
[contact-timescale]: https://www.timescale.com/contact
[gap-filling-info]: /use-timescale/:currentVersion:/query-data/advanced-analytic-queries#gap-filling
[hypertable-info]: /use-timescale/:currentVersion:/hypertables
[resize]: /use-timescale/:currentVersion:/resources/autoscaling/
[slack-info]: https://slack-login.timescale.com
[time-bucket-info]: /use-timescale/:currentVersion:/query-data/advanced-analytic-queries#time-bucket
[terraform-provider-docs]: https://registry.terraform.io/providers/timescale/timescale/latest/docs
[terraform-provider]: https://registry.terraform.io/providers/timescale/timescale/latest/
