# CHANGELOG for chef-handler-sns

This file is used to list changes made in each version of `chef-handler-sns`.

## 1.2.0:

* README:
 * Added Method 2.2: LWRP inside OpsWorks (related to [issue #4](https://github.com/onddo/chef-handler-sns/issues/4)).
 * Add a note in the method 2 about convergence phase (related to [issue #3](https://github.com/onddo/chef-handler-sns/issues/3)).
 * Some capitals fixed.
 * Added ohai credentials explanation (related to [cookbook issue #1](https://github.com/onddo/chef_handler_sns-cookbook/issues/1)).
 * *filter_opsworks_activities* documentation improved.
 * Use [shields.io](http://shields.io/) badges.
 * *Contributing* section completed.
* Fixed *AWS::SNS::Errors::InvalidClientTokenId* when using version 1.1.0 ([issue #5](https://github.com/onddo/chef-handler-sns/issues/5), thanks [Michael Hobbs](https://github.com/michaelshobbs) for reporting and testing).

## 1.1.0:

* Filter Notifications by Opsworks Activity ([issue #2](https://github.com/onddo/chef-handler-sns/pull/2), thanks [Florian Holzhauer](https://github.com/fh))

## 1.0.0:

* Replaced `right_aws` dependency with `aws-sdk` gem.
  * Update the tests and the README.
* Add security tokens support.
* IAM roles support ([issue #1](https://github.com/onddo/chef-handler-sns/issues/1), thanks [Michael T. Halligan](https://github.com/mhalligan) for reporting).
  * Read AWS credentials from Ohai (IAM role) by default.
* Gemfile: add_development_dependency for Ruby 1.8 compatibility now checks ruby version.
* Travis: added Ruby 2.1 to the tests.
* LICENSE: brackets replaced by copyright owner.
* Added Coverall badge again.
* Multiple README improvements and fixes.

## 0.2.6:

* Gemspec: added license.

## 0.2.5:

A Bug fix release:
* Multiple fixes in the README examples.
* Removed coveralls link from the README, sends erroneus reports.
* Added `.coveralls.yml` file.
* Removed the needless `require 'rubygems'` from the tests.
* Added `simplecov` gem for coverage tests.
* Force `mime-type` version to `~> 1.0` to fix the tests on some cases (travis related).
* Homepage changed to *GitHub Pages*.

