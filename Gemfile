source "https://rubygems.org"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
# gem "minima", "~> 2.0"

# gem "jekyll", "3.9.0"
# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
gem "github-pages", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
  # Pin activesupport manually - otherwise it was sticking to version 3.2.22.5
  gem "activesupport", "~> 5"
  # No other plugins that are not already included in github-pages
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1" if Gem.win_platform?

