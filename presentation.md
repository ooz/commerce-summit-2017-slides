---
title: "ePages REST API - Live-coding"
theme: league
revealOptions:
    transition: 'slide'
    slideNumber: 'c/t'
---

<!-- .slide: data-background="./33.jpg" -->

<div style="background-color:rgba(0, 0, 0, 0.8);">
<h1>Live-coding</h1>

<b>
Oliver Zscheyge<br/>
Software Engineer<br/>
[@oozgo](https://twitter.com/oozgo)<br/>
[github.com/ooz](https://github.com/ooz)<br/>
[o.zscheyge@epages.com](mailto:o.zscheyge@epages.com)<br/>
<br/>
Commerce Summit<br/>
Hamburg, 2017-09-21
</b>
</div>

---

## Getting an ePages dev shop

[![ePages Developer Website](epages_dev.png)](https://developer.epages.com/)

---

## ePages REST API differences

||Base/Now|Now&Beyond|
|---|---|---|---|
|**Auth**|perm. access token|expiring JWT + refresh|
|**Compatibility**|Now ~ Base|new API|
|**Features**|private apps, installation test, app store, webhooks|private apps, rest planned|

---

## Order Document App

[![Order Documents App](screenshot.png)](https://github.com/ooz/epages-rest-python-examples/tree/master/beautiful_order_documents)

---

## OAuth 2.0 flow for app installation

[![OAuth flow for app installation](oauth2-flow.png)](https://developer.epages.com/apps/install-app#docs)

---

## Webhooks

[![Webhooks API doc](webhooks.png)](https://developer.epages.com/apps/api-reference/resource-webhooks#docs)

---

## ♥ Thank You! ♥

* [https://github.com/ooz/epages-rest-python](https://github.com/ooz/epages-rest-python)
* [https://github.com/ooz/epages-rest-python-examples](https://github.com/ooz/epages-rest-python-examples/tree/master/beautiful_order_documents)
