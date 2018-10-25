# nycitymarathon
This repository is the source for https://nycitymarathon.us (A web portal for the New York City Marathon. This portal is all about the information of New York City Marathon. Help extend and fix any typo by submitting and contributing on this repo.

Please don't send pull request unless you found an major typo or mistakes in the articles.

## The sources, Software, Tools and credits

package.json

    "autoprefixer": "^9.1.5",
    "browser-sync": "^2.26.3",
    "critical": "^1.3.4",
    "css-mqpacker": "^7.0.0",
    "del": "^3.0.0",
    "fontawesome": "^4.7.2",
    "foundation-sites": "^6.5.0-rc.4",
    "gulp": "^4.0.0",
    "gulp-autoprefixer": "^6.0.0",
    "gulp-cache": "^1.0.2",
    "gulp-changed": "^3.2.0",
    "gulp-concat": "^2.6.1",
    "gulp-cssnano": "^2.1.3",
    "gulp-imagemin": "^4.1.0",
    "gulp-modernizr": "^3.0.0",
    "gulp-purifycss": "^0.2.0",
    "gulp-rename": "^1.4.0",
    "gulp-rsync": "0.0.8",
    "gulp-sass": "^4.0.1",
    "gulp-shell": "^0.6.5",
    "gulp-sourcemaps": "^2.6.4",
    "gulp-uglify": "^3.0.1",
    "gulp-useref": "^3.1.5",
    "jquery": "^3.3.1",
    "node-sass": "^4.9.3",
    "run-sequence": "^2.2.1",
    "what-input": "^5.1.2"

 Gemfile
 
    source "https://rubygems.org"
    gem "jekyll", "~> 3.8.4"
    gem "minima", "~> 2.0"
    group :jekyll_plugins do
      gem "jekyll-feed", "~> 0.6"
    end
    gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
    gem "wdm", "~> 0.1.0" if Gem.win_platform?

    gem 'jekyll-mentions'
    gem 'jekyll-toc'
    gem 'jekyll-sitemap'
    gem 'jekyll-last-modified-at'
    gem 'jekyll-compose', group: [:jekyll_plugins]
    gem "jekyll-assets", group: :jekyll_plugins
    gem 'jekyll-archives'
    gem 'jekyll-redirect-from'
    gem 'amp-jekyll'
    gem 'jekyll-twitter-plugin'
