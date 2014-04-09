# Label

[![Gem Version](https://img.shields.io/gem/v/label.svg)](https://rubygems.org/gems/label)
[![Build Status](https://img.shields.io/travis/jgorset/label.svg)](https://travis-ci.org/jgorset/label)
[![Dependency Status](https://img.shields.io/gemnasium/jgorset/label.svg)](https://gemnasium.com/jgorset/label)
[![Code Climate](https://img.shields.io/codeclimate/github/jgorset/label.svg)](https://codeclimate.com/github/jgorset/label)
[![Coverage Status](https://img.shields.io/coveralls/jgorset/label.svg)](https://coveralls.io/r/jgorset/label)

Label labels the gems in your Gemfile.

## Installation

    $ gem install label

## Usage

    $ label

Label will look for a `Gemfile` in your current working directory, but you can
tell it to look somewhere else if you like:

    $ label /path/to/Gemfile

```ruby
# /path/to/Gemfile

source 'http://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

# Flexible authentication solution for Rails with Warden
gem 'devise'

# Upload files in your Ruby applications, map them to a range of ORMs, store
# them on different backends.
gem 'carrierwave'

# RailsAdmin is a Rails engine that provides an easy-to-use interface for
# managing your data.
gem 'rails_admin'
```

Oh, and let's be real; you will always want to use label.

```bash
alias bundle="bundle && label"
```

## I love you

Johannes Gorset made this. You should [tweet me](http://twitter.com/jgorset) if you can't get
it to work. In fact, you should tweet me anyway.
