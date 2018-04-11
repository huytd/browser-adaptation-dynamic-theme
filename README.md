# Dynamic theme

## Introduction

This is a prototype for a Firefox theme, however using a UX-oriented mindset; this project was oriented to reflection, therefore it's beyond code — ah such a resting and calm place to be. This experiment also offers a Firefox theme currently published at https://addons.mozilla.org/en-US/firefox/addon/semantic-dynamic-theme. The idea is to consider how a browser can/should blend with the actual content that the user is visiting, and to specially consider the dichotomy between external and internal browser pages.

When publishing this work, I have noticed myself using the Mozilla add-on site as a place for UX discussions. For example, I have decided to add screenshots however each screenshot aimed to discuss cases. At the same time noticed how add-ons sites could be improved around these discussions perhaps. If you want to jump to a reflection about the Add-ons site see bellow.

## What it does

This dynamic theme adapts to web sites and apps or fixed bars.

## What it shows

How to use the dynamic theme API.

## Related

* https://hacks.mozilla.org/2017/12/using-the-new-theming-api-in-firefox/
* Properties for theme https://developer.mozilla.org/en-US/Add-ons/WebExtensions/manifest.json/theme

## Add-on listing

*

## Heuristics

* When navbar — If the site has navbar, adapts to navbar and removes the bottom border of the theme;
* When bgcolor – If the site has background color, adapts to background color
* When chrome — Page background and removes bottom border

### Calculations

* Graphics analysis looks at a section cut, vertical line, first 10 pixels
* Text color calculation heuristics
* Favicon analysis

## Discussions around use cases

### Browser blends with tab content's navbar

![](https://raw.githubusercontent.com/taboca/themematcher/master/images/30_blend_navbar_2.png)

### Browser blends with tab content's navbar

![](https://raw.githubusercontent.com/taboca/themematcher/master/images/20_blend_navbar.png)

### Browser blends with its own content (about:)

![](https://raw.githubusercontent.com/taboca/themematcher/master/images/10_blend_about.png)

## Analysis of Add-ons as a distribution channel

Since this is an experiment, yet functional within the guides of Mozilla Add-ons framework, I had also the chance to reflect about the actual channel of distribution, the Mozilla Add-ons web site.

When working in publishing the Add-on, again, as an experiment, I noticed my mindset: a publisher, or author, aiming to connect with potential early adopters, aiming to connect with developers, aiming to connect with UX experienced professionals; willing to expand the realm of UX discussions around the work. As an example, I have decided to add screenshots as means to discuss specific cases — screenshots of the user visiting the browser internal pages versus screenshots of an user visiting external sites; screenshots of the user visiting a site where the content shows a navbar, and more.

When working with a view oriented to the UX discussion, however, I have allowed myself to stumble into the analysis of reviewing, or less naively, reflecting about the role of the Add-ons site itself.

My first naive thought was — oh, after about 10 years without visiting Add-ons, I confess surprised it's sort of the same thing.

But a less naive reflection is more like a subtle proposition — could Add-ons become a place for scaling extensions and ideas? what UI elements and social network key indicators could help to better match tests, usage, feedback, discussions around the development for next generation features?

A lot of developers, specially within the Mozilla realm, really understand that Add-on space have always served the purpose of evolving Firefox — however in a chaotic way — which Mozilla always benefited even if one or other developer-user had no idea how they have participated in the chain.  

I wonder if it would be possible to better integrate Add-ons, APIs, tests and the community to improve how new UX insights could be evaluated and evolve.
