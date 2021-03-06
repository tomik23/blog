# jekyll-uno

Jekyll-Uno - a minimal, responsive theme for Jekyll based on the [Uno](https://github.com/daleanthony/Uno) theme for Ghost.

> :warning:
  This theme requires ruby and rubygems installed

### Features

* Clean layout
* Resposive layout
* Pagination
* Syntax highlighting
* Social links
* Tags listing page
* Categories listing page
* Google Analytics integration
* Disqus integration

---

### Install and Test

1. Download or clone repo
2. Enter the folder
3. Command line run `yarn`
4. Run development version `docker-compose up`
5. Build production `yarn prod`

Plugins for **css** optimization have also been used and instead of 70KB! css we have 23KB
- postcss-cli
- autoprefixer
- cssnano
- @fullhuman/postcss-purgecss

Access via: [http://localhost:4000/blog/](http://localhost:4000/blog/)

---

### UX Experience

For better user experience, the [zooom.js] library has been added [zooom.js](https://github.com/tomik23/zooom.js)
To the photo which we want to be enlarged should be added class `zooom`
Example of use:
`![Bitbucket screen](/blog/images/bugfix123-bug_remove_extra_padding.png "Bitbucket screen"){: class="zooom"}`

---

### Copyright and license

It is under [the MIT license](/LICENSE).