require 'rubygems'
require 'bundler/setup'
require 'rspec/core/rake_task'

RSpec::Core::RakeTask.new(:spec) do
  system("ruby -v")
end

task :default => :spec
