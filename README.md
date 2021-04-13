# mroelandts.github.io
static page

Go to [webpage](https://mroelandts.github.io/mroelandts)

## build and test locally
```bash
sudo apt-get install ruby-full build-essential zlib1g-dev
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
gem install jekyll bundler
bundle install
bundle exec jekyll serve
```

## Links
* [Jekyll](https://jekyllrb.com)
* [Minimal Mistakes](https://mademistakes.com/work/minimal-mistakes-jekyll-theme)
