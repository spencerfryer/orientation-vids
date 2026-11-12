# Orientation Videos

A simple GitHub Pages site that lists links to the orientation videos.

## Adding or changing videos

All the content lives in [`index.md`](index.md). Open it on GitHub, click the pencil icon, and add a line like this:

```markdown
- [Video title](https://link-to-the-video) (optional short note)
```

Start a new section with a line beginning `## `. Commit the change and the site rebuilds automatically within a minute or two (see the **Actions** tab for progress).

## One-time setup

In **Settings → Pages**, set **Source** to **GitHub Actions** so the included workflow can publish the site.
