### Setting this repo up:
1. [Install Homebrew](https://brew.sh/)
2. Install asdf and ruby:
```
brew install asdf
asdf plugin add ruby
asdf plugin-update ruby
asdf install ruby latest
asdf reshim
asdf global ruby latest
```
3. Install Jekyll: `gem install bundler jekyll`

### Dev Loop
1. Run Jekyll:
`bundle exec jekyll serve`
2. Go to http://127.0.0.1:4000/