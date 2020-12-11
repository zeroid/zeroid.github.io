after https://www.kiltandcode.com/2020/04/30/how-to-create-a-blog-using-jekyll-and-github-pages-on-windows/

# Setup
Install latest RubyInstaller for Windows (https://rubyinstaller.org/downloads/). Choose a version with Devkit.
Use default options.
Select Run 'ridk install' on final screen.
Select MSYS2 base installation in the installer script
Restart the cmd.exe shell
gem install jekyll bundler
jekyll -v to confirm jekyll install was successful

# Create a new blog
jekyll new <FULL-PATH>

# Test the blog
jekyll serve

# Themes
https://jekyllthemes.io/

