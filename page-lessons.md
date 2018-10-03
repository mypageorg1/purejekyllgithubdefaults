---
title: Lessons Learned
layout: page
---

# minima

jekyll/minima: Minima is a one-size-fits-all Jekyll theme for writers.
https://github.com/jekyll/minima

Layouts

Refers to files within the _layouts directory, that define the markup for your theme.

    default.html — The base layout that lays the foundation for subsequent layouts. The derived layouts inject their contents into this file at the line that says {{ content }} and are linked to this file via FrontMatter declaration layout: default.
    home.html — The layout for your landing-page / home-page / index-page. [More Info.]
    page.html — The layout for your documents that contain FrontMatter, but are not posts.
    post.html — The layout for your posts.

# jekyll config.yml

## github inferences
title: Your awesome title
author: GitHub User
email: your-email@domain.com

were infered in github without need to specify them in git hub
# netlify

## nothing in _site ?

## no admin folder ? no identity enabled ?
