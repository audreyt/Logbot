
source 'https://rubygems.org'

gem 'jellyfish', '~>1.1.1' # web
gem 'rack',      '~>1.5.2' # web
gem 'cinch',     '~>2.3.3' # agent
gem 'redis',     '~>3.3.2' # used in web and agent

# All of below are optional/selectional:
group :server do
  gem 'foreman', '~>0.82.0'

  platform(:ruby) do
    gem 'yahns', '~>1.9.0'
  end

  platform(:jruby) do
    gem 'trinidad', '~>1.4.6'
  end
end

# compile assets
group :assets do
  gem 'compass', '~>0.12.4'
  gem 'sass',    '~>3.2.17'
end

group :test do
  gem 'pork', '~>2.0.0'
end
