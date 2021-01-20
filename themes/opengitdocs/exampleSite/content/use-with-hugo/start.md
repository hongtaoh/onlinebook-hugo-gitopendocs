---
title: "Get Started with Hugo"
draft: false
weight: 1
---

Build your OpenGitDocs site with Hugo static site generator.

## 1. Prepare Your Documentation

Ensure your documentation is in the right format for use with [Hugo static site generator](https://gohugo.io/). See [Getting Started](https://gohugo.io/getting-started/) if you're new to Hugo.

Here's an example of what your [content directory organization](https://gohugo.io/content-management/organization/) might look like:

```sh
content/
├── _index.md
├── intro/
│   ├── config.md
│   ├── deploy.md
│   ├── _index.md
│   ├── quickstart.md
│   └── screenshot.png
├── support.md
└── usage/
    ├── customizing.md
    ├── _index.md
    └── settings.md
```

Here's an example of what one page's [front matter](https://gohugo.io/content-management/front-matter/) might look like:

```yml
---
title: "Getting Started"
draft: false
weight: 1
---
```

OpenGitDocs doesn't need any special front matter parameters other than those Hugo expects. The `weight` parameter is optional.

## 2. Install OpenGitDocs

Clone the OpenGitDocs repository for Hugo into your Hugo themes directory. From your site root:

```sh
git clone \
https://github.com/opengitdocs/hugo.git themes/opengitdocs
```

Alternatively, you can include this repository as a [git submodule](https://git-scm.com/docs/gitsubmodules):

```sh
git submodule add \
https://github.com/opengitdocs/hugo.git themes/opengitdocs
```

You're almost ready to build; you'll just need to add a configuration file.
