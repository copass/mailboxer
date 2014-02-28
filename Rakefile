require 'rubygems'
require 'bundler/setup'

require "bundler/gem_tasks"

require 'appraisal'
require 'rspec/core'
require 'rspec/core/rake_task'
RSpec::Core::RakeTask.new(:spec)
task :default => :spec

task :console do
  require 'irb'
  require 'irb/completion'
  require 'mailboxer' # You know what to do.
  ARGV.clear
  IRB.start
end