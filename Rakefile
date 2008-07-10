Dir['tasks/**/*.rake'].sort.each { |rakefile| load rakefile }

task :default do
  Rake::Task["copy_assets"].execute(nil)
end
