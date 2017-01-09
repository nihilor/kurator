# kurator
A Jekyll theme for curation websites.

## What is Kurator?

Kurator is an open-source Jekyll theme for curation websites. Just fork the theme, add some content, commit the theme to Github, and activate Github pages to run your own curation website.

## How to start?

Kurator is easy to use. Follow these instructions to set up and run your own curation website within minutes.

1. Fork this repository.
2. Edit `_config.sample.yml` and fill it with your specific website information.
3. Rename `_config.sample.yml` to `_config.yml`.
4. Add some content by creating new files in the subdirectory `_curation`. There you can find a sample file.
5. If necessary, commit your site to Github.
6. Activate Github pages. On the Github website, click on *Settings*, scroll down to *Github Pages* and select from *None* the Option *master branch*.
7. Done.

## Do you have a sample file for new curation entries?

You can use the following sample for new curation entries. Important: The files must end with `.md`. Otherweise Github pages won't render these files to HTML. And don't change the `layout` setting.

```yaml
---
layout: page
title: Kurator
category: Theme
tags: 
thumbnail: kurator.jpg
gallery:
    - kurator.jpg
    - kurator-2.jpg
social:
    website: http://kurator.mlu.io
    steam: https://steamcommunity.com/groups/steamdb
    github: https://github.com/nihilor/kurator
    twitter: http://twitter.com/kuratortheme
    facebook: http://facebook.com/kuratortheme
    reddit: 
    youtube: 
    twitch: 
---
Kurator is an open-source Jekyll theme for curation websites. Just fork the theme, add some content, commit the theme to Github, and activate Github pages to run your own curation website.
```

