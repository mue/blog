---
title: Version 5.3
date: 2021-08-21T10:56:00.000Z
draft: false
authors:
  - David Ralph
featured_image: 'https://res.cloudinary.com/mue/image/upload/blog/version-5-3.webp'
tags:
  - Update release
summary: Bug fixes and optimisations with a few small features to improve your Mue experience further
---

Here's an update that brings some new features to Mue and fixes.

## Changelog

### Added

* Stats tab allowing you to see things such as how many tabs you have opened, quotes favourited and more
* Create tab so you can easily make preset settings addons with photo packs and quote packs coming soon
* Navbar widget zoom

### Changes

* Mue now opens a new tab when installed
* When uninstalling Mue, an optional uninstall survey is opened in a new tab once it has been uninstalled
* Photo information no longer shows N/A, instead the field is hidden
* Optimisations

### Fixed

* Tooltip has correct fade out transition
* Favourite button now works properly when photo information icon is off
* Favourite button now works properly with marketplace photo packs
* Birthday greeting inconsistency has been fixed when default greeting message is off
* Massive fixes to modal responsiveness, including sidebar and marketplace issues
* Fixed text appearing behind modal during open transition
* Search now works correctly when pressing enter
* Widget order tab no longer glitches when moving items for the first time and a widget is hidden
* Tab name now changes along with the language if you haven't set a custom one
* Hot reload bugs fixed with quote and more
* About tab tooltips text no longer go outside of the tooltip
* Quicklinks zoom no longer affects the add quicklink button which has also been fixed with zoom
* Text shadow removed on add quicklink to be consistent with notes
* 12 hour clock has been fixed at midnight (thanks @garfieldbanks for reporting!)
