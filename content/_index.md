---
title: "PUMI Components"
linkTitle: "Documentation"
type: "docs"
tags: []
weight: 20

cascade:
- _target:
    path: "/blog/**"
  type: "blog"
  # set to false to include a blog section in the section nav along with docs
  toc_root: true
- _target:
    path: "/about/**"
  type: "about"
- _target:
    path: "/community/**"
  type: "community"
  # set to false to include a blog section in the section nav along with docs
- _target:
    path: "/**"
    kind: "page"
  type: "docs"
- _target:
    path: "/**"
    kind: "section"
  type: "docs"
- _target:
    path: "/**"
    kind: "section"
  type: "home"
---


The PUMI Components provide support for a range of unstructured mesh workflows, such as mesh adaption, particle-in-cell 
calculations, and developing support for field-transfer and parallel control of coupled applications. The PUMI components 
are an integrated set of codes that make up each of these pieces as follows:

{{< components >}}
