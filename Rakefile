
desc "Build"
task :build do
  sh "jekyll build -s src -d docs --config ./_config.yml"
  sh "touch docs/.nojekyll"
end
