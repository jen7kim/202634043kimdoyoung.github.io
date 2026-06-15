source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins

gem "tzinfo-data"
gem "wdm", "~> 0.1.0" if Gem.win_platform?

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-feed"
  gem "jemoji"
  gem "jekyll-include-cache"
  gem "jekyll-algolia"
end

gem "racc", "= 1.8.1"
# 윈도우 컴파일러 에러를 우회하기 위한 강제 바이너리 선언
gem "racc", "1.8.1", platforms: [:mingw, :mswin, :x64_mingw]
gem "nokogiri", "1.19.3", platforms: [:mingw, :mswin, :x64_mingw]
gem "json", "2.19.9", platforms: [:mingw, :mswin, :x64_mingw]