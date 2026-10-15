source "https://rubygems.org"

# Match the versions GitHub Pages runs (232 = Jekyll 3.10, Liquid 4.0.4).
# Liquid 4.0.3 (github-pages <= 227) crashes on Ruby 3.2+ with `tainted?`.
gem "github-pages", "~> 232", group: :jekyll_plugins

# Stdlib gems removed from Ruby's default gems in 3.4+ / 4.0, required by Jekyll 3.9
gem "csv"
gem "base64"
gem "bigdecimal"
gem "logger"
gem "webrick"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:windows, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?
