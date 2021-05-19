source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.1.7'
gem 'mysql2', '>= 0.3.18', '< 0.6.0'
gem 'puma', '~> 4.3'
gem 'rack-cors'
gem 'redis', '~> 4.1', '>= 4.1.2'
gem 'jwt_sessions', '~> 2.4', '>= 2.4.1'
gem 'bcrypt', '~> 3.1', '>= 3.1.13'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
