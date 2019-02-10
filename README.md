# Chef Repo for Deeptech Infrastructure

## Setup

* `bundle install`
* `bundle exec berks install`
* Bootstrap chef (1st time) : `knife solo bootstrap user@host nodes/xxxxxx.json`
* Running recipe : `knife solo cook user@host nodes/yyyyyy.json`

Use `--no-berkshelf` option if you have to modify the cookbook directly before running knife.
