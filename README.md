# tempate.github.io

This is my personal Github Pages site.

## Run locally

1. Install Ruby (for Manjaro)

```
sudo pacman -S ruby
```

2. Install Bundler and Jekyll

```
gem install bundler jekyll
```

3. Configure Bundler to install gems locally

```
bundle config set --local path 'vendor/bundle'
```

4. Install the required gems from the Gemfile

```
bundle install
```

5. Run the site locally

```
bundle exec jekyll serve
```
