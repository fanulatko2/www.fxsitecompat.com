---
title: "`ArrayBuffer.slice` will be removed"
date: "2016-12-04T19:50:00-05:00"
categories: ["javascript"]
tags: []
versions: ["53"]
references:
    - url: "https://bugzilla.mozilla.org/show_bug.cgi?id=1313112"
      title: "Bug 1313112 - Deprecate and remove ArrayBuffer.slice"
---
The non-standard `ArrayBuffer.slice` static method, [deprecated since Firefox 52](https://www.fxsitecompat.com/en-CA/docs/2016/arraybuffer-slice-has-been-deprecated/), is planned to be removed soon from Firefox 53. Use the standard [`ArrayBuffer.prototype.slice`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/ArrayBuffer/slice) method instead.