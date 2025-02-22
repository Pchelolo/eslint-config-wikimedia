0.12.0 / 2019-05-06
===================
* Provide ability to lint JSON files (James D. Forrester)
* Update eslint from 5.14.x to 5.16.x (James D. Forrester)

0.11.0 / 2019-02-20
===================
* build: Switch to renamed wikimedia/eslint-plugin-no-jquery (Ed Sanders)

* jquery: Enable `allowScroll` option of `no-jquery/no-animate` (Ed Sanders)

* Update eslint: 5.9.0 -> to 5.14.0
* Use new globals syntax (Ed Sanders)

0.10.1 / 2019-02-01
===================

* jquery: New rule `jquery/no-global-eval` (Ed Sanders)
* jquery: New rule `jquery/no-hold-ready`, `jquery/no-is-numeric` & `jquery/no-now` rules (Ed Sanders)

* Add "es6" env to presets for ES2015 and later (Ed Sanders)
* Document how to use Node with later versions of ES (Ed Sanders)

* build: Update wikimedia/eslint-plugin-jquery to wmf.6 (Ed Sanders)

0.10.0 / 2019-01-07
===================

* jquery: New rule `jquery/no-animate`, `no-animate-toggle` (Ed Sanders)
* jquery: New rule `jquery/no-fade`, `jquery/no-slide` (Ed Sanders)
* jquery: New rule `jquery/no-global-selector` (Ed Sanders)
* jquery: New rule `jquery/no-is-array`, `jquery/no-size` (Ed Sanders)
* jquery: New rule `jquery/no-parse-html-literal` (Ed Sanders)
* jquery: New rule `no-event-shorthand`, `no-noop` and `no-type` (Ed Sanders)

* Changed rule `quote-props` - Reverse ES3-keyword restriction (Timo Tijhof)

* build: Update wikimedia/eslint-plugin-jquery to wmf.5 (James D. Forrester)

0.9.0 / 2018-11-19
==================

* Implement `wikimedia/client` coding style (James D. Forrester)
* Implement `wikimedia/server` coding style (James D. Forrester)
* Implement `wikimedia/jquery` coding style (Ed Sanders)

* New rule: `max-statements-per-line` (Ed Sanders)
* New rule: `no-misleading-character-class` (Ed Sanders)

* Changed rule: `valid-jsdoc` – Add various preferred tags (Timo Tijhof)

* Update eslint: 5.6.0 -> 5.9.0
* Update elint-plugin-qunit: 3.3.0 -> 4.0.0
* Update assert-diff 1.2.0 -> 2.0.3
* Library sub-profile dependencies are now full dependencies instead of peerDependencies. (James D. Forrester)
* Refactor code to split into multiple profiles (James D. Forrester)
* test: Fix ESLint directive regex (Stephen Niedzielski)

0.8.1 / 2018-09-10
==================

* qunit: extend wikimedia.json (not .eslintrc.json) (Timo Tijhof)

0.8.0 / 2018-09-08
==================

* Changed rule: `quotes` – Add the 'avoidEscape' option. (James D. Forrester)
* qunit: Add the appropriate `env` setting. (James D. Forrester)

0.7.2 / 2018-08-14
==================

* Add qunit.json to "files" (Ed Sanders)

0.7.1 / 2018-08-13
==================

* No-op release bump for npmjs.com. (James D. Forrester)

0.7.0 / 2018-08-13
==================

* Implement `wikimedia/qunit` coding style (Timo Tijhof)

* New rule: `qunit/require-expect` (James D. Forrester)

* Changed rule: `valid-jsdoc` — Set preferred cases for types (Stephen Niedzielski)

* Removed rule: `no-catch-shadow` – Deprecated in eslint v5.1.0 (Stephen Niedzielski)
* Removed rule: `no-native-reassign` – Already inherited as `no-global-assign` (Stephen Niedzielski)
* Removed rule: `no-negated-in-lhs` – Already inherited as `no-unsafe-negation` (Stephen Niedzielski)

* package.json: Correct 'bugs' key (James D. Forrester)
* build: Use relative offsets in expected "invalid-results" file (Timo Tijhof)

0.6.0 / 2018-07-05
==================

* Update ESLint to version 4 (Timo Tijhof)
* Update ESLint to version 5 (James D. Forrester)

* New rule: `arrow-steps` (James D. Forrester)
* New rule: `max-len` (Joaquin Hernandez)
* New rule: `no-prototype-builtins` (James D. Forrester)
* New rule: `semi-style` (James D. Forrester)
* New rule: `switch-colon-spacing` (James D. Forrester)

* build: Add package-lock.json, expand testing to node 8, 10 (James D. Forrester)

0.5.0 / 2017-08-15
==================

* Remove explicitly defined `ecmaVersion` (Ed Sanders)

* Changed rule: `dot-notation` - Remove redundant allowKeywords override (Ed Sanders)
* Changed rule: `valid-jsdoc` - Validate use of `@return` (Timo Tijhof)

* test: Add tests for negative rules (Timo Tijhof)

0.4.0 / 2017-05-03
==================

* We now explicitly define the `ecmaVersion` as 5 (James D. Forrester)
* We removed a number of rules duplicated from `eslint:recommended` (Ed Sanders)

* New rule: `no-alert` (Ed Sanders)
* New rule: `no-catch-shadow` (Ed Sanders)
* New rule: `no-extend-native` (Ed Sanders)
* New rule: `no-extra-bind` (Ed Sanders)
* New rule: `no-extra-label` (Ed Sanders)
* New rule: `no-floating-decimal` (Ed Sanders)
* New rule: `no-implicit-globals` (Ed Sanders)
* New rule: `no-label-var` (Ed Sanders)
* New rule: `no-multi-str` (Ed Sanders)
* New rule: `no-native-reassign` (Ed Sanders)
* New rule: `no-negated-in-lhs` (Ed Sanders)
* New rule: `no-new-require` (Ed Sanders)
* New rule: `no-new-wrappers` (Ed Sanders)
* New rule: `no-octal-escape` (Ed Sanders)
* New rule: `no-proto` (Ed Sanders)
* New rule: `no-return-assign` (Ed Sanders)
* New rule: `no-self-compare` (Ed Sanders)
* New rule: `no-sequences` (Ed Sanders)
* New rule: `no-shadow-restricted-names` (Ed Sanders)
* New rule: `no-throw-literal` (Ed Sanders)
* New rule: `no-undef-init` (Ed Sanders)
* New rule: `no-unmodified-loop-condition` (Ed Sanders)
* New rule: `no-unused-expressions` (Ed Sanders)
* New rule: `no-useless-call` (Ed Sanders)
* New rule: `no-useless-computed-key` (Ed Sanders)
* New rule: `no-useless-concat` (Ed Sanders)
* New rule: `no-void` (Ed Sanders)
* New rule: `prefer-numeric-literals` (Ed Sanders)
* New rule: `unicode-bom` (Ed Sanders)

* Changed rule: `space-before-function-paren` — Also require spaces before parentheses in anonymous functions (Ed Sanders)

* Replaced rule: `no-spaced-func` with `func-call-spacing`, the new value upstream (Ed Sanders)

0.3.0 / 2016-11-15
==================

* We now extend `eslint:recommended` except for `no-constant-condition` (Ed Sanders)

* New rule: `computed-property-spacing` set to `always` (Ed Sanders)
* New rule: `no-array-constructor` (Ed Sanders)
* New rule: `no-new-object` (Ed Sanders)
* New rule: `no-script-url` (Ed Sanders)
* New rule: `no-unneeded-ternary` including for default assigment (Ed Sanders)
* New rule: `no-whitespace-before-property` (Ed Sanders)
* New rule: `object-curly-spacing` set to `always` (Ed Sanders)

* Changed rule: `no-multiple-empty-lines` — Also reject empty lines at the start or end of a file (Ed Sanders)

* test: Update sample.js to cover recently added rules (Timo Tijhof)

0.2.0 / 2016-10-27
==================

* New rule: `block-spacing` (Timo Tijhof)
* New rule: `new-cap` (Timo Tijhof)
* New rule: `new-parens` (James D. Forrester)
* New rule: `no-console` (Ed Sanders)
* New rule: `no-debugger` (Ed Sanders)
* New rule: `no-eval` (Ed Sanders)
* New rule: `no-extra-semi` (Timo Tijhof)
* New rule: `no-implied-eval` (Ed Sanders)
* New rule: `no-loop-func` (Ed Sanders)
* New rule: `no-multi-spaces` (Timo Tijhof)
* New rule: `no-new-func` (Ed Sanders)
* New rule: `no-sparse-arrays` (Ed Sanders)
* New rule: `vars-on-top` (Ed Sanders)

* Changed rule: `camelcase` — Make stricter by applying to properties (Ed Sanders)
* Changed rule: `space-in-parens` — Reject `foo( )` and not `foo()` (James D. Forrester)
* Changed rule: `spaced-comment` — Allow `/**` and `/*!` comment blocks (James D. Forrester)
* Changed rule: `space-unary-ops` — Make stricter by applying to "words" (Timo Tijhof)

* cleanup: Alphabetize rules in eslintrc (Timo Tijhof)
* test: Add comments to sample.js indicating which rules are tested (Timo Tijhof)
* README: Update Travis badge to @wikimedia (Timo Tijhof)
* Repo transferred from @markelog to @wikimedia.

0.1.0 / 2016-07-21
==================

* Initial release (markelog)
