# Redmine Closed Date

## Summary

Add info closed_on on issue view

![sample](sample.png "closed_on")


## Installation

1. Copy the plugin directory into the vendor/plugins directory
2. install plugin

```
   cd redmine/plugins
   git clone https://github.com/fraoustin/redmine_closed_date.git
   bundle exec rake deface:precompile RAILS_ENV=production
   bundle exec rake deface:clean RAILS_ENV=production

```

restart Redmine
