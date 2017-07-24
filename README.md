# ionic-calabash
A simple guide to have running calabash test on a ionic project

### Quick Definiton
Calabash is a test automation framework that enables mobile developers and pretty much anyone without coding skills to create and execute automated acceptance tests for Android and iOS apps.

Calabash works by enabling automatic UI interactions within an application such as pressing buttons, inputting text, validating responses, etc. 

While this is a great first step in automated UI acceptance test automation, the real benefits can be gained when Calabash tests are executed on real mobile devices.



### Requiriments

Is recommend that you use the most recent released version of Xcode, MacOS, and Ruby.

MacOS 10.10 or 10.11

Xcode 7 or 8

iOS Devices >= 9.0

iOS Simulators >= 9.0

ruby >= 2.0 (latest is preferred)

### Quick Septup

Calabash requires Ruby to be installed on your machine. First, check whether you have Ruby installed on your machine:

```
# On Console:
$ ruby -v
```
##### In addition, if you plan to manage several versions of Ruby, it’s recommended to use tools like rbenv.

```
$ gem install bundler
$ bundle install
```

#### ANDROID

```
# If you want to use Calabash for Android, make sure you have the latest and greatest SDK installed.
$ gem install calabash-android
```

#### IOS

```
# For the host machine, it’s recommended to have (at least) Mac OS 10.11 (Capitan) or 10.12 with Xcode 7.x or 8.x. d.
$ gem install calabash-cucumber
```

### If you are using Mac OS X, you could also use cURL to fetch all files to your machine:
```
$ curl -sSL https://raw.githubusercontent.com/calabash/install/master/install-osx.sh | bash
```

### There's a problem with the syntax highlighting of a file

#### Documentation

##### Vim
```
# Some examples of various styles:
vim: syntax=java
vim: set syntax=ruby:
vim: set filetype=prolog:
vim: set ft=cpp:
```

## Contributing

Please check out our [contributing guidelines](CONTRIBUTING.md).
