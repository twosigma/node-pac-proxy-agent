
1.0.0 / 2015-07-10
==================

  * package: update "extend" to v3
  * refactor to use proxy agent classes directly
  * upgrade to `agent-base` v2 API
  * use "stream-to-buffer"
  * use %o formatter for debug() calls
  * package: update "get-uri" to v1
  * package: update "mocha" to v2
  * travis: test node v0.8, v0.10, and v0.12
  * test: add initial test cases
  * test: add basic "https" module tests
  * README: use SVG for Travis-CI badge

0.2.0 / 2014-11-10
==================

  * index: add reference link for Chrome's "HTTPS" support
  * index: throw an error for unknown proxy types (#2, @michaelansel)
  * index: support HTTPS proxies (#2, @michaelansel)
  * package: allow any "debug" v2

0.1.2 / 2014-04-04
==================

  * package: update outdated dependencies

0.1.1 / 2014-02-03
==================

  * index: move the exports before the `require()` calls
  * index: minor code cleanup
  * index: better proxy string splitting logic

0.1.0 / 2014-01-25
==================

  * index: calculate an SHA1 hash of the JS code
  * index: pass the `sandbox` option in to PacResolver
  * index: remove final remnants of the `code` property
  * index: set the `filename` option when creating the resolver function
  * package: update to "pac-resolver" v1.1.0

0.0.2 / 2014-01-25
==================

  * package: be lax on the `proxy-agent` version
  * index: remove incomplete support for the `code` property

0.0.1 / 2014-01-12
==================

  * gitignore: ignore development test files
  * index: set `port` to null when it is the protocol default port (80 / 443)
  * index: better support for passing in an "options object"
  * index: add more debug() calls, store the `cache` reference
  * index: use `proxy-agent` for "PROXY" and "SOCKS"
  * add README.md file
  * initial code
