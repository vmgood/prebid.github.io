---
layout: bidder
title: RhythmOne
description: Prebid RhythmOne Bidder Adaptor
top_nav_section: dev_docs
nav_section: reference
hide: true
biddercode: rhythmone
biddercode_longer_than_12: false
prebid_1_0_supported : true
media_types: video
gdpr_supported: true
---



### bid params

{: .table .table-bordered .table-striped }
| Name          | Scope    | Description                                 | Example | Type      |
|---------------|----------|---------------------------------------------|---------|-----------|
| `placementId` | required | The ID issued by RhythmOne to the publisher | `'34887'` | `string`  |
| `zone` | optional | Optional string issued by RhythmOne to the publisher | `'1r'` | `string` |
| `path` | optional | Optional string issued by RhythmOne to the publisher | `'mvo'` | `string` |
