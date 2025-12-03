# frozen_string_literal: true

source "https://rubygems.org"

# Specify your gem's dependencies in umappp.gemspec
gemspec

# Allow overriding rice version via environment variable for testing
if ENV["RICE_VERSION"]
  gem "rice", ENV["RICE_VERSION"]
end

gem "rake"

gem "rake-compiler"

gem "test-unit"

group :examples do
  gem "gr-plot"
  gem "numo-gnuplot"
  gem "red-datasets"
  gem "red-datasets-numo-narray"
end
