---
title: date.monthDay() function
description: >
  The `date.monthDay()` function returns the day of the month for a specified time.
  Results range from `[1-31]`.
aliases:
  - /v2.0/reference/flux/functions/date/monthday/
menu:
  v2_0_ref:
    name: date.monthDay
    parent: Date
weight: 301
---

The `date.monthDay()` function returns the day of the month for a specified time.
Results range from `[1-31]`.

_**Function type:** Transformation_  

```js
import "date"

date.monthDay(t: 2019-07-17T12:05:21.012Z)

// Returns 17
```

## Parameters

### t
The time to operate on.

_**Data type:** Time_
