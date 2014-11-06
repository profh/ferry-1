![ferry](doc/ferry_readme_icon_2.png)

<!-- ![Build Status](https://travis-ci.org/cmu-is-projects/ferry.png)(https://travis-ci.org/cmu-is-projects/ferry) -->

## What is Ferry?
Ferry is a command-line tool rubygem designed for for data migrations and manipulation, maintained as an open-source project by the students of [Carnegie Mellon's Information Systems department](http://www.cmu.edu/information-systems/) currently [Anthony Corletti](http://github.com/anthcor) and [Logan Watanabe](http://github.com/loganwatanabe). The inspiration for ferry was brought from collective internship experiences and from the growing prevalence of big data migration and manipulation challenges that companies, corporations, universities, and organizations face in today's information age.

## What can I use Ferry for? (Use Cases)
See the [ferry_demo](http://github.com/cmu-is-projects/ferry_demo.com) app or our [GitHub pages site](http://cmu-is-projects.github.com/ferry) for guidance on using Ferry!

Migration and Manipulation use cases
  - Exporting data to various file formats (.csv, .yml, .sql)
  - Importing data from various file formats
  - Migrating data to third party hosts (Amazon S3, Oracle)
  - Migrating data to a different database

## TO-DOs
- [ ] Refactoring before public release October 17th!!!
- [ ] TEST!!! EVERYTHING!!!
  - [ ] Provide working example(s) of using ferry (see [ferry_demo](http://github.com/cmu-is-projects/ferry_demo.com) app)
- [x] ferry --help
- [ ] CLI tool dev
  - [ ] USING OPTION PARSER
- [x] Simple CSV/YAML export & import
  - [x] using sqlite3
  - [x] using psql
  - [x] using MySQL
  - [ ] using other dbs ...
- [ ] Forking processes to make them faster!
- [ ] RESTful column interaction
- [ ] db switcher
  - [ ] handling dependency installation (db or gem dependencies)
- [ ] 3rd party connections (importing and exporting data to S3 or related services)
  - [ ] Understanding relationships between generating migrations and migration files in place
- [ ] Rolling back on errors / mishaps during migrations and manipulations
  - [ ] error catching and give proper clues to fix errors
- [ ] Host documentation site via GitHub pages

## Installation
Add this line to your application's Gemfile:
``` ruby
gem 'ferry'
```

And then execute:
``` sh
bundle
```

Or install it yourself as:
``` sh
gem install ferry
```

To view what Ferry can do for you just run:
``` sh
ferry --help
```

## Contributing

1. Fork it ( https://github.com/[my-github-username]/ferry/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
