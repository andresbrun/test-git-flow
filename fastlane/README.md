fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew cask install fastlane`

# Available Actions
## iOS
### ios release_start
```
fastlane ios release_start
```
Create a new release candidate version. i.e: bundle exec fastlane release_start version:7.1.2
### ios release_finish
```
fastlane ios release_finish
```
Merges the release branch into master & develop, then it deletes it. i.e: bundle exec fastlane release_finish version:7.1.2
### ios hotfix_start
```
fastlane ios hotfix_start
```
Create a new hotfix version from master. i.e: bundle exec fastlane hotfix_start version:7.1.2
### ios hotfix_finish
```
fastlane ios hotfix_finish
```
Close a previous hotfix version. i.e: bundle exec fastlane hotfix_finish version:7.1.2

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
