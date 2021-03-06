# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.3.0] - 2019-01-09
### Changed
- Bye `pages.json`! Welcome store-builder.

### Fixed
- Spacing between login credentials and login options.

## [2.2.1] - 2019-01-04
### Changed
- Use `ButtonWithIcon` in favour of `Button` from styleguide. 

### Fixed
- Create `GoBackButton` to remove duplicated code.

## [2.2.0] - 2018-12-17
### Added
- Support to messages builder.

## [2.1.0] - 2018-12-14
### Changed
- Use `vtex.auth` lib instead of mutations to perform authentication operations.
- Bump `vtex.styleguide` major version.

### Fixed
- Add design tokens on labels. 

## [2.0.4] - 2018-11-29
### Changed
- Use of `vtex.use-svg` lib to display icons.

## [2.0.3] - 2018-11-27
### Added
- Internationalization on all the inputs placeholder.

## [2.0.2] - 2018-11-23
### Changed
- Use icons from the dreamstore icon pack.

## [2.0.1] - 2018-11-09
### Fixed
- Fix redirect behavior, now this function is called only when `/login` is in path

## [2.0.0] - 2018-11-08
### Changed
- Replace tachyons classes with design tokens.
- Use icons from dreamstore icon pack.

## [1.6.5] - 2018-11-08
### Fixed
- Fix Account Options is showing before complete login action

## [1.6.4] - 2018-10-18
### Fixed
- *Hotfix* - Move out the return null of redirect logic.

## [1.6.3] - 2018-10-18
### Fixed
- Fix redirect behavior, now this function is called only when `returnUrl` is defined in location.search.

## [1.6.2] - 2018-10-09
### Fixed
- Warning message on loading element being a function.

## [1.6.1] - 2018-10-02
### Fixed
- Await before logout to avoid reloading before logging out

## [1.6.0] - 2018-10-02
### Changed
- Uses session query provided by vtex.store

## [1.5.6] - 2018-09-26
### Fixed
- Redirecting to the previous route in the app when the user tries to go to Login when already logged

## [1.5.5] - 2018-09-26
### Fixed
- Login does not break when there are no options. Now it allows the user to refetch it.

## [1.5.4] - 2018-09-24
### Changed
- Hide label in screens thinner than the laptop resolution.

## [1.5.3] - 2018-09-14
### Fixed
- Redirect to return URL after login success.

## [1.5.2] - 2018-09-13
### Changed
- Change My Orders to My account route. 

## [1.5.1] - 2018-09-12
### Fixed
- Add HOC `withSession` to the `LoginContent` component.

## [1.5.0] - 2018-09-06
### Added
- Add HOC `withSession` to initialize user session.

### Changed
- Change profile query to session query. 

## [1.4.1] - 2018-09-05
### Changed
- Update the `Login` to receive classnames for the label and icon.

## [1.4.0] - 2018-08-31
### Changed
- Update `Styleguide` version.

## [1.3.1] - 2018-08-24
### Added
- Add CSS class to `Login` label.

## [1.3.0] - 2018-08-23
### Added
- `LoginContent` animation.

## [1.2.2] - 2018-08-21
### Fixed
- Box position to be compatible with the new header design.

## [1.2.1] - 2018-08-20
### Fixed
- Fix email to e-mail in `pt-BR` translate.

## [1.2.1] - 2018-08-20
### Fixed
- Fix email to e-mail in `pt-BR` translate.

## [1.2.0] - 2018-08-17
### Added
- prop `fillColor` to `ProfileIcon` component.
- props `iconLabel`, `iconSize`, `iconColor` to `Login` component.

## [1.1.4] - 2018-08-17
### Fixed
- `Tooltip` position and container width.
- Close `Login` when clicking outside it.

## [1.1.3] - 2018-08-08
### Fixed
- Login page options when displaying login form.

## [1.1.2] - 2018-08-07
### Changed
- Add slugify in `providerName` CSS token.

## [1.1.1] - 2018-08-06
### Fixed
- `LoginOptions` throwing error on invalid element type

## [1.1.0] - 2018-08-02
### Added
- `Tooltip` component to show to the user if the password is attending the requisites.
- Schema into `Login` component.

### Fixed
- `LoginContent` form position.

## [1.0.1] - 2018-07-30
### Fixed
- Console warning of `loginTitle` being undefined.

## [1.0.2] - 2018-07-30
- Fix error of undefined LoginOption props.

## [1.0.1] - 2018-07-30
### Fixed
- Console warning of `loginTitle` being undefined.

## [1.0.0] - 2018-07-26
### Added
- Receive from the `VTEX-ID` all the login options available to authenticate users.
- Arrow icon to the back button.

### Changed
- Validation component tick color to red (error) and green (success).

## [0.10.0] - 2018-07-26
### Added
- `PasswordInput` to validate the password and show the validation to the user.
- Show password icon.

## [0.9.13] - 2018-07-25
### Fixed
- `LoginContent` position to be always under the `ProfileIcon`.

## [0.9.12] - 2018-07-24
### Fixed
- Fix onClick handle of recovery password.

## [0.9.11] - 2018-07-24
### Added
- Now, placeholders are customize by schema props.

### Changed
- Allow breakline on Login Titles.

## [0.9.10] - 2018-07-24
### Added
- Support for attribute `closeonclick` to close on click events inside modal.

### Changed
- Update CCS classes to improve customization.

## [0.9.9] - 2018-07-24
### Fixed 
- Set default option correctly in `LoginContent`.

## [0.9.8] - 2018-07-23
### Added
- Add `ExtensionContainer` to allow multiple `ExtensionPoints`.

### Fixed
- Set cookie properly when is a social login. 

## [0.9.7] - 2018-07-19
### Changed
- Move css back to tachyons classes.
- Refactor form structure to generic component.

## [0.9.6] - 2018-07-16
### Added
- Add `ExtensionPoint` as a custom login option.

## [0.9.5] - 2018-07-13
### Added
- Default callback after login success.

### Fixed
- Get profile after login.

## [0.9.4] - 2018-07-12
### Fixed
- Callback after login success.

## [0.9.3] - 2018-07-12
### Fixed
- Fix oAuth Set-Cookie in `LoginContent`. 

## [0.9.2] - 2018-07-11
### Fixed
- Add intl and css in `LoginContent`.

## [0.9.1] - 2018-7-9
### Fixed
- Icon not showing on mobile.

## [0.9.0] - 2018-7-9
### Changed
- Render login icon as a link when mobile.

## [0.8.0] - 2018-7-6
### Fixed
- The Login button padding.

### Added
- `LoginContent` component.

### Changed
- Moved from tachyons classes to custom classes with the tachyons properties.

## [0.7.2] - 2018-7-6
### Changed
- Change to HTML button instead of VTEX Style Guide.

## [0.7.1] - 2018-7-5
### Fixed
- Intl of the OAuth Component.

## [0.7.0] - 2018-7-5
### Added
- `OAuth` with Facebook account.

## [0.6.0] - 2018-7-5
### Added
- `OAuth` with Google account.

## [0.5.0] - 2018-7-4
### Added 
- Add recovery password in classic login.

## [0.4.0] - 2018-6-28
### Added 
- Add validation on email, password and code inputs. 

## [0.3.0] - 2018-6-28

### Added
- Login with email and password.

## [0.2.1] - 2018-6-26
### Changed
- Add email when user profile don't have firstName.

### Fixed 
- Fix `accessKeySignIn` and `sendEmailVerification` mutations to reflect the changes in resolvers. 

## [0.2.0] - 2018-6-14
### Added
- Add form in login inputs and my-orders route in account options.
- Remove My Profile from Account Options. 

## [0.1.0] - 2018-6-11

### Added
- Add Account content when user is logged.

## [0.0.2] - 2018-6-8
### Changed
- Rename `index` to `Login`

## [0.0.1] - 2018-6-8
### Added
- Add _Login_ app.
