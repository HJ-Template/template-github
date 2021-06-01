# Settings

## Run

```
$ gem install bundler
$ bundle
$ jekyll serve –port 4000
```

## Site Settings

```yml
# Site Settings
locale: "ko-KR"
title: "Blog"
title_separator: "&#124;"
subtitle: "This is my Blog"
name: "Jiseong"
description: "Jiseong's blog"
url: "https://hj-template.github.io/template-github"
baseurl: # the subpath of your site, e.g. "/blog"
repository: "hj-template/template-github" # GitHub username/repo-name e.g. "mmistakes/minimal-mistakes"
```

## Site Author

```yml
# Site Author
author:
  name: "Jiseong"
  avatar: "/assets/images/profile.jpg" # path of avatar image, e.g. "/assets/images/bio-photo.jpg"
  bio: "I am an **amazing** person."
  location: "Republic of Korea"
  # email: "dgf5820@gmail.com"
  links:
    - label: "Email"
      icon: "fas fa-fw fa-envelope-square"
      url: "mailto:dgf5820@email.com"
    - label: "Website"
      icon: "fas fa-fw fa-link"
      # url: "https://your-website.com"
    - label: "Twitter"
      icon: "fab fa-fw fa-twitter-square"
      # url: "https://twitter.com/"
    - label: "Facebook"
      icon: "fab fa-fw fa-facebook-square"
      # url: "https://facebook.com/"
    - label: "GitHub"
      icon: "fab fa-fw fa-github"
      url: "https://github.com/"
    - label: "Instagram"
      icon: "fab fa-fw fa-instagram"
      # url: "https://instagram.com/"
```

## Defaults

```yml
# Defaults
defaults:
  # _posts
  - scope:
      path: ""
      type: posts
    values:
      layout: single
      author_profile: true
      read_time: true
      comments: true
      share: true
      related: true

  # _pages
  - scope:
      path: "_pages"
      type: pages
    values:
      layout: single
      author_profile: true
```
