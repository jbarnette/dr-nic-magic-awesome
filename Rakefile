require "rubygems"
require "rake"
require "active_support"

task :default do
  puts "It is now #{Time.now.utc + 10.hours} in Brisbane, Australia"
end

namespace :nic do
  GOOD_NIGHTS_SLEEP = 9.hours
  
  desc "Notifies you when to expect Dr. Nic"
  task :arrives do
    puts "Nic arrives at #{(Time.now + GOOD_NIGHTS_SLEEP).strftime('%H:%M on %d-%m-%Y')}"
  end
end