---
fragment: content
sidebar:
  sticky: true
title: Deployment
weight: 100
---

In order to deploy your website using Syna follow the [Hugo documentation](https://gohugo.io/hosting-and-deployment/) which describes the process of deploying on various hosts or host agnostic approaches.

### Environment Variables

#### DEMO_MODE
*type: boolean*  
*default: false*

If set to true, all Syna related build time error messages will be muted.

### Configurations

#### .Site.Params.debug
*type: boolean*  
*default: false*

If set to true, Syna related error messages will appear on the page.
