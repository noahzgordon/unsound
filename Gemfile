source 'https://rubygems.org'

# Specify your gem's dependencies in unsound.gemspec
gemspec

group :test do
  gem "rspec"
end

group :development do
  gem "yard"
end

group :debug do
  gem "pry"
  gem "pry-byebug"
  gem "pry-doc"
end

group :metrics do
  gem "rubocop", require: false

  platform :mri do
    gem "mutant"
    gem "mutant-rspec"
  end
end
