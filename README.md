Satellite Data and Models for Computational Climate or Agricultural Science
===========================================================================

Installation and Setup
----------------------

```sh
# Install dependencies using Ubuntu package manager
sudo apt install ruby-bundler ruby-dev

# It's easier to install the Ruby packages to a user directory;
#   or, a project-specific directory
LOCAL_RUBY_PATH="/home/arthur/.ruby"
mkdir -p $LOCAL_RUBY_PATH
bundle config set --local path $LOCAL_RUBY_PATH

bundle install
```
