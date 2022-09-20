---
title: iox.from() function
description: >
  `iox.from()` reads from the selected bucket and measurement in an IOx storage node.
menu:
  flux_0_x_ref:
    name: iox.from
    parent: experimental/iox
    identifier: experimental/iox/from
weight: 201
flux/v0.x/tags: [inputs]
---

<!------------------------------------------------------------------------------

IMPORTANT: This page was generated from comments in the Flux source code. Any
edits made directly to this page will be overwritten the next time the
documentation is generated. 

To make updates to this documentation, update the function comments above the
function definition in the Flux source code:

https://github.com/influxdata/flux/blob/master/stdlib/experimental/iox/iox.flux#L20-L20

Contributing to Flux: https://github.com/influxdata/flux#contributing
Fluxdoc syntax: https://github.com/influxdata/flux/blob/master/docs/fluxdoc.md

------------------------------------------------------------------------------->

`iox.from()` reads from the selected bucket and measurement in an IOx storage node.

This function creates a source that reads data from IOx. Output data is
"pivoted" on the time column and includes columns for each returned
tag and field per time value.

##### Function type signature

```js
(bucket: string, measurement: string) => stream[{A with _time: time}] where A: Record
```

{{% caption %}}For more information, see [Function type signatures](/flux/v0.x/function-type-signatures/).{{% /caption %}}

## Parameters

### bucket
({{< req >}})
IOx bucket to read data from.



### measurement
({{< req >}})
Measurement to read data from.


