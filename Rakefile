require 'html-proofer'

task :test do
  options = { 
    :assume_extension => true,
    :check_html => true,
    :check_favicon => true,
    :empty_alt_ignore => true
  }
  HTMLProofer.check_directory("./_site", options).run
end
