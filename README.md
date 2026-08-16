# io3

**English** | [简体中文](README.zh-CN.md)

A modern theme family for [Zed](https://zed.dev) — light and dark variants with a subtle frosted-glass background and readability-first syntax colors.

## Preview

**io3 Dark**

![io3 Dark](screenshots/dark.png)

**io3 Light**

![io3 Light](screenshots/light.png)

## Variants

- **io3 Light / io3 Dark** — the modern light/dark pair
- **io3 Glow** — a neon variant: the full io3 palette boosted to luminous, fluorescent colors on a near-black tube, evoking the glow of CRT text without going monochrome

## Features

- **Light & dark** — `io3 Light` and `io3 Dark`, following your system appearance
- **Frosted glass** — a nearly-opaque window with system blur: solid black/white overall, just a hint of transparency
- **Readability-first palette** — dark variant tuned from Tokyo Night, light variant from One Light; saturated types, dimmed italic parameters, and a dedicated color for Rust macros so they stand apart from functions
- **Complete coverage** — syntax, UI chrome, Git status colors, diagnostics, terminal ANSI 16 colors, and multiplayer cursors
- **Opaque popovers** — hover docs, completions, and menus stay readable

## Install

1. Copy `themes/io3.json` into Zed's themes directory:
   - Windows: `%USERPROFILE%\AppData\Roaming\Zed\themes\`
   - macOS / Linux: `~/.config/zed/themes/`
2. Restart Zed, then open the theme selector (`Ctrl+K Ctrl+T` / `Cmd+K Cmd+T`) and pick **io3 Dark** or **io3 Light**
3. Optionally merge `settings.example.json` into your `settings.json` for recommended fonts (JetBrains Mono + Inter) and automatic light/dark switching

## Recommended Fonts

Free, with ligatures: **JetBrains Mono** (code), **Inter** (UI). CJK-friendly alternative: Maple Mono.
