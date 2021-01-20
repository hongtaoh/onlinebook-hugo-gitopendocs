---
title: "Configure Hugo"
draft: false
weight: 2
---

Hugo expects a configuration file to build your site. OpenGitDocs includes one already set up; simply move it from the theme repository into your site root:

```sh
mv themes/opengitdocs/exampleSite/config.yaml .
```

Be careful not to overwrite an existing file named `config.yaml`, if that is not your intention.

Here's the full `config.yaml` used to build this site (yes, the one you're reading right now!):

```sh
{{< readfile file="config.yaml" >}}
```

OpenGitDocs uses reasonable defaults for unset parameters where possible.

Hugo makes no assumptions, so if a necessary parameter is missing, you'll see a warning when building or serving your site. Here are [all configuration settings for Hugo configuration files](https://gohugo.io/getting-started/configuration/#all-configuration-settings).

Congratulations, you're ready to preview and build your site!
