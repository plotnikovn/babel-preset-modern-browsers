<a name="8.1.1"></a>
## [8.1.1](https://github.com/christophehurpeau/babel-preset-modern-browsers/compare/v8.1.0...v8.1.1) (2017-02-27)


### Bug Fixes

* missing dependencies ([f925a55](https://github.com/christophehurpeau/babel-preset-modern-browsers/commit/f925a55)), closes [#16](https://github.com/christophehurpeau/babel-preset-modern-browsers/issues/16)


<a name="8.1.0"></a>
# [8.1.0](https://github.com/christophehurpeau/babel-preset-modern-browsers/compare/v8.0.0...v8.1.0) (2017-02-25)


### Features

* add es2017 plugins and es2016, es2017 option ([ade31a8](https://github.com/christophehurpeau/babel-preset-modern-browsers/commit/ade31a8))


## 8.0

- Firefox 51 release   
Firefox 50 is no longer supported (removed `babel-plugin-transform-es2015-block-scoping`)
 
 
## 7.0

- remove object-rest (now supported in [babel 6.19](https://babeljs.io/blog/2016/11/16/6.19.0))
- add babel-plugin-transform-es2015-arrow-functions

## 6.0

- drop safari 9 support
- preset options

## 5.1

- added object-rest

## 5.0

- removed stage1, see #4 for discussion
- updated compatibility table

## 4.0

- uglify fixed issue https://github.com/mishoo/UglifyJS2/issues/1098L remove uglifyjs special preset
- add full-support preset: parameters, for...of and destructuring (see readme for details)
- Breaking: firefox 46 and edge 13 are no longer supported (upgrade to edge 14 and Firefox 47)

## 3.0

Webpack fixed https://github.com/webpack/webpack/issues/2522 and https://github.com/webpack/webpack/issues/2523
For preset `webpack2` and `webpack2-uglifyjs`, plugins `babel-plugin-transform-es2015-modules-commonjs` and `babel-plugin-transform-es2015-shorthand-properties` are removed.
Requires webpack `v2.1.0-beta.9`


## 2.0

Firefox 46 release
Firefox 45 is no longer supported
