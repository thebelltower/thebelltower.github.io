source "https://rubygems.org"
ruby File.read('.ruby-version').chomp if File.exist?('.ruby-version')

gem "jekyll", "3.3.0"
gem "html-proofer"

# Theme. Must be listed on https://pages.github.com/themes/
gem "minima", "~> 2.0"

# Helps maintain a local Jekyll environment in sync with GitHub Pages
gem "github-pages", group: :jekyll_plugins

# Jekyll plugins https://jekyllrb.com/docs/plugins/
group :jekyll_plugins do
   gem "jekyll-feed", "~> 0.6"
   gem "jekyll-compose"
end
