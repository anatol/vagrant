bundle install --path vendor/bundle
bundle exec rake install


gem push pkg/vagrant-unbundled-$VERSION.gem
