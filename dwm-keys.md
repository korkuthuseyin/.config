# dwm Default Keybindings

**Mod Key:**  
- Default is `Alt` (Mod1Mask)  
- Can be changed to `Super` (Mod4Mask) in `config.h`

---

## Application Launch
| Shortcut | Action |
|----------|--------|
| Mod+Shift+Enter | Spawn terminal (default: st) |
| Mod+p           | Launch dmenu |

---

## Layout Control
| Shortcut | Action |
|----------|--------|
| Mod+b | Toggle status bar visibility |
| Mod+t | Set tiling layout |
| Mod+f | Set floating layout |
| Mod+m | Set monocle layout |

---

## Window Focus
| Shortcut | Action |
|----------|--------|
| Mod+j | Focus next window |
| Mod+k | Focus previous window |

---

## Master Area
| Shortcut | Action |
|----------|--------|
| Mod+h | Shrink master area |
| Mod+l | Grow master area |
| Mod+Enter | Swap focused window with master |
| Mod+i | Increase number of master clients |
| Mod+d | Decrease number of master clients |

---

## Window Management
| Shortcut | Action |
|----------|--------|
| Mod+Shift+c | Kill focused client |

---

## Tag (Workspace) Navigation
| Shortcut | Action |
|----------|--------|
| Mod+[1-9] | View tag N |
| Mod+Ctrl+[1-9] | Toggle view tag N |
| Mod+Shift+[1-9] | Move focused window to tag N |
| Mod+Ctrl+Shift+[1-9] | Toggle focused window on tag N |

---

## Monitor (Multi-Display)
| Shortcut | Action |
|----------|--------|
| Mod+, | Focus previous monitor |
| Mod+. | Focus next monitor |
| Mod+Shift+, | Send focused window to previous monitor |
| Mod+Shift+. | Send focused window to next monitor |

---

## Quit / Restart
| Shortcut | Action |
|----------|--------|
| Mod+Shift+q | Quit dwm |

---

### Notes
- These are the vanilla **dwm** defaults from `config.def.h`.
- Custom patches or changes to `config.h` may alter these bindings.
- You can change the Mod key and commands by editing `config.h` and recompiling.
