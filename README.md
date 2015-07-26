# GitHub Dark [![tags](https://img.shields.io/github/tag/StylishThemes/GitHub-Dark.svg?style=flat)](https://github.com/StylishThemes/GitHub-Dark/tags) [![star this repo](http://github-svg-buttons.herokuapp.com/star.svg?user=StylishThemes&repo=GitHub-Dark&style=flat&background=1081C1)](http://github.com/StylishThemes/GitHub-Dark) [![fork this repo](http://github-svg-buttons.herokuapp.com/fork.svg?user=StylishThemes&repo=GitHub-Dark&style=flat&background=1081C1)](http://github.com/StylishThemes/GitHub-Dark/fork)

- Install from [userstyles.org](http://userstyles.org/styles/37035) (with customization options) or [manually](https://raw.githubusercontent.com/StylishThemes/GitHub-Dark/master/github-dark.css).
- Stylish is available for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/2108/), [Chrome](https://chrome.google.com/extensions/detail/fjnbnpbmkenffdnngjfgmeleoegfcffe), [Opera](https://addons.opera.com/en/extensions/details/stylish/), [Safari](http://sobolev.us/stylish/) and [Firefox Mobile](https://addons.mozilla.org/en-US/firefox/addon/2108/).
- Includes styling for [Octotree](https://github.com/buunguyen/octotree/#octotree) &amp; [ZenHub](https://www.zenhub.io/).
- Use the [grunt build process](https://github.com/StylishThemes/GitHub-Dark/wiki/Build) to customize your GitHub Dark theme.
- Please refer to the [installation documentation](https://github.com/StylishThemes/GitHub-Dark/wiki/Install) for more details.

## Preview
![GitHub Dark preview](http://i.imgur.com/9ChgiR6.png)

## [Available Syntax Highlighting Themes](http://stylishthemes.github.io/GitHub-Dark/)

|   |   |   |   |   |
| --- | --- | --- | --- | --- |
| Ambiance | Chaos | Clouds Midnight | Cobalt | Idle Fingers* |
| Kr Theme | Merbivore | Merbivore Soft | Mono Industrial | Mono Industrial Clear |
| Monokai* | Pastel on Dark* | Solarized Dark* | Terminal | Tomorrow Night* |
| Tomorrow Night Blue* | Tomorrow Night Bright* | Tomorrow Night Eigthies* | Twilight* | Vibrant Ink |

\* Supports [Jupyter notebook syntax highlighting](https://github.com/sujitpal/statlearning-notebooks/blob/master/src/chapter2.ipynb)

## Notes

* If you're using a custom domain for GitHub Enterprise, be sure to include it though a `@-moz-document` rule (Firefox) or add it to the `Applies to` section in (Chrome).

## Contributions

If you would like to contribute to this repository, please...

1. Fork
2. Make changes (please read the [contribution guidelines](https://github.com/StylishThemes/GitHub-Dark/blob/master/CONTRIBUTING.md) and abide by them)
3. Create a pull request!

Thanks to all that have [contributed](https://github.com/StylishThemes/GitHub-Dark/graphs/contributors) so far!

## Recent Changes

See the [full change log](https://github.com/StylishThemes/GitHub-Dark/wiki).

#### Version 1.14.6 (7/26/2015)

* Notifications: correct closed issue icon color. Fixes [issue #245](https://github.com/StylishThemes/GitHub-Dark/issues/245).

#### Version 1.14.5 (7/25/2015)

* Graphs:
  * Brighten highlight on contribution graph. Fixes [issue #241](https://github.com/StylishThemes/GitHub-Dark/issues/241).
  * Fix tooltip.
* Pull request:
  * Style new status icons.
  * Fix grey status icons.
  * Fix new checks form.
  * Change sidebar tooltip z-index. See [pull #244](https://github.com/StylishThemes/GitHub-Dark/pull/244) thanks to [40n](https://github.com/40n)!
* Gist
  * Add description & meta link styles. Fixes [issue #243](https://github.com/StylishThemes/GitHub-Dark/issues/243).
  * Fix secret button & gist descriptions.
  * Fix secret label.
  * Fix secret button disabled state.
* ZenHub: add style for new toggle buttons.
* Diff:
  * Color tweaks (darker)
  * More color tweaks, make all line selections yellow.
* Global: Fix misaligned counters in boxes.
* GeoJSON map styling (darken). Fixes [issue #242](https://github.com/StylishThemes/GitHub-Dark/issues/242).
* Maintenance: remove all empty lines.

#### Version 1.14.4 (7/20/2015)

* Themes: Fix an issue with backgrounds in notebook renders.
* Pull requests:
 * Fix merge form on Windows.
 * Fix border on pull request checks.

#### Version 1.14.3 (7/15/2015)

* Global search: word result highlight for code & users. Fixes [issue #238](https://github.com/StylishThemes/GitHub-Dark/issues/238).
* Build
  * Add font parameter & fix tabs in custom builds.
  * Disable cleancss advanced optimization for themes. Fixes [issue #240](https://github.com/StylishThemes/GitHub-Dark/issues/240).
  * Disable cleancss advanced optimization for userstyle minified file (not currently being used).
* Update "Industrial Mono Clear" theme on userstyles.
