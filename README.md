# usashiki.github.io

Forked from [barryclark/jekyll-now](https://github.com/barryclark/jekyll-now).

## Posts

To create a post, create a new file in `_posts/` titled `yyyy-mm-dd-post-title.md`.
This will create a post at `https://usashiki.github.io/post-title/`.

## Images

To keep things organized, when adding an image to a post, create a new folder `_images/post-title` and put any images in there.
To attach an image with a caption like on Medium, use [`_includes/image.html`](/_includes/image.html) ([source](https://stackoverflow.com/a/19360305)) like so:

```
{% include image.html url="/images/post-title/image.png" description="caption text" %}
```

### TODOs

- [ ] favicon?
- [ ] site description?
- [ ] customize css more?
- [ ] rss feed?
