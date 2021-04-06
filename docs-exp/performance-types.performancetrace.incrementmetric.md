<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/performance-types](./performance-types.md) &gt; [PerformanceTrace](./performance-types.performancetrace.md) &gt; [incrementMetric](./performance-types.performancetrace.incrementmetric.md)

## PerformanceTrace.incrementMetric() method

Adds to the value of a custom metric. If a custom metric with the provided name does not exist, it creates one with that name and the value equal to the given number. The value will be floored down to an integer.

<b>Signature:</b>

```typescript
incrementMetric(metricName: string, num?: number): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  metricName | string | The name of the custom metric. |
|  num | number | The number to be added to the value of the custom metric. If not provided, it uses a default value of one. |

<b>Returns:</b>

void
