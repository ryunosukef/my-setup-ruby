my-setup-ruby
=============

インストールするgemを管理するために、Bundlerを使う

```
 fujimoto  ~  rbenv versions
  system
* 2.1.1 (set by /Users/fujimoto/.rbenv/version)
 fujimoto  ~  gem list

*** LOCAL GEMS ***

CFPropertyList (2.2.0)
libxml-ruby (2.6.0)
nokogiri (1.5.6)
sqlite3 (1.3.7)
 fujimoto  ~  gem install bundler
Fetching: bundler-1.6.2.gem (100%)
ERROR:  While executing gem ... (Gem::FilePermissionError)
    You don't have write permissions for the /Library/Ruby/Gems/2.0.0 directory.
 fujimoto  ~  sudo gem install bundler                               1
Password:
Fetching: bundler-1.6.2.gem (100%)
Successfully installed bundler-1.6.2
Parsing documentation for bundler-1.6.2
Installing ri documentation for bundler-1.6.2
1 gem installed
 fujimoto  ~  gem list

*** LOCAL GEMS ***

bundler (1.6.2)
CFPropertyList (2.2.0)
libxml-ruby (2.6.0)
nokogiri (1.5.6)
sqlite3 (1.3.7)
```

