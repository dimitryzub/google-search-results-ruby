require 'rake'
require 'rspec/core/rake_task'

RSpec::Core::RakeTask.new(:test) do |t|
  t.pattern = Dir.glob('test/*_spec.rb')
  t.rspec_opts = '--format documentation'
end

task :default => :test
