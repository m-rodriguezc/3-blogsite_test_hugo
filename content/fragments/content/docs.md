---
fragment: content
sidebar:
  sticky: true
title: Documentation
weight: 300
---

### Slots

- `sidebar`: Only active if `sidebar` is set.
- `before-content`
- `after-content`

### Variables

#### summary
*type: string*

Ability to override the generated default summary by Hugo to be displayed in fragments such as List.

#### asset
*type: [asset object]({{< ref "global-variables" >}}#asset)*

This value will render an image on top of the content.

#### display_date
*type: boolean*  
*default: false*

#### sidebar
*type: object*

If this object is present in fragment configuration a sidebar would appear next to the fragment.

**NOTE:** If sidebar is active the `sidebar` slot would also be active.

##### sidebar.title
*type: string*

##### sidebar.sticky
*type: boolean*

Makes the sidebar stick to top of the page when user scrolls past it.

**NOTE:** Sticky sidebars will not be merged into one, when there are multiple content fragment in a page.

##### sidebar.align
*type: string*  
*accepted values: right, left*  
*default: left*

Sets the alignment on the page.

##### sidebar.content
*type: string*

Markdown enabled content that would be rendered in the sidebar.

[Global variables]({{< ref "global-variables" >}}) are documented as well and have been omitted from this page.
