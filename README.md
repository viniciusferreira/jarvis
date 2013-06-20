Deprecated
==========

Please see [JARVIS 2](https://github.com/martinp/jarvis2).

JARVIS
======
A collection of jobs and widgets for
[Dashing](http://shopify.github.com/dashing/) that powers my personal info
monitor.

Why Jarvis? Go watch [Iron Man](http://en.wikipedia.org/wiki/Iron_Man_(film\))
:-)

Dependencies
============
Debian packages:
`aptitude install ruby ruby-dev rubygems libxml2-dev libxslt1-dev nodejs`

[Bundler](http://gembundler.com/):
`gem install bundler`

Application dependencies:
`bundle install`

Configuration
=============
All widgets are configured in `jobs/config.yml`. Take a look at
`jobs/config.yml.sample` for examples.

Usage
=====
Use `dashing start` to start the server. Then point your browser to
[http://localhost:3030/jarvis](http://localhost:3030/jarvis)

Screenshot
==========
![Screenshot](https://github.com/martinp/jarvis/raw/master/public/jarvis.png)
