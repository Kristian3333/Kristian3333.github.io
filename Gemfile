source 'https://rubygems.org'
ruby '3.0.2'  # Use an older, more stable Ruby version

# Fix for URI gem conflict
gem 'uri', '0.10.1', require: false

# Add webrick as a dependency (needed for Ruby 3.0+)
gem 'webrick', '~> 1.7'

group :jekyll_plugins do
    gem 'jekyll', '~> 4.2.2'
    gem 'jekyll-archives'
    gem 'jekyll-diagrams'
    gem 'jekyll-email-protect'
    gem 'jekyll-feed'
    gem 'jekyll-imagemagick'
    gem 'jekyll-minifier'
    gem 'jekyll-paginate-v2'
    gem 'jekyll-scholar'
    gem 'jekyll-sitemap'
    gem 'jekyll-link-attributes'
    gem 'jekyll-twitter-plugin'
    gem 'jemoji'
    gem 'mini_racer'
    gem 'unicode_utils'
    # Removed duplicate webrick from here
end

group :other_plugins do
    gem 'httparty'
    gem 'feedjira'
end