---
title: Firefox 137 for developers
slug: Mozilla/Firefox/Releases/137
page-type: firefox-release-notes
---

{{FirefoxSidebar}}

This article provides information about the changes in Firefox 137 that affect developers. Firefox 137 is the current [Nightly version of Firefox](https://www.mozilla.org/en-US/firefox/channel/desktop/#nightly) and ships on [April 1, 2025](https://whattrainisitnow.com/release/?version=137).

## Changes for web developers

### Developer Tools

### HTML

#### Removals

### CSS

#### Removals

### JavaScript

- The {{jsxref("Math.sumPrecise()")}} static method is now supported. This takes an [iterable](/en-US/docs/Web/JavaScript/Reference/Iteration_protocols#the_iterable_protocol) (such as an {{jsxref("Array")}}) of numbers and returns their sum. It is more precise than summing the numbers in a loop because it avoids floating point precision loss in intermediate results. ([Firefox bug 1943120](https://bugzil.la/1943120)).

#### Removals

### SVG

- The {{svgelement("discard")}} SVG element is now supported, along with its corresponding {{domxref("SVGDiscardElement")}} JavaScript interface.
  The element allows developers to specify a trigger time or event at which a specified element and its children should be removed from the DOM.
  An SVG viewer can use this information to conserve memory by discarding elements that are no longer needed, such as animated elements that have completed.
  ([Firefox bug 1945330](https://bugzil.la/1945330)).

#### Removals

### HTTP

#### Removals

### Security

#### Removals

### APIs

#### DOM

#### Media, WebRTC, and Web Audio

#### Removals

### WebAssembly

#### Removals

### WebDriver conformance (WebDriver BiDi, Marionette)

#### General

#### WebDriver BiDi

#### Marionette

## Changes for add-on developers

- Adds {{WebExtAPIRef("commands.openShortcutSettings")}} that opens the Manage Extension Shortcuts page of Manage Your Extensions (`about:addons`) and, if the extension has shortcuts, scrolls to and highlights the extension's shortcut key options. ([Firefox bug 1538451](https://bugzil.la/1538451))
- The 10 MB quota for data stored by the {{WebExtAPIRef("storage.session")}} API is now enforced. ([Firefox bug 1915688](https://bugzil.la/1915688))

### Removals

### Other

## Experimental web features

These features are newly shipped in Firefox 137 but are disabled by default. To experiment with them, search for the appropriate preference on the `about:config` page and set it to `true`. You can find more such features on the [Experimental features](/en-US/docs/Mozilla/Firefox/Experimental_features) page.

## Older versions

{{Firefox_for_developers}}
