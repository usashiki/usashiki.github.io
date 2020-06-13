# [usashiki.github.io](https://usashiki.github.io/)

Forked from [barryclark/jekyll-now](https://github.com/barryclark/jekyll-now). 

## Posts

To create a post, create a new file in `_posts/` titled `yyyy-mm-dd-post-title.md`.
This will create a post at `https://usashiki.github.io/post-title/`.

## Images

To keep things organized, when adding an image to a post, create a new folder `_images/post-title` and put any images in there.
To attach an image with a caption like on Medium, use the custom Liquid tag [`_includes/image.html`](/_includes/image.html) ([source](https://stackoverflow.com/a/19360305)) like so:

```
{% include image.html url="/images/post-title/image.png" description="caption text" %}
```

## TODOs

- [ ] make it easier to embed tweets: there's [this](https://github.com/rob-murray/jekyll-twitter-plugin) but [github doesn't support custom plugins](https://help.github.com/en/github/working-with-github-pages/about-github-pages-and-jekyll#plugins) ([workaround](https://github.com/rob-murray/jekyll-twitter-plugin/issues/15#issuecomment-122787785))
- [ ] make it easier to embed igs: [here's](http://khoparzi.com/2019-02-06-embedding-instagram-on-jekyll/) a hacky way
- [ ] inconsistent centering of images/embeds
- [ ] favicon?
- [ ] name/description?
- [ ] customize css?
