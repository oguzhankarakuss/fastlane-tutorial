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
or alternatively using `brew install fastlane`

# Available Actions
## iOS
### ios add_badge_to_app_icon
```
fastlane ios add_badge_to_app_icon
```
Add Badge
### ios commit_beta_version
```
fastlane ios commit_beta_version
```

### ios notify_in_slack
```
fastlane ios notify_in_slack
```
Notify
### ios test_flight_beta
```
fastlane ios test_flight_beta
```
Push a new beta build to TestFlight

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
