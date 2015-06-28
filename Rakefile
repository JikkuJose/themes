require 'fileutils'

home = ENV['HOME']
pwd = ENV['PWD']

desc "Setup themes"
task :setup_themes do
  FileUtils.ln_sf "#{pwd}/Tomorrow-Night.vim", "#{home}/.vim/colors/Tomorrow-Night.vim"
end

task default: :setup_themes
