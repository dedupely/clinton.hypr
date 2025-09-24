# 🧹 Hyprland Minimalist Config

This is a minimalist configuration for Hyprland, a dynamic Wayland compositor. It's designed to be clean, simple, and fast, stripping away all unnecessary fluff while providing a powerful and efficient workflow. This config is **keyboard-driven** and is perfect for users who value speed and efficiency over visual effects.

---

## ⌨️ Shortcuts

This configuration is built for speed, relying on keyboard shortcuts instead of the mouse. The main modifier key is the **Super** key (usually the Windows key ⌘).

| Shortcut | Action | Description |
| :--- | :--- | :--- |
| **Super** + **R** | Open Program Launcher | Launches Wofi, a program finder to quickly start any application. |
| **Super** + **C** | Close Active Window | Kills the currently focused window. |
| **Super** + **H/J/K/L** | Move Focus | Shifts focus to the window on the left, down, up, or right. |
| **Super** + **S** | Take Screenshot | Takes a screenshot of a selected region and saves it to the clipboard. |
| **Super** + **V** | Start/Stop Screencast | Starts or stops a screen recording session using a custom script. |
| **Super** + **Alt** + **H/J/K/L** | Resize Window | Resizes the active window by a small increment. |
| **Super** + **Ctrl** + **H/J/K/L** | Move Window | Moves the active window left, down, up, or right across the screen or monitors. |

---

## 🧘 Minimalist Philosophy

This configuration is an exercise in minimalism. The core philosophy is to remove anything that doesn't directly contribute to a functional and efficient workflow. If something doesn't serve a purpose, it's removed. This approach results in a workspace that's clutter-free and incredibly responsive.

This minimalist philosophy extends to everything:
* **No gaps or rounding** on windows, maximizing screen real estate.
* **No shadows or blur effects** on windows or backgrounds, reducing visual noise.
* **No animations**, ensuring instant window changes for a snappier feel. 

---

## ✨ What It Has (and Doesn't)

This config is defined by what it **lacks**. The absence of certain features is a deliberate choice for speed and simplicity.

### ✅ What it **has**:

* **Custom keybinds:** Essential shortcuts for a keyboard-driven workflow.
* **Simple layout:** Uses the **dwindle** layout, which automatically manages window placement without manual fuss.
* **Multi-monitor support:** Pre-configured for a triple-monitor setup, including one rotated screen.

### ❌ What it **doesn't have**:

* **Shadows, blur, and rounding:** These are disabled to save resources and make the UI feel faster. Why? Because they're purely aesthetic and can slightly slow down the rendering of your desktop.
* **Animations:** All window animations are turned off. This makes transitions feel immediate and responsive, which is great for muscle memory.
* **Gaps:** There are no gaps between windows or at the edges of the screen. This is a personal preference that ensures every pixel is used for content. Why? Because gaps are mostly aesthetic and can waste screen space.
* **Touchpad gestures:** These are turned off to prevent accidental workspace switching and to encourage a keyboard-centric workflow.
