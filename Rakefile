require 'rubygems'
require 'bundler/setup'

task :default => :spec

begin
  require 'rspec/core/rake_task'
  desc "run specs"
  task :spec do
    system("ruby -v")
    RSpec::Core::RakeTask.new
  end
rescue NameError, LoadError => e
  puts e
end
