# jekyll-plyr
Embed YouTube, Vimeo, and HTML5 video using [Plyr](https://github.com/sampotts/plyr).

## Table of Contents

* [Embed HTML5](#embed-html5)
* [Embed YouTube](#embed-youtube)
* [Embed Vimeo](#embed-vimeo)

## HTML5
1. Drop [plyr.html](https://github.com/joeljayakaran/jekyll-plyr/blob/main/_includes/plyr.html) in your `_includes` folder
2. Put the link to your video at the top of your .md file

```html
---
html: https://example.com/example.mp4
---
```

3. Place this code in your .md file where you want to embed your video

```html
{% include plyr.html video=page.html %}
```
## YouTube
1. Drop [plyrYoutube.html](https://github.com/joeljayakaran/jekyll-plyr/blob/main/_includes/plyrYoutube.html) in your `_includes` folder
2. Put the YouTube video ID  at the top of your .md file

```html
---
YouTubeID: bTqVqk7FSmY
---
```

3. Place this code in your .md file where you want to embed your video

```html
{% include plyrYoutube.html youtube=page.YouTubeID %}
```

## Vimeo
1. Drop [plyrVimeo.html](https://github.com/joeljayakaran/jekyll-plyr/blob/main/_includes/plyrVimeo.html) in your `_includes` folder
2. Put the Vimeo video ID  at the top of your .md file

```html
---
VimeoID: 76979871
---
```

3. Place this code in your .md file where you want to embed your video

```html
{% include plyrVimeo.html vime=page.VimeoID %}
```
