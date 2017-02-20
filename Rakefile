task :default => :build

task :build do
  sh "docker build -t automaticgiant/httrack-git -t lastbuild ."
end

task :push do
  sh "docker push automaticgiant/httrack-git"
end
