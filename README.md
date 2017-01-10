# kurator
A Jekyll theme for curation websites.

## What is Kurator?

Kurator is an open-source Jekyll theme for curation websites. Just fork the theme, add some content, commit the theme to Github, and activate Github pages to run your own curation website.

![Recherchequellen is a sample project for the Kurator theme](https://raw.githubusercontent.com/nihilor/recherchequellen/master/169screenshot.png "Recherchequellen is a sample project for the Kurator theme")


## How does it work?

Kurator makes use of the collection feature of Jekyll. Every file in the `_curation` directory creates a new entry in the collection. Just copy the sample file and fill in the websites details.

In addition, Kurator uses the sources of [Bootstrap 4 Alpha](https://v4-alpha.getbootstrap.com/). That means: You can use any of the Bootstrap components in the theme and you can easily change the look and feel of the theme just by editing the SASS files. Github pages automaticallly render the Jekyll theme and all the SASS files.

## How to start?

Kurator is easy to use. Follow these instructions to set up and run your own curation website within minutes.

1. Fork this repository.
2. Edit `_config.sample.yml` and fill it with your specific website information.
3. Rename `_config.sample.yml` to `_config.yml`.
4. Add some content by creating new files in the subdirectory `_curation`. There you can find a sample file.
5. If necessary, commit your site to Github.
6. Activate Github pages. On the Github website, click on *Settings*, scroll down to *Github Pages* and select from *None* the Option *master branch*.
7. Done.

## Sample curation file

You can use the following sample for new curation entries. Important: The files must end with `.md`. Otherweise Github pages won't render these files to HTML. And don't change the `layout` setting.

```yaml
---
# Don't change this value.
layout: page
# The title of the curated site.
title: Kurator
# The category of curated site. Type any category you want.
category: Theme
# An image used as a thumbnail on the index page. Must be placed in "assets".
thumbnail: kurator.jpg
# A list of images used for a gallery shown on the details page. Images must be placed in "assets".
gallery:
    - kurator.jpg
    - kurator-2.jpg
# The links to the curated website and their social media profiles.
social:
    website: http://kurator.mlu.io
    github: https://github.com/nihilor/kurator
    twitter: http://twitter.com/kuratortheme
    facebook: http://facebook.com/kuratortheme
    reddit: 
    youtube: 
    twitch: 
---
# A brief description of the curated website.
Kurator is an open-source Jekyll theme for curation websites. Just fork the theme, add some content, commit the theme to Github, and activate Github pages to run your own curation website.
```

