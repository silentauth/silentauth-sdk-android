
# SilentAuth SDK for Android

Change Log
==========
## Version 1.0.9
_2023-07-05_
**Changes**
- targetSdkVersion updated to 34
- kotlin_version updated to 1.8.10
- gradlePluginVersion updated to 8.4.2
- gradleVersion updated to 8.6
- JavaVersion updated to 17
- Previously deprecated `postWithDataCellular` method and relevant testing removed

## Version 1.0.8
_2023-03-06_
**Changes**
- `send` and `post` methods updated to prevent http call requests
- `post` method amended to prevent CRLF injections
- `postWithDataCellular` method now deprecated and will be removed in future releases
**Bug Fix**
- `sendAndReceive` method updated

## Version 1.0.6
_2023-08-14_
**Bug Fix**
- `makeHTTPCommand` empty path handling

## Version 1.0.5
_2023-07-06_
**Changes**
- kotlin_version 1.5.20
- compileSdkVersion 33
- targetSdkVersion 33
- **Bug Fix**
- HTTP status parsing
  **New**
- Convenience method `postWithDataCellular`

## Version 1.0.4
_2023-04-26_
**New**
- Changes removing dependency on commons-io

## Version 1.0.3
_2023-02-01_
**New**
- New method `openWithDataCellularAndAccessToken`

## Version 1.0.2
_2022-11-03_
**Changes**
- targetSdkVersion increased to 31 (Android 12)

## Version 1.0.1
_2022-10-10_


**Release of silentauth-sdk-android**
