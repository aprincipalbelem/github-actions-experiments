# frozen_string_literal: true

source "https://rubygems.org"
PACKAGE_CLOUD = 'https://packages.shopify.io/shopify/gems'

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# Super relevant comment
gem "rspec", "~> 3.10"
unless ENV["GITHUB_ACTIONS"]
  gem "monorail", source: PACKAGE_CLOUD
end
