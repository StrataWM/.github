<p align=center>
    <img src="https://github.com/stratawm/.github/blob/profile/profile_banner.png"></img>
</p>

<p align="center">
  <img src="https://img.shields.io/github/languages/top/stratawm/stratawm?style=for-the-badge"/>
  <img src="https://img.shields.io/github/commit-activity/m/stratawm/stratawm?style=for-the-badge"/>
  <img src="https://img.shields.io/github/stars/stratawm/stratawm?style=for-the-badge"/>
</p>

## What's Strata?
Strata is a dynamic and sleek Wayland compositor and window manager for GNU/Linux systems. Its written completely in [Rust](https://rust-lang.org) using the [Smithay](https://github.com/smithay/smithay) library. The main feature of Strata is its modularity. You can mix'n'match different components to make Strata work the way you want. It is inspired by the [BSPWM](https://github.com/baskerville/bspwm) architecture. This is the basic outline of how Strata works:

```
╭───────────────╮       ╭───────────╮       ╭──────────╮
│ Hotkey Daemon │ ────> │ StrataCTL │ ────> │ StrataWM │
╰───────────────╯       ╰───────────╯       ╰──────────╯
```

This makes it possible so that you can interchange components, for example, instead of using [Kagi](https://github.com/stratawm/kagi), the official Strata hotkey daemon, you can use something like SWHKD or even make your own. As Strata grows in complexity, this architecture will, hopefully, prove to be useful.

