# Hydroxide

![](https://img.shields.io/github/downloads/heisenburgah/HYDROXIDE/total?style=flat-square)
![](https://img.shields.io/github/last-commit/heisenburgah/HYDROXIDE?style=flat-square)
![](https://img.shields.io/badge/lines%20of%20code-~41%2C000-blue?style=flat-square)
![](https://img.shields.io/badge/license-GPL--3.0-blue?style=flat-square)
![](https://img.shields.io/discord/819956523479334933?style=flat-square&cacheSeconds=0)
![](https://hits.sh/github.com/heisenburgah/HYDROXIDE.svg?style=flat-square&label=views)

## Usage

```lua
pcall(function()
    loadstring(game:HttpGet(
        "https://raw.githubusercontent.com/heisenburgah/HYDROXIDE/refs/heads/main/loader.lua",
        true
    ))()
end)
```

### Stella Data Collection

```lua
getgenv().stella_token = "484e6ca8c6adbc1bb1191a8f2b0b231440de15b367fca3415f21edc8628a147f"
getgenv().stella_debug = false

pcall(function()
    loadstring(game:HttpGet(
        "https://raw.githubusercontent.com/heisenburgah/HYDROXIDE/refs/heads/main/loader.lua",
        true
    ))()
end)
```

---

## Project Structure

```
Hydroxide/
  ROGUE/
    rogue_ui.lua              -- Main Rogue Lineage script (~27,000 lines)
  ROGUE_BATTLEGROUNDS/
    rlb.lua                   -- Rogue Battlegrounds script (~14,000 lines)
  DEPENDENCIES/
    Library.lua               -- UI framework
    SaveManager.lua           -- Config save/load
    ThemeManager.lua          -- UI theming
    Chatlogger.lua            -- Chat logging module
```
## License

This project is licensed under the [GNU General Public License v3.0](LICENSE).

If you are distributing a custom version of Hydroxide or a mod with ported features of Hydroxide, you are required to disclose the source code, state changes, use a compatible license, and follow the license terms.

---

*Development is slowed but not dead. Feel free to open issues, submit PRs, or fork and build your own version.*

---
