# scorec.github.io


The current version of this site is built using the [hugo](https://gohugo.io/) website generator with the ["docsy" theme](https://github.com/google/docsy).

This documentation is set up as a very bare-bones documentation only page. For examples on how to add blog content, community page, about page, etc. check out the docsy-example: https://github.com/google/docsy-example


To build the site and develop content locally use:
```
hugo serve
```

Note: The following steps may not be needed. Haven't tested on a clean machine yet.

To meet the requirements of the docsy theme you must:
1. Install a recent release of the Hugo "extended" version. If you install from the Hugo release page, make sure you download the extended version, which supports SCSS.
2. Install PostCSS so that the site build can create the final CSS assets. You can install it locally by running the following commands from the root directory of your project:

```
npm install --save-dev autoprefixer
npm install --save-dev postcss-cli
npm install -D postcss
```


# PUMI Components
The PUMI components make up a set of interconnected software based on unstructured meshing technologies to support various aspects of the engineering analysis workflow.

| Component     | Description                                 | github           |
| ------------- | ------------------------------------------- | ---------------- |
| PUMI          | The Parallel Unstructured Mesh Infrastructure provides a mesh database with O(1) adjaceny information and mesh adaption on CPUs. | https://github.com/SCOREC/core |
| PUMI-PIC      |  PUMI-PIC provides efficient datastructures and algorithms for particle-in-cell computations. | https://github.com/SCOREC/pumi-pic |
| Omega_h       | Omega_h provides a mesh database with O(1) adjacency information and mesh adaptation on GPUs | https://github.com/SCOREC/omega_h |
| PCMS          | PCMS provides parallel control and field transfer operations for tightly coupled simulations | https://github.com/SCOREC/PCMS |
