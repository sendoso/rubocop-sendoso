# RuboCop Sendoso

This repository provides recommended Rubocop configuration for use on Sendoso Ruby projects.

## Installation

Add this line to your application's Gemfile replacing the `tag` value with the most recent Github
tag:

```ruby
group :development do
  gem 'rubocop-sendoso', github: 'sendoso/rubocop-sendoso', tag: 'vx.x.x', require: false
end
```

And then execute:

    $ bundle install


## Usage

First create a new file called `.rubocop.yml` in your root directory if it doesn't exist yet
and add the following to the top of `.rubocop.yml`
```
inherit_gem:
  rubocop-sendoso: config/default.yml
```

