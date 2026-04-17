desc 'Clean up generated site'
task :clean do
  sh 'rm -rf _site'
end

task :bump do
  sh 'bundle update --ruby'
  sh 'bundle update --bundler'
  sh 'bundle update'
end

task :test do
  sh 'bundle exec jekyll build'
end

task default: :test
