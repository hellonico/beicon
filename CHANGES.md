# Changelog #

## Version 0.6.1 ##

Date: 2016-01-28

- Add `take-until` function.


## Version 0.6.0 ##

Date: 2016-01-22

- The old `timeout` function becomes `timer`.
- Add proper `timeout` function.
- Add `delay` function.
- Add `interval` function.
- Add support for schedulers (`subscribe-on` and `observe-on`).
- Make cats dependency optional (only if you require `beicon.monad` ns).
  (Is responsability of the user include the appropriate cats version).
- Start using clojure 1.8 and clojurescript 1.7.228.

## Version 0.5.1 ##

Date: 2016-01-08

- Fix wrong path to the minified version of bundled rxjs.


## Version 0.5.0 ##

Date: 2015-12-23

- Add `sample` function.


## Version 0.4.0 ##

Date: 2015-12-23

- Add `debounce` function.
- Allow multimethods on `on-value`, `on-error` and `on-end`.


## Version 0.3.0 ##

Date: 2015-12-08

- Fix wrong precondition on `repeat` function.
- Add `scan` function.
- Add `from-promise` function.
- Add `retry` function.
- Add `with-latest-from` function.
- Add `catch` function.
- Add `from-exception` function.
- Add `empty` function.
- Add `share` function.
- Add `merge-all` function.
- Add `of` function.
- Add `just` function (once is now an alias for just).
- Implement `never` in function of empty.
- Improve `zip` function allowing passing user defined
  join functon.
- Changed call signature of `to-atom` for consistency
  with the subscribe related functions.


## Version 0.2.0 ##

Date: 2015-12-03

- Fix incompatibilities with advanced compilations.
- Add new and improved externs.
- Update to rxjs 4.0.7


## Version 0.1.1

Date: 2015-11-03

- Update bundled rxjs to 4.0.6.


## Version 0.1.0

Date: 2015-11-02

- Initial release.
