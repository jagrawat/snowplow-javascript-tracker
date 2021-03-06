<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@snowplow/browser-tracker](./browser-tracker.md) &gt; [setBufferSize](./browser-tracker.setbuffersize.md)

## setBufferSize() function

Set the buffer size Can be useful if you want to stop batching requests to ensure events start sending closer to event creation

<b>Signature:</b>

```typescript
declare function setBufferSize(newBufferSize: number, trackers?: Array<string>): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  newBufferSize | number | The value with which to update the bufferSize to |
|  trackers | Array&lt;string&gt; | The tracker identifiers which will be flushed |

<b>Returns:</b>

void

