---
title: today() function
description: >
  `today()` returns the now() timestamp truncated to the day unit.
menu:
  flux_0_x_ref:
    name: today
    parent: universe
    identifier: universe/today
weight: 101
flux/v0.x/tags: [date/time]
introduced: 0.116.0
---

<!------------------------------------------------------------------------------

IMPORTANT: This page was generated from comments in the Flux source code. Any
edits made directly to this page will be overwritten the next time the
documentation is generated. 

To make updates to this documentation, update the function comments above the
function definition in the Flux source code:

https://github.com/influxdata/flux/blob/master/stdlib/universe/universe.flux#L4743-L4743

Contributing to Flux: https://github.com/influxdata/flux#contributing
Fluxdoc syntax: https://github.com/influxdata/flux/blob/master/docs/fluxdoc.md

------------------------------------------------------------------------------->

`today()` returns the now() timestamp truncated to the day unit.



##### Function type signature

```js
() => time
```

{{% caption %}}For more information, see [Function type signatures](/flux/v0.x/function-type-signatures/).{{% /caption %}}


## Examples

- [Return a timestamp representing today](#return-a-timestamp-representing-today)
- [Query data from today](#query-data-from-today)

### Return a timestamp representing today

```js
option now = () => 2022-01-01T13:45:28Z

today()// Returns 2022-01-01T00:00:00.000000000Z


```


### Query data from today

```js
from(bucket: "example-bucket")
    |> range(start: today())

```

