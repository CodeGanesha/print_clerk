source 'https://rubygems.org'

gem "office_clerk" , :github => "rubyclerks/office_clerk"
gem "print_clerk" , :path => "../"

gem 'sqlite3'

#asset / production reelated
gem "therubyracer" 
gem "libv8" 
gem "rb-readline"
gem 'uglifier', '>= 1.3.0'

group :development do
  gem 'better_errors' , :platforms=>[:mri_20, :mri_21, :rbx]
  gem 'binding_of_caller', :platforms=>[:mri_19, :mri_20, :mri_21,:rbx]
  gem 'quiet_assets'
  gem "i18n-tasks"
end
group :test do
#  gem "poltergeist"
#  gem "phantomjs"
  gem "codeclimate-test-reporter"
  gem 'rspec-rails'
  gem 'capybara'
  gem 'capybara-screenshot'
  gem 'database_cleaner'
  gem "factory_girl_rails"
  gem 'email_spec'
  gem 'i18n-spec'
  gem 'guard-rails'
  gem 'guard-rspec'
end
