source "https://rubygems.org"

# Mirrors the exact gem versions GitHub Pages builds with. The version is
# pinned deliberately: unpinned, bundler will silently fall back to a very old
# release (223 / Jekyll 3.9) on a Ruby it does not support, instead of failing.
gem "github-pages", "~> 232", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-sitemap"
end

# Ruby 3.4+ dropped these from the default gems while the pinned Jekyll still
# requires them. Harmless on 3.3; needed if you move to a newer 3.x.
gem "csv"
gem "base64"
gem "bigdecimal"
gem "logger"
gem "ostruct"

# Windows / JRuby timezone support
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
