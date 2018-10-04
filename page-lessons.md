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


## on netlify

no title yeslayout -> doesnst appear on the menu
no layout yes title -> gets published but not formated

# jekyll config.yml

## github inferences
title: Your awesome title
author: GitHub User
email: your-email@domain.com

were infered in github without need to specify them in git hub
# netlify

## nothing in _site ?

## no admin folder ? no identity enabled ? no git-gateway enabled ? no netlify.toml ?


# migrations of jekyll from ghub to glab

Moving your Jekyll site from GitHub Pages to GitLab - BFTSYSTEMS | LTD
Once your repository has been moved to GitLab, nothing will work immediately and no pages will be built. Unlike GitHub, GitLab uses a CI (continuous integration) configuration file to instruct the GitLab site Runners how to build your site. This process is a little more complex than GitHub, but also more flexible. Primarily, this flexibility is what brought me to GitLab for hosting.

To setup the build process, you must create a file named .gitlab-ci.yml in your repository. The contents of this file will direct GitLab how to build your site. The full documentation on this process can be found in the document Hosting on GitLab.com with GitHub Pages. As this site is built using Jekyll, I followed the steps in the document outlining the configuration process specifically for Jekyll.

This is where things get a little interesting. When it comes to building the CI file for Jekyll, the GitLab documentation is somewhat vague, and misses several edge cases


https://bftsystems.ca/moving-from-github-to-gitlab-pages/


Hosting on GitLab.com with GitLab Pages | GitLab
https://about.gitlab.com/2016/04/07/gitlab-pages-setup/



