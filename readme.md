# Jekyll + ZURB Template + Gulpfile

This is a Jekyllized version of the [official ZURB Template](https://github.com/zurb/foundation-zurb-template) for use with [Foundation for Sites](http://foundation.zurb.com/sites). Zurb's [Panini](https://github.com/zurb/panini) and [Style Sherpa](https://github.com/zurb/style-sherpa/) have been removed and [Jekyll](http://jekyllrb.com/) has been added. Everything else has remained pretty much the same.

## Origins

This is a slight modification of:
` git clone https://github.com/huphtur/jekyll-foundation-zurb-template projectname `

## Installation

```
cd projectname
npm install
bower install
```

Run `npm start` to run Gulp. Your finished site will be created in a folder called `docs`, viewable at ` http://localhost:8000 `

To create compressed, production-ready assets, run `npm run build`.

## Deployment

The `docs` directory can be copied/sync'ed/pushed to whatever hosting solution,
perhaps the easiest method would be to treat it as its own repo and publish on gh-pages.

