source "https://rubygems.org"

# GitHub Pages
gem "github-pages", group: :jekyll_plugins

# Jekyll plugins (included in github-pages but specified for clarity)
gem "jekyll-feed", "~> 0.12"
gem "jekyll-sitemap"
gem "jekyll-seo-tag"

# Required for Jekyll 4.x
gem "webrick", "~> 1.7"

# Development dependencies
group :development do
  gem "listen", "~> 3.0"
end

# Windows and JRuby does not include zoneinfo files
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
