Skip to content
This repository
Search
Pull requests
Issues
Marketplace
Explore
 @derekponce
Sign out
35
643 741 mmistakes/skinny-bones-jekyll
 Code  Issues 11  Pull requests 5  Projects 0  Insights
skinny-bones-jekyll/_config.yml
07f637c  on Jun 1, 2016
@mmistakes mmistakes Update gems and remove dependencies
     
65 lines (57 sloc)  1006 Bytes
# Site wide configuration

title: "My Site"
description: "This is a description of my awesome site."
logo: # 120x120 px default image used for Twitter summary card
teaser: # 400x250 px default teaser image used in image archive grid
locale: en
url:
feed:
  path: atom.xml

# Jekyll configuration

sass:
  sass_dir: _sass
  style: compressed
permalink: /:categories/:title/
kramdown:
  toc_levels: 1..2
highlighter: rouge
gems:
  - jekyll-sitemap
  - jekyll-gist
  - jekyll-feed


# Site owner
owner:
  name:
  email:
  twitter:
  google:
    ad-client:
    ad-slot:
  bio:
  avatar: bio-photo.jpg # 160x160 px image for author byline
  disqus-shortname:


include:
  - .htaccess
exclude:
  - "*.less"
  - "*.sublime-project"
  - "*.sublime-workspace"
  - .asset-cache
  - .bundle
  - .jekyll-assets-cache
  - .sass-cache
  - CHANGELOG
  - Capfile
  - Gemfile
  - Gruntfile.js
  - LICENSE
  - README
  - Rakefile
  - config
  - gulpfile.js
  - lib
  - log
  - node_modules
  - package.json
  - spec
  - tmp
© 2018 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
API
Training
Shop
Blog
About
