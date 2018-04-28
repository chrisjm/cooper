# [Cooper Jekyll Theme](https://chrisjm.github.io/cooper/)

[![LICENSE](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/chrisjm/cooper/master/LICENSE.txt)
[![Jekyll](https://img.shields.io/badge/jekyll-%3E%3D%203.6-blue.svg)](https://jekyllrb.com/)
[![Ruby gem](https://img.shields.io/gem/v/cooper-jekyll-theme.svg)](https://rubygems.org/gems/cooper-jekyll-theme)

Cooper is a flexible, minimally opinionated two-column Jekyll theme. It works well for a personal, professional, marketing,  blog, or portfolio site on GitHub, Netlify, or self-hosting on your own server. Styling and choice of components is kept to a minimum so that you may craft or "cooper" your own site.

:sparkles: See what's new in the [CHANGELOG](CHANGELOG.md).

[![Cooper live preview][2]][1]

[1]: https://chrisjm.github.io/cooper/
[2]: screenshot.png (live preview)

![layout examples](screenshot-layouts.png)

## Notable Features

- Bundled as a "theme gem" for modern Jekyll compatibility.
- Compatible with GitHub Pages.
- Compatible with Netlify
- Support for Jekyll's built-in Sass/SCSS preprocessor.
- Built for simple layout.
- Optimized for search engines with support for [Twitter Cards](https://dev.twitter.com/cards/overview) and [Open Graph](http://ogp.me/) data.
- Optional [header images](https://chrisjm.github.io/cooper/docs/layouts/#headers), [custom sidebars](https://chrisjm.github.io/cooper/docs/layouts/#sidebars), [table of contents](https://chrisjm.github.io/cooper/docs/helpers/#table-of-contents), [galleries](https://chrisjm.github.io/cooper/docs/helpers/#gallery), related posts, [breadcrumb links](https://chrisjm.github.io/cooper/docs/configuration/#breadcrumb-navigation-beta), [navigation lists](https://chrisjm.github.io/cooper/docs/helpers/#navigation-list), and more.
- No comment system by design.
- [Google Analytics](https://www.google.com/analytics/) support.

## Demo Pages

| Name                                        | Description                                           |
| ------------------------------------------- | ----------------------------------------------------- |
| [Post with Header Image][header-image-post] | A post with a large header image. |
| [HTML Tags and Formatting Post][html-tags-post] | A variety of common markup showing how the theme styles them. |
| [Syntax Highlighting Post][syntax-post] | Post displaying highlighted code. |
| [Post with a Gallery][gallery-post] | A post showing several images wrapped in `<figure>` elements. |
| [Sample Collection Page][sample-collection] | Single page from a collection. |
| [Categories Archive][categories-archive] | Posts grouped by category. |
| [Tags Archive][tags-archive] | Posts grouped by tag. |

Additional sample posts are available under [posts archive][year-archive] on the demo site. Source files for these (and the entire demo site) can be found in [`/docs`](docs).

[header-image-post]: https://chrisjm.github.io/cooper/layout-header-image-text-readability/
[gallery-post]: https://chrisjm.github.io/cooper/post%20formats/post-gallery/
[html-tags-post]: https://chrisjm.github.io/cooper/markup/markup-html-tags-and-formatting/
[syntax-post]: https://chrisjm.github.io/cooper/markup-syntax-highlighting/
[sample-collection]: https://chrisjm.github.io/cooper/recipes/chocolate-chip-cookies/
[categories-archive]: https://chrisjm.github.io/cooper/categories/
[tags-archive]: https://chrisjm.github.io/cooper/tags/
[year-archive]: https://chrisjm.github.io/cooper/year-archive/

## Installation

There are three ways to install the theme:

* Ruby gem (for self-hosted sites)
* Ruby gem + jekyll-remote-theme plugin (GitHub Pages hosted sites)
* Forking/directly copying all of the theme files into your project

### Ruby Gem Method

1. Install the theme as a Ruby Gem by adding it to your `Gemfile` like so:

   ```ruby
   gem "cooper-jekyll-theme"
   ```

2. Fetch and update bundled gems by running the following [Bundler](http://bundler.io/) command:

   ```bash
   bundle
   ```

3. Set the `theme` in your project's Jekyll `_config.yml` file:

   ```yaml
   theme: cooper-jekyll-theme
   ```

To update the theme run `bundle update`.

### GitHub Pages Method

1. Create/replace the contents of your `Gemfile` with the following:

   ```ruby
   source "https://rubygems.org"

   gem "github-pages", group: :jekyll_plugins
   ```

2. Fetch and update bundled gems by running the following [Bundler](http://bundler.io/) command:

   ```bash
   bundle
   ```

3. Add `remote_theme: "chrisjm/cooper"` to your `_config.yml` file. Remove any other `theme:` or `remote_theme:` entry.

## Usage

For detailed instructions on how to configure, customize, add/migrate content, and more read the [theme's documentation](https://chrisjm.github.io/cooper/docs/quick-start-guide/).

---

## Contributing

Having trouble working with the theme? Found a typo in the documentation? Interested in adding a feature or [fixing a bug](https://github.com/chrisjm/cooper/issues)? Then by all means [submit an issue](https://github.com/chrisjm/cooper/issues/new) or [pull request](https://help.github.com/articles/using-pull-requests/). If this is your first pull request, it may be helpful to read up on the [GitHub Flow](https://guides.github.com/introduction/flow/) first.

Cooper has been designed as a base for you to customize and fit your site's unique needs. Please keep this in mind when requesting features and/or submitting pull requests.

### Pull Requests

When submitting a pull request:

1. Clone the repo.
2. Create a branch off of `master` and give it a meaningful name (e.g. `feature/awesome-feature` or `bug/fix-broken-thing`).
3. Open a pull request on GitHub and describe the feature or fix.

Theme documentation and demo pages can be found in the [`/docs`](docs) if submitting improvements, typo corrections, etc.

## Development

To set up your environment to develop this theme, run `bundle install`.

To test the theme, run `bundle exec rake preview` and open your browser at `http://localhost:4000/test/`. This starts a Jekyll server using content in the `test/` directory. As modifications are made to the theme and test site, it will regenerate and you should see the changes in the browser after a refresh.

---

## Credits

### Creator

**Chris J Mears**

- <https://chrisjmears.com>
- <https://twitter.com/chrisjm>
- <https://github.com/chrisjm>

### Icons + Demo Images:

- [The Noun Project](https://thenounproject.com) -- Garrett Knoll, Arthur Shlain, and [tracy tam](https://thenounproject.com/tracytam)
- [Font Awesome](http://fontawesome.io/)
- [Unsplash](https://unsplash.com/)

### Other:

- [Jekyll](http://jekyllrb.com/)
- [jQuery](http://jquery.com/)
- [Breakpoint](http://breakpoint-sass.com/)
- [FitVids.JS](http://fitvidsjs.com/)
- [GreedyNav.js](https://github.com/lukejacksonn/GreedyNav)
- [jQuery Smooth Scroll](https://github.com/kswedberg/jquery-smooth-scroll)
- [Lunr](http://lunrjs.com)

---

## License

The MIT License (MIT)

Copyright (c) 2013-2018 Chris J Mears and contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Cooper incorporates icons from [The Noun Project](https://thenounproject.com/)
creators Garrett Knoll, Arthur Shlain, and tracy tam.
Icons are distributed under Creative Commons Attribution 3.0 United States (CC BY 3.0 US).

Cooper incorporates [Font Awesome](http://fontawesome.io/),
Copyright (c) 2017 Dave Gandy.
Font Awesome is distributed under the terms of the [SIL OFL 1.1](http://scripts.sil.org/OFL)
and [MIT License](http://opensource.org/licenses/MIT).

Cooper incorporates photographs from [Unsplash](https://unsplash.com).

Cooper incorporates [Breakpoint](http://breakpoint-sass.com/).
Breakpoint is distributed under the terms of the [MIT/GPL Licenses](http://opensource.org/licenses/MIT).

Cooper incorporates [FitVids.js](https://github.com/davatron5000/FitVids.js/),
Copyright (c) 2013 Dave Rubert and Chris Coyier.
FitVids is distributed under the terms of the [WTFPL License](http://sam.zoy.org/wtfpl/).

Cooper incorporates [jQuery Smooth Scroll](https://github.com/kswedberg/jquery-smooth-scroll),
Copyright (c) 2017 Karl Swedberg.
jQuery Smooth Scroll is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Cooper incorporates [GreedyNav.js](https://github.com/lukejacksonn/GreedyNav),
Copyright (c) 2015 Luke Jackson.
GreedyNav.js is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Cooper incorporates [Jekyll Group-By-Array](https://github.com/mushishi78/jekyll-group-by-array),
Copyright (c) 2015 Max White <mushishi78@gmail.com>.
Jekyll Group-By-Array is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Cooper incorporates [@allejo's Pure Liquid Jekyll Table of Contents](https://allejo.io/blog/a-jekyll-toc-in-liquid-only/),
Copyright (c) 2017 Vladimir Jimenez.
Pure Liquid Jekyll Table of Contents is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).

Cooper incorporates [Lunr](http://lunrjs.com),
Copyright (c) 2017 Oliver Nightingale.
Lunr is distributed under the terms of the [MIT License](http://opensource.org/licenses/MIT).
