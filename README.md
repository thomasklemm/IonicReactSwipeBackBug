# IonicReactSwipeBackBug

Reproduction of a bug happening in Ionic React v6.0.0-rc.3.

According to the Ionic React docs the config setting for `swipeBackEnabled` is still present in v6: [Ionic React v6 Config](https://beta.ionicframework.com/docs/react/config)

However, as can be seen when building this app in multiple stages, the `swipeBackEnabled: false` settings is not longer respected in Ionic React v6 (using the latest v6.0.0-rc.3).
The swipe back gesture is always active and can't currently be disabled by that setting.
