---
fragment: content
sidebar:
  sticky: true
title: Documentation
weight: 300
---

This fragment needs a fragment controller file and subitems. You need to create a directory for this fragment and put `index.md` with `fragment = "member"` and subitems next to that file.

### Variables

`index.md` doesn't use any variables. Following variables are for subitems.

#### position
*type: string*

#### company
*type: string*

#### reports_to
*type: string*

#### lives_in
*type: string*  
*Markdown enabled*

#### scope
*type: array of strings*  
*Markdown enabled*

#### icons
*type: array of [asset object]({{< ref "global-variables" >}}#asset)s*

Social media and other icons.

#### asset
*type: [asset object]({{< ref "global-variables" >}}#asset)*  
*size: 250x250*

Member avatar.

[Global variables]({{< ref "global-variables" >}}) are documented as well and have been omitted from this page.
