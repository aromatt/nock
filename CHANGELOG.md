3.1.1 / 2015-11-19
==================

  * [fix] delay now works with replyWithError. Fixes [#411](https://github.com/pgte/nock/issues/411)
  * generated change log
  * changelog script. fixes [#287](https://github.com/pgte/nock/issues/287)
  * added node v5 to be tested in travis
  * added node v0.10 to travis tests
  * reinstated recorder tests (related to [#404](https://github.com/pgte/nock/issues/404))
  * Merge branch 'ierceg-fix-issue-404'
  * Fix [#404](https://github.com/pgte/nock/issues/404) replace bad POST with GET requests

3.1.0 / 2015-11-17
==================

  * v3.1.0
  * taking out the tests that dont run in node v0.10
  * updated browserify bundle
  * fixed nock hanging on node v0.10. fixes [#402](https://github.com/pgte/nock/issues/402)
  * removed recorder from coverage tests
  * [fix] updated debug version (see [#403](https://github.com/pgte/nock/issues/403))
  * [fix] fixed recorder test because of failing domain.com url
  * removed recorder tests for now. (see [#404](https://github.com/pgte/nock/issues/404))
  * using latest superagent

3.0.0 / 2015-11-16
==================

  * browserify bundle update
  * query(true) matches no query string
  * Merge branch 'master' of github.com:pgte/nock

2.18.2 / 2015-11-13
===================

  * v2.18.2
  * browserify bundle
  * no presumption we have fs because of browserify. another attempt at trying to fix [#150](https://github.com/pgte/nock/issues/150)

2.18.1 / 2015-11-13
===================

  * v2.18.1
  * no presumption we have fs because of browserify. trying to fix [#150](https://github.com/pgte/nock/issues/150)
  * Merge pull request [#395](https://github.com/pgte/nock/issues/395) from ryanmurakami/master
    Adding example for debug environment variable
  * [doc] clarifying net connect behaviour, fixes [#401](https://github.com/pgte/nock/issues/401)
  * net connect examples

2.18.0 / 2015-11-11
===================

  * v2.18.0

2.18.0-alpha.2 / 2015-11-11
===========================

  * v2.18.0-alpha.2
  * more generic treatment for arrays
  * isomorphic fetch
  * examples for several types of delay and timeout

2.18.0-alpha.1 / 2015-11-09
===========================

  * v2.18.0-alpha.1
  * Merge pull request [#397](https://github.com/pgte/nock/issues/397) from pgte/browserify
    Browserify support - alpha
  * removing node v0.10 from travis tests
  * harmony flags on istanbul coverage tests
  * trying to make it work with browserify
  * Merge branch 'master' of github.com:pgte/nock
  * travis badge is just master status
  * added browserify test to collection of tests
  * browserify test dependencies
  * make nock work on browserify. fixes [#150](https://github.com/pgte/nock/issues/150)
  * browserify tests
  * Merge pull request [#396](https://github.com/pgte/nock/issues/396) from four43/patch-1
    Added localhost enableNetConnect to README
  * Added localhost enableNetConnect to README
    I'm just getting picky here but I didn't put together the `enableNetConnect` and localhost when I was testing my express server, after "CTRL+F" ing my way through the README I came across: https://github.com/pgte/nock/issues/239 
    Thanks
  * Adding example for debug environment variable

2.17.0 / 2015-10-29
===================

  * v2.17.0
  * Merge branch 'seegno-forks-enhancement/add-global-pending-mocks'
  * Add `pendingMocks()` to global scope

2.16.1 / 2015-10-29
===================

  * v2.16.1
  * Merge branch 'neophob-request-promise-testcase'
  * support for IPv6 addresses. fixes [#386](https://github.com/pgte/nock/issues/386)
  * Merge branch 'request-promise-testcase' of git://github.com/neophob/nock into neophob-request-promise-testcase
  * Merge branch 'neophob-use-strict-for-testcases'
  * Merge branch 'use-strict-for-testcases' of git://github.com/neophob/nock into neophob-use-strict-for-testcases
  * add request-promise to requred dev packages
  * add request-promise test case - does not work if ipv6 address gets enabled
  * Merge branch 'seegno-forks-bugfix/improve-is-done-code-coverage'
  * Merge branch 'bugfix/improve-is-done-code-coverage' of git://github.com/seegno-forks/nock into seegno-forks-bugfix/improve-is-done-code-coverage
  * Improve code coverage for `isDone` method

2.16.0 / 2015-10-28
===================

  * v2.16.0
  * Merge branch 'seegno-forks-enhancement/add-global-is-done'
  * Add `isDone()` to global scope
  * test files use strict consistent
  * add missing strict to testcase
  * ipv6 url in test
  * clarified allowUnmocked option
  * Merge pull request [#383](https://github.com/pgte/nock/issues/383) from izaakrogan/master
    addition to allow-unmocked section of README
  * addition to allow-unmocked section of readme

2.15.0 / 2015-10-10
===================

  * v2.15.0
  * added Matt Oakes as contributor
  * Merge branch 'matto1990-feature_after_record'
  * Allow filtering nock back recording before saving
    An `afterRecord` option can be passed in which will be called with the
    array of scopes as a paramter. The function can then filter these as
    it wishes an return the array of scopes that will be saved to the
    fixture.
    This fixes [#300](https://github.com/pgte/nock/issues/300).
  * removed change log
  * v2.14.0
  * Merge branch 'DavidTPate-reqheader-regex-function'
  * Add the ability (and positive + negative tests around the functionality) to specify a regular expression or function to check incoming request headers. Also add documentation around it and add myself to the contributors list.

2.13.0 / 2015-09-25
===================

  * v2.13.0
  * Merge branch 'jshcrowthe-master'
  * Remove throw error statement from test (copy paste error)
  * Test wording change
  * Add query param length check to prevent false positives
  * added @ruimarinho as contributor

2.12.0 / 2015-09-17
===================

  * v2.12.0
  * Merge branch 'seegno-forks-bugfix/auth-with-username-only'
  * Fix authentication using username only
    When using just an username for authentication, the password
    `undefined` would be used instead of `''`.
  * Use travis container infrastructure
  * Add support for node 4.0.0+

2.11.0 / 2015-09-14
===================

  * v2.11.0
  * removed node 4
  * added node 4.0
  * Merge branch 'pwmckenna-propagatedataevents'
  * propagate data events the same way we propagate readable events
  * Merge pull request [#363](https://github.com/pgte/nock/issues/363) from marneborn/doc/replyStatus
    doc fix - several .reply calls are made without a status, so there is no body.
  * Merge branch 'PsiXdev-master'
  * fix recording body of form-data
  * In README.md, several .reply calls were missing status so body wasn't returned
  * Merge branch 'ZephyrHealth-chai'
