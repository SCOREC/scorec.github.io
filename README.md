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


