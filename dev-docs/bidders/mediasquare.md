---
layout: bidder
title: MediaSquare
description: Prebid MediaSquare Bidder Adapter

biddercode: mediasquare
gdpr_supported: true
tcf2_supported: true
usp_supported: true
schain_supported: true
userIds: id5Id
media_types: banner
---


### Bid Params

{: .table .table-bordered .table-striped }
| Name          | Scope    | Description           | Example                              | Type      |
|---------------|----------|-----------------------|--------------------------------------|-----------|
| `owner `      | required | Mediasquare owner ID  | `'test'`                               | `string`  |
| `code`        | required | Mediasquare code ID   | `'publishername_atf_desktop_rg_pave'`  | `string`  |
