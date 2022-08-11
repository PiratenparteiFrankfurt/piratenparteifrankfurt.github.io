source 'https://rubygems.org'

## If you update the version here, also update it in .travis.yml and
## docs/setting-up-your-environment.md. Then push your branch and
## make sure Travis supports that version. Then remind one of the
## site maintainers that they need to run `rvm install <VERSION>` on
## the build server(s) before they commit to master
ruby '3.1.2'
gem 'github-pages'

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "~> 4.2.2"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!
# group :jekyll_plugins do
#   gem "jekyll-feed", "~> 0.12"
# end


gem "webrick", "~> 1.7"

## Used on the build server. If you add a package here (like nokogiri)
## that has non-Gem dependencies (like zlib), please remind the site
## maintainers that they need to manually update the build server(s)
## before they commit to master. If `bundle install` can satisfy all
## your dependencies, then nothing extra needs to be done
group :development do
  gem 'ffi-icu'
  gem 'json', '2.6.2'
  gem 'less', '2.6.0'
  gem 'kramdown', '2.4.0'
  gem 'RedCloth', "4.3.2"
  gem 'mini_racer'
  # gem 'therubyracer', "0.12.3" # required by less
  gem 'jshintrb', '0.3.0'
  gem 'safe_yaml', '1.0.5'
  gem 'json-schema', '3.0.0'
end