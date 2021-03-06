---
title: Technical Errata
---

# Boring Technical Details

### Site Architecture

This site, as well as all of my recent prototypes for the day job, are built using the [Hugo static site generator](https://gohugo.io). I like the [SASS/SCSS processing](https://github.com/perardi/portfolio/blob/main/assets/css/main.scss), [partials](https://github.com/perardi/portfolio/blob/main/assets/css/main.scss) (reusable elements), [template logic](https://github.com/perardi/portfolio/blob/main/layouts/_default/section.html)…but what I also appreciate: it’s just a binary. Like, there's just a hugo executable, and that’s it. No leaning tower of Node.js or Ruby. *(Jekyll, aptly named, because once some inscrutable bit of the Ruby stack breaks, it quickly becomes Mr. Hyde)*

This is currently hosted on GitHub pages, because I don’t want a really obvious URL right now, as one of these projects is not quite released. Though I also sure do love Netlify.

### CSS Trickery

I am using a [variable webfont](https://fonts.google.com/specimen/Archivo). I hope that becomes absolutely ubiquitous, quickly.

This site is my first experiment in using “fluid” typography, using the [clamp() function and viewport units](https://css-tricks.com/linearly-scale-font-size-with-css-clamp-based-on-the-viewport/). Something may break. It’ll definitely break on IE, but whatever.

CSS via SCSS, if only because I like [the color functions](https://github.com/perardi/portfolio/blob/main/assets/css/components/colors.scss). Also, [nested classes](https://github.com/perardi/portfolio/blob/main/assets/css/components/typography.scss). Oh, and [shards/components](https://github.com/perardi/portfolio/blob/main/assets/css/components/nav.scss). It’s all nice.