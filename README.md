# What's this

This repository disiplays the initial Rails configration after running the below commands.

```
$ rails --version
Rails 6.1.3
$ rails new rails-6.1.3-webpacker-initial-setup --webpack --skip-turbolinks --skip-sprocket --skip-active-storage
$ cd rails-6.1.3-webpacker-initial-setup
$ bin/rails webpacker:install:typescript
$ bin/rails webpacker:install:react # Then resolve a conflict with babel.config.js
$ bin/rails webpacker:compile # Succeeds
```

