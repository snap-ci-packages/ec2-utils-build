require 'rubygems'
require 'bundler/setup'

require 'rake/clean'

task :default do
  mkdir_p "pkg"
  cp("rpm/ec2-utils-0.4-1.19.amzn1.noarch.rpm", "pkg")
end
