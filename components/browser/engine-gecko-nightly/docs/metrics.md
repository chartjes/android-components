<!-- AUTOGENERATED BY glean_parser.  DO NOT EDIT. -->

# Metrics
This document enumerates the metrics collected by this project.
This project may depend on other projects which also collect metrics.
This means you might have to go searching through the dependency tree to get a full picture of everything collected by this project.
Sorry about that.

# Pings

 - [metrics](#metrics)


## metrics
This is a built-in ping that is assembled out of the box by the Glean SDK.
See the Glean SDK documentation for the [`metrics` ping](https://mozilla.github.io/glean/book/user/pings/metrics.html).
The following metrics are added to the ping:

| Name | Type | Description | Data reviews | Extras | Expiration |
| --- | --- | --- | --- | --- | --- |
| test.glean.geckoview.streaming |[timing_distribution](https://mozilla.github.io/glean/book/user/metrics/timing_distribution.html) |A test-only, disabled metric. This is required to guarantee that a `GleanGeckoHistogramMapping` is always generated, even though the GeckoView AAR exports no metric. Please note that the data-review field below contains no review, since this metric is disabled and not allowed to collect any data.  |[1](https://bugzilla.mozilla.org/show_bug.cgi?id=1566374)||never |


<!-- AUTOGENERATED BY glean_parser.  DO NOT EDIT. -->
