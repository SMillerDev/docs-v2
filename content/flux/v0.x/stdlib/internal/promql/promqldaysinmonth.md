---
title: promql.promqlDaysInMonth() function
description: >
  `promql.promqlDaysInMonth()` implements functionality equivalent to
  [PromQL's `days_in_month()` function](https://prometheus.io/docs/prometheus/latest/querying/functions/#days_in_month).
menu:
  flux_0_x_ref:
    name: promql.promqlDaysInMonth
    parent: internal/promql
    identifier: internal/promql/promqlDaysInMonth
weight: 201
---

<!------------------------------------------------------------------------------

IMPORTANT: This page was generated from comments in the Flux source code. Any
edits made directly to this page will be overwritten the next time the
documentation is generated. 

To make updates to this documentation, update the function comments above the
function definition in the Flux source code:

https://github.com/influxdata/flux/blob/master/stdlib/internal/promql/promql.flux#L40-L40

Contributing to Flux: https://github.com/influxdata/flux#contributing
Fluxdoc syntax: https://github.com/influxdata/flux/blob/master/docs/fluxdoc.md

------------------------------------------------------------------------------->

`promql.promqlDaysInMonth()` implements functionality equivalent to
[PromQL's `days_in_month()` function](https://prometheus.io/docs/prometheus/latest/querying/functions/#days_in_month).



##### Function type signature

```js
(timestamp: float) => float
```

{{% caption %}}For more information, see [Function type signatures](/flux/v0.x/function-type-signatures/).{{% /caption %}}

## Parameters

### timestamp
({{< req >}})
Time as a floating point value.



