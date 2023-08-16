<p align="center">
  <img alt="screenshot" src="https://github.com/GitSquared/horizon-edex-theme/raw/master/screenshots/main.png">
  <br><br>
</p>

## Horizon eDEX-UI Theme Fork

This fork provides three different types, for each theme (`horizon-disrupted` and `horizon-full`).
The three types are:
- `-no-shell-reverse`. This makes it so the shells are no longer reversed, and go from left to right, **instead of** right to left.
- `-no-memory-reverse`. This makes it so that the active memory slots are highlighted with green, and free slots highlighted with dark blue, **instead of** the other way around.
- `-no-reverse`. This has both of the above changes.

Horizon is a modern, sexy and colorful theme for [eDEX-UI](https://github.com/GitSquared/edex-ui).

To install it, download the `fonts` and `themes` folders of this repo and put them in your [eDEX config directory](https://github.com/GitSquared/edex-ui/wiki/userData).

Then, launch eDEX, use `Ctrl+Shift+S` (or `⌘+Shift+S`) to open the settings, select your chosen theme (`horizon-disputed` or its versions, or `horizon-full` or its versions) in the "theme" dropdown menu, hit "Save to Disk" and "Reload UI". Done!

The `-full` variant has no on-screen keyboard and a larger terminal. Screenshots below.

*Note: In this theme, the visual order of terminal tabs is reversed (unless using `-no-shell-reverse` or `-no-reverse` versions), and the memory monitor emphasizes free memory slots instead of used ones (unless using `-no-memory-reverse` or `-no-reverse` versions).*


<p align="center">
  <img alt="screenshot" src="https://github.com/GitSquared/horizon-edex-theme/raw/master/screenshots/bobfish.png">
  <br><br>
  <img alt="screenshot" src="https://github.com/GitSquared/horizon-edex-theme/raw/master/screenshots/htop.png">
  <br><br>



## `horizon-full.json`

 <p align="center">
  <img alt="screenshot" src="https://github.com/GitSquared/horizon-edex-theme/raw/master/screenshots/full.png">
  <br><br>
</p>


## Credits & License

The color scheme for this theme was blatantly stolen from the [Horizon VS Code theme](https://github.com/jolaleye/horizon-theme-vscode) by [@jolaleye](https://github.com/jolaleye). Go check it out!

The fonts redistributed with this theme have their own (permissive) licenses, specifically:
- the [Apache 2.0 license](https://github.com/GitSquared/horizon-edex-theme/blob/master/LICENSE-Roboto) for Roboto and Roboto Mono, and
- the [SIL Open Font License](https://github.com/GitSquared/horizon-edex-theme/blob/master/LICENSE-Gugi) for Gugi.

I do not own these fonts.
As for the theme itself, it is licensed under the [MIT License](https://github.com/GitSquared/horizon-edex-theme/blob/master/LICENSE).
