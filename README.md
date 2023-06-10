[Original Blog](https://huangxuan.me)
================================

[User Manual 👉](_doc/Manual.md)
--------------------------------------------------

Update Gems etc.

```sh
$ bundle install 
```

Serve the website (`localhost:4000` by default):

```sh
$ bundle exec jekyll serve
```

Make a post

```sh
$ rake post title="Hello 2015" subtitle="Hello World, Hello Blog"
```

Critical Jekyll-related code are located in `_include/` and `_layouts/`. Most of them are [Liquid](https://github.com/Shopify/liquid/wiki) templates.

This theme uses the default code syntax highlighter of jekyll, [Rouge](http://rouge.jneen.net/), which is compatible with Pygments theme so just pick any pygments theme css (e.g. from [here](http://jwarby.github.io/jekyll-pygments-themes/languages/javascript.html) and replace the content of `highlight.less`.

License
-------

Apache License 2.0.
Copyright (c) 2015-present Huxpro

Hux Blog is derived from [Clean Blog Jekyll Theme (MIT License)](https://github.com/BlackrockDigital/startbootstrap-clean-blog-jekyll/)
Copyright (c) 2013-2016 Blackrock Digital LLC.
