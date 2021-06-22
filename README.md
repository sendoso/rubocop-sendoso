# RuboCop Sendoso

This repository provides recommended Rubocop configuration for use on Sendoso Ruby projects.

## Installation

Add this line to your application's Gemfile:

```ruby
group :development do
  gem 'rubocop-sendoso', require: false, github: 'sendoso/rubocop-sendoso'
end
```

And then execute:

    $ bundle install


## Usage

First create a new file called `.rubocop.yml` in your root directory if it doesn't exist yet
and add the following to the top of `.rubocop.yml`
```
inherit_gem:
  rubocop-sendoso: default.yml
```

