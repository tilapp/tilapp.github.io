<!-- omit in toc -->
# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.5.0 - 2023-10-31

### Added

- Riverpod provider for OrganizationDB instance
- Riverpod provider for FriendRequestDB instance

### Changed

- Changed project structure to a feature-first structure

## 0.4.1 - 2023-10-26

### Fixed

- `@riverpod` to `@Riverpod(keepAlive: true)` because previous generated providers had `autoDispose = true`
- Create NavigatorState keys during build

## 0.4.0 - 2023-10-26

### Added

- Sign In page
- Sign Up page
- Riverpod provider for PostDB instance
- Riverpod provider for settings
- Riverpod provider for loggedInUser
- `LimitedLayout` for pages when you aren't logged in (limited home, sign in, sign up)
- Another `ShellRoute` for limited layout routes
- GlobalKeys for route `navigatorKey` / `parentNavigatorKey`
- VSCode task: `dart: build_runner` to run `build_runner` in watch mode
- Ability to log out from settings page
- Light mode/dark mode toggle
- Dependencies:
  - [riverpod](https://pub.dev/packages/riverpod): ^2.4.4
  - [riverpod_annotation](https://pub.dev/packages/riverpod_annotation): ^2.2.1
  - [freezed_annotation](https://pub.dev/packages/freezed_annotation): ^2.4.1
- Dev-dependencies:
  - [custom_lint](https://pub.dev/packages/custom_lint): ^0.5.5
  - [riverpod_lint](https://pub.dev/packages/riverpod_lint): ^2.3.2
  - [riverpod_generator](https://pub.dev/packages/riverpod_generator): ^2.3.5
  - [build_runner](https://pub.dev/packages/build_runner): ^2.4.6
  - [freezed](https://pub.dev/packages/freezed): ^2.4.5

### Changed

- Renamed `settings_controller.dart` to `settings.dart`
- Use Riverpod annotations and Riverpod generator to generate providers
- Convert PostDB dependent widgets to consumer widgets

### Fixed

- Added missing "TIL" prefix to post content

### Removed

- Unused `widget_test.dart`

## 0.3.0 - 2023-10-25

### Added

- Riverpod provider for UserDB instance
- Dependencies:
  - [flutter_riverpod](https://pub.dev/packages/flutter_riverpod): ^2.4.4
  - [flutter_form_builder](https://pub.dev/packages/flutter_form_builder): ^9.1.1
  - [form_builder_validators](https://pub.dev/packages/form_builder_validators): ^9.1.0

### Changed

- Convert UserDB, settings, or loggedInUser dependent widgets to consumer widgets

## 0.2.0 - 2023-10-17

### Added

- Arabic translation (#444).
- Other Profile page
- Temporary ID generation with [shortid](https://pub.dev/packages/shortid)
- Dependencies:
  - [shortid](https://pub.dev/packages/shortid): ^0.1.2

### Changed

- Moved app to top-level of repo (out of `til/` directory)

## 0.1.0 - 2023-10-11

### Added

- Home page
- New Post page
- Profile page
- Page Not Found page
- `MockupMarkdownView` and `MockupMarkdownPage` for pages written in markdown
- `MainPageLayout` to wrap a component with the app's header and footer
- `User` data model and `UserDB` API
- `Post` data model and `PostDB` API
- `Organization` data model and `OrganizationDB` API
- `FriendRequest` data model and `FriendRequestDB` API
- `UserReport` data model and `UserReportDB` API
- `SettingsController` and `SettingsService` to manage local app settings
- `formatTime` helper function to convert DateTimes to post time strings
- Routing with [go_router](https://docs.page/csells/go_router/navigation)
- Dependencies:
  - [flutter_markdown](https://pub.dev/packages/flutter_markdown): ^0.6.17+3
  - [url_launcher](https://pub.dev/packages/url_launcher): ^6.1.14
  - [google_fonts](https://pub.dev/packages/google_fonts): ^6.1.0
  - [go_router](https://docs.page/csells/go_router/navigation): ^11.1.2
  - [intl](https://pub.dev/packages/intl): ^0.18.1
