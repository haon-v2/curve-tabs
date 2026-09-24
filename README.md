# Curve Tabs — appearance mod

**Curve Tabs is an optional appearance package by Noah Helms ([@haon-v2](https://github.com/haon-v2)).** It is separate from the [Appearance Mod Loader for Search](https://github.com/haon-v2/search-appearance-mods).

**The browser is Search, created by [Drice Roland (@driceroland)](https://github.com/driceroland) / [Office Commun](https://officecommun.com) and its contributors. Full credit for the browser belongs to them.** This mod and its loader are community additions, not an official Search release or endorsement.

## What this package contains

One JSON appearance manifest: `curve-tabs.json`. It selects the host’s generic top/right edge rail with an 80-point corner radius, 210-point tabs, and 12-point spacing. Colors follow Search’s light/dark palette. The mod contains no browser executable, scripts, or network permissions.

## Install

1. Install the separate [Appearance Mod Loader preview](https://github.com/haon-v2/search-appearance-mods/releases). It ships with no mods installed. Unmodified official Search cannot load this package yet.
2. Download `curve-tabs.json` from this repository’s release.
3. In **Search Mod Preview**, open **Settings → Appearance → Import Mod…**.
4. Select the JSON file, then click **Enable** beside Curve Tabs.

Scroll over the rail to reach additional tabs, drag to reorder, and click × to close. Use ⌘T for a new tab and ⌘L for the address field. Disable or remove this mod in the same Settings page; loaded pages remain open.

## Compatibility and scope

Requires appearance API 1 with the `edgeRail` capability. Version 0.1.0 of the loader supports it. This is not a WebExtension, Zen Mod, or replacement browser. The renderer’s current limitations are documented in the loader’s API guide.

The package is MIT licensed; see [LICENSE](LICENSE). Search’s code and license remain with its upstream project and the separate loader fork. Installing this optional mod gives no ownership of Search’s name or branding.
