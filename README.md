https://udesc-larva.github.io/sKanner3D/
====================

[sKanner3D](https://udesc-larva.github.io/sKanner3D/)'s project pages using [Bootstrap](http://getbootstrap.com/), [Jekyll](http://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/). Thus it is necessary to have installed [Ruby](https://www.ruby-lang.org/en/), [Node.js](http://nodejs.org/) and [Bundler](http://bundler.io/).

To run pages locally run following code:

```bash
git clone git@github.com:/UDESC-LARVA/sKanner3D.git
cd sKanner3D
bundle install
jekyll server --watch
```

Then open following link in your browser: http://localhost:4000

When you update the page, then you should run following commands:

```bash
cd sKanner3D
bundle update
jekyll server --watch
```

When you want to have live preview of your changes, then you have to run guard command in another terminal:

```bash
guard
```

