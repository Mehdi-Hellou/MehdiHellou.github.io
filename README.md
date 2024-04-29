
# Introduction

This is my website created from the Prologue Theme with Jekyll. Go on this github for more information ().

# Line command to execute:

- Install ruby with the proper openssl version:

export RUBY_CONFIGURE_OPTS="--with-openssl-dir=$(brew --prefix openssl@1.1)"
rbenv install 3.0.6

- Manually install the openssl gem for your ruby:

rbenv local 3.0.6
gem install openssl -v '2.2.3' -- --with-openssl-dir=$(brew --prefix openssl@1.1)

- Then you can compile as usual with bundle by doing
bundle install
bundle exec jekyll serve

# Credits

[![Gem Version](https://badge.fury.io/rb/jekyll-theme-prologue.svg)](https://badge.fury.io/rb/jekyll-theme-prologue)

![Prologue Theme](assets/images/screenshot.png "Prologue Theme Screenshot")

This is Prologue, a simple, single page responsive site template from [HTML5 UP](https://html5up.net/prologue), now available as a blog-aware Jekyll theme from [Chris Bobbe](https://chrisbobbe.github.io). It features a clean, minimalistic design and a sticky sidebar with navigation-linked scrolling.

**Demo**: https://chrisbobbe.github.io/jekyll-theme-prologue/

Thanks to @andrewbanchich for his many Jekyll adaptations of HTML5 UP's elegant themes, which helped and inspired me, and of course many thanks to HTML5 UP.

Original README from HTML5 UP:

```
Prologue by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


This is Prologue, a simple, single page responsive site template. It features a
clean, minimalistic design and a sticky sidebar with navigation-linked scrolling.

Demo content images* are courtesy of the ridiculously talented Felicia Simion. Check out
more of her amazing work over at deviantART:

http://ineedchemicalx.deviantart.com/

(* = Not included! Only meant for use with my own on-site demo, so please do NOT download
and/or use any of Felicia's work without her explicit permission!)

Demo banner images* courtesy of Unsplash, a radtastic collection of CC0 (public domain)
images you can use for pretty much whatever.

(* = Not included)

AJ
aj@lkn.io | @ajlkn

PS: Not sure how to get that contact form working? Give formspree.io a try (it's awesome).


Credits:

	Demo Images:
		Felicia Simion (ineedchemicalx.deviantart.com)
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fortawesome.github.com/Font-Awesome)

	Other
		jQuery (jquery.com)
		html5shiv.js (@afarkas @jdalton @jon_neal @rem)
		CSS3 Pie (css3pie.com)
		background-size polyfill (github.com/louisremi)
		Respond.js (j.mp/respondjs)
		jquery.scrolly (@ajlkn)
		jquery.scrollzer (@ajlkn)
		Skel (skel.io)
```
