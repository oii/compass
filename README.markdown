# Compass Stylesheet Authoring Framework

## Butchery

The following commands were used to convert this repo to something that can be directly `submodule`'d into a project:

    git mv frameworks/compass/stylesheets/compass/* .
    git rm -rf bin compass.gemspec CONTRIBUTING.md doc-src examples features frameworks gemfiles lib test .gitignore .project .rspec .travis.yml CONTRIBUTING.md Gemfile Gemfile_rails2 Guardfile Rakefile TODO.md compass.gemspec

This branch can be used as a submodule with the following:

    git submodule add https://github.com/oii/compass.git sass/compass

And then included into a `sassc` run with:

    sassc -I sass/compass input.scss output.css

Build Status: [![Build Status](https://travis-ci.org/chriseppstein/compass.png)](https://travis-ci.org/chriseppstein/compass)

Code Quality: [![Code Climate](https://codeclimate.com/badge.png)](https://codeclimate.com/github/chriseppstein/compass)

## Resources

* [Compass Homepage](http://compass-style.org/)
* [Installing Compass](http://compass-style.org/install/)
* [Compass Reference](http://compass-style.org/install/reference/)

## Author
Compass is written by [Chris Eppstein](http://chriseppstein.github.com/).<br>
Chris is the Software Architect of [Caring.com](http://caring.com) and a member of the [Sass](https://github.com/nex3/sass) core team.

## Core Team Members

* [Scott Davis](https://github.com/scottdavis)
* [Eric Meyer](https://github.com/ericam)
* [Brandon Mathis](https://github.com/imathis)
* [Anthony Short](https://github.com/anthonyshort/)

## Major Contributors

* [Nico Hagenburger](https://github.com/hagenburger)

## License
Copyright (c) 2008-2009 Christopher M. Eppstein<br>
All Rights Reserved.<br>
Released under a [slightly modified MIT License](compass/blob/stable/LICENSE.markdown).
