# Changelog

## [unreleased]
* Remove requirement to provide next.js
* Fix withRouter wrapper

## 3.0.0 - 2020-03-08
* rewrite route definition API so it's considerably more approachable.
* Automatically generate asPath from the route URL given.
* Add tests

## 2.2.0 - 2020-01-26
* Use updated validator lib.
* add new `setRoutes` function, which accepts an array of route data arrays.
    - We are leaving this function undocumented for the time being as this API may change in the near future.

## 2.1.2 - 2020-01-26
* Revert from Yarn2/PnP. too new a technology :P

## 2.1.1 - 2020-01-26
* update validator utils, since it was released with some old garbage code.

## 2.1.0 - 2020-01-26
* Ensure route helper class instance is created properly.
* Export Route class

## 2.0.4 - 2020-01-26
* Remove next babel preset.
* Use React.createElement over JSX since we only need it in 2 spots

## 2.0.3 - 2020-01-26
* Hopefully fix this for real this time?

## 2.0.2 - 2020-01-25
* Realized Yarn 2 is a bit weird about prepublish. now we have a 2.0 release :P

## 2.0.1 - 2020-01-25
* Fix documentation error.

## 2.0.0 - 2020-01-25
* **BREAKING** Properly respect package boundaries by having the user provide what we need for us. (yay)
    - Refer to the updated example config in `README.md`.
* Convert to Yarn2 / PnP.
* Add better argument validation via our new validation utility library.

## 1.1.0

### Changes
* rewrite `withRouter` implementation. Solution: just use `hoist-non-react-statics`!

## 1.0.0

* Initial public release
