require 'fileutils'

home = ENV['HOME']

desc "Setup themes"
task :setup_themes do
  FileUtils.ln_sf './Tomorrow-Night.vim', "#{home}/.vim/colors/Tomorrow-Night.vim"
end

task default: :setup_themes
