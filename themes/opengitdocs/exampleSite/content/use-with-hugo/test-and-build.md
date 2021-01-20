---
title: "Test and Build"
draft: false
weight: 3
---

Serve your new documentation site locally to see how it looks. Run:

```sh
hugo serve
```

And visit `http://localhost:1313/` in your browser to preview the site.

If everything seems lovely, you can build your site. Hugo will build to the `public/` directory by default. To customize this, pass the `-d` flag and specify the destination directory.

For example, to build your site into your `docs/` directory:

```sh
hugo -d docs/
```

Commit and push the changes back to your site repository.

Congratulations, you're ready to host your documentation site! 🎉 See [Host in Your Repository](https://opengitdocs.com/host) on the main OpenGitDocs site for your next steps towards fame and fortune.
