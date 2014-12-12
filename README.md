#lein-flyway

##Intro

Leiningen Plugin for Database Migration Tool [Flyway](http://flywaydb.org/).

This plugin is alpha version, expecting defects.

##Usage

### Latest version

![Clojars Project](http://clojars.org/com.github.metaphor/lein-flyway/latest-version.svg)

### Configuration
lein-flyway tries to align with offical configuration properties, please refer to [sample.project.clj](https://github.com/metaphor/lein-flyway/blob/master/sample.project.clj) for configuration details.

### Leiningen Tasks


```shell
lein flyway ${subtask}
```
And *subtask* includes following flyway aligned tasks,

* clean
* validate
* migrate
* baseline
* repair
* info

##LICENSE

Copyright © Zhiheng Li

Licensed under the EPL (see the file LICENSE)
