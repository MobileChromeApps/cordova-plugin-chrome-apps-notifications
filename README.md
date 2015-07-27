# chrome.notifications Plugin

This plugin allows apps to show notifications in the status bar.

## Status

Stable on Android; not supported on iOS.

## Reference

The API reference is [here](http://developer.chrome.com/apps/notifications.html).

# Release Notes

## 1.3.1 (July 27, 2015)
- Allow gopher: in URLs (http://crbug.com/513352)

## 1.3.0 (June 1, 2015)
- Allow data: URLs for icons

## 1.2.0 (April 30, 2015)
- Renamed plugin to pubilsh to NPM
- Now using cordova-background-app@2.0.0 for better background processing

## 1.1.1 (Mar 17, 2015)
* Remove version constraint on backgroundapp dependency due to plugman bug CB-8696

## 1.1.0 (Mar 17, 2015)
* Use `org.chromium.backgroundapp` for background events

## 1.0.7 (Jan 27, 2015)
* More fully stub out chrome.notifications on iOS (fixes #485)
* Fix javascript validation when updating notifications (fixes #224)

## 1.0.6 (November 17, 2014)
- Refactor notifications to follow same paradigm as Alarms on Android

## 1.0.5 (October 21, 2014)
- Documentation updates.

## 1.0.4 (August 20, 2014)
- Add support for progress notifications

## 1.0.3 (April 1, 2014)
- Expand basic notification when message text overflows.

## 1.0.2 (March 10, 2014)
- Use `android.support.v4` instead of `com.google.android-support`

