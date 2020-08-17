<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Page](./puppeteer.protocol.page.md) &gt; [DownloadProgressEvent](./puppeteer.protocol.page.downloadprogressevent.md)

## Protocol.Page.DownloadProgressEvent interface

Fired when download makes progress. Last call has \|done\| == true.

<b>Signature:</b>

```typescript
export interface DownloadProgressEvent 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [guid](./puppeteer.protocol.page.downloadprogressevent.guid.md) | string | Global unique identifier of the download. |
|  [receivedBytes](./puppeteer.protocol.page.downloadprogressevent.receivedbytes.md) | number | Total bytes received. |
|  [state](./puppeteer.protocol.page.downloadprogressevent.state.md) | ('inProgress' \| 'completed' \| 'canceled') | Download status. (DownloadProgressEventState enum) |
|  [totalBytes](./puppeteer.protocol.page.downloadprogressevent.totalbytes.md) | number | Total expected bytes to download. |
