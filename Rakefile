require 'html-proofer'

task :test do
  options = { assume_extension: true }
  HTMLProofer.check_directory('./_site', options).run
end
