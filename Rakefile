require "rake/clean"

SITE_DIRECTORY = "_site"
CLOBBER << SITE_DIRECTORY

desc "builds the site"
task "build" do
  sh "jekyll build"
end

desc "check hyperlinks for issues"
task "checklinks" => "build" do
  sh "check-links #{SITE_DIRECTORY}"
end

task "default" => "checklinks"
