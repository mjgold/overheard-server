source "https://rubygems.org"

gem 'sinatra', '~>1.4'
gem 'datamapper', '~>1.2'
gem 'faker', '~>1.4'

group :development do
  gem 'sqlite3', '~>1.3'
  gem 'dm-sqlite-adapter', '~>1.2'

  gem 'rerun', '~>0.10'
  gem 'dotenv', '~>0.11'

  gem 'minitest', '~>5.4'
end

group :test do
  gem "minitest-capybara", '~>0.7'
  gem "rack-test", "~>0.6"
end


group :production do
  gem 'dm-postgres-adapter', '~>1.2'
  gem 'pg', '~>0.17'
end
