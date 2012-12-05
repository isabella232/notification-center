Capistrano + Notification Center
=========================

capistrano-nc integrates Capistrano and Mountain Lion's Notification Center.

![Screenshot](http://f.cl.ly/items/1k253H0o350m1F0L371j/Screen%20Shot%202012-09-29%20at%2012.57.34%20PM.png)

Installation
------------

Just put `gem 'capistrano-nc'` in your Gemfile and add `require "capistrano-nc"` at the top of your deploy.rb. That's it!

By default it will run the `nc:finished` task after your `deploy` or `deploy:migrations`. If this behavior doesn't suit you, you can hook `nc:finished` to any custom task by editing `deploy.rb`:

```
after `your:task`, `nc:finished`
```

##Contributors

- [Kir Shatrov](https://github.com/kirs/) (Evrone)

##Feel free to pull request!

