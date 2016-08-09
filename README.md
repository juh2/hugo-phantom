# Hugo Phantom Themes

This is a Hugo theme based on the [Phantom Theme by HTML5 UP](https://html5up.net/phantom).

I created this theme for my [blog](http://www.hasecke.eu). Actually it's my first Hugo theme.

I provided an example site to show how to use the theme.

To make use of the tiles on the start page you have to provide a link to an image in the metadata section.
You can use the built-in dictionary 'images' for this.

In YAML:

````
---
title: foo bar
images:
- /images/pic01.jpg
- /images/pic13.jpg
---
````

In TOML:

````
---
title = "foo bar"
images = ["/images/pic06.jpg", "/images/pic13.jpg"]
---
````

The first image is used for the tile on the front page. The second as a title picture in the post.

There is basic i18n support with a YAML-file in the data folder, so that you can easily customize the theme to your language.

Look at `exampleSite/data/i18n.yaml`

````
morelink: "More…"
sectionshare: "Share"
sectionfollow: "Follow"
````

Please report bugs [here](https://github.com/juh2/hugo-phantom/issues)

Enjoy!
