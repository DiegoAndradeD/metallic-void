# Metallic Void

> 🚧 **Work In Progress**: This theme is continually evolving based on personal workflows and aesthetic preferences.

**Metallic Void** is a high-end, dark, and minimalist VS Code theme.

It is designed with a "matte" philosophy: avoiding neon/saturated colors in favor of oxidized metals (rust, brass, copper) and cold alloys (steel, titanium). The UI is strictly flat, removing 3D shadows to mimic the tiling window manager aesthetic (Hyprland/Sway).

## The Aesthetic

- **Deep Matte Background:** `#0f0f0f` (Not absolute black, to prevent OLED smearing).
- **Flat UI:** No drop shadows. Borders are used for separation.
- **Semantic Richness:** Context-aware coloring for variables vs. parameters vs. constants.

## Color Palette

| Color | Hex | Role | Semantic Meaning |
| :---: | :--- | :--- | :--- |
| ![#0f0f0f](https://placehold.co/15x15/0f0f0f/0f0f0f.png) | `#0f0f0f` | **Background** | The Void. Used in editor, sidebar, and terminal. |
| ![#a64952](https://placehold.co/15x15/a64952/a64952.png) | `#a64952` | **Keywords** | **Control Flow**. Imports, returns, and conditionals. |
| ![#bf616a](https://placehold.co/15x15/bf616a/bf616a.png) | `#bf616a` | **Cursor / Focus** | **The Laser**. Active elements and deletions. |
| ![#889fa1](https://placehold.co/15x15/889fa1/889fa1.png) | `#889fa1` | **Variables** | **Mutable Data**. Local variables (`let`, `var`). |
| ![#b48ead](https://placehold.co/15x15/b48ead/b48ead.png) | `#b48ead` | **Properties / Const** | **Fixed Data**. Object keys, attributes, and constants. |
| ![#d08770](https://placehold.co/15x15/d08770/d08770.png) | `#d08770` | **Parameters** | **Input**. Arguments passed into functions. |
| ![#d8dee9](https://placehold.co/15x15/d8dee9/d8dee9.png) | `#d8dee9` | **Functions** | **Action**. Methods and function calls. |
| ![#c9b385](https://placehold.co/15x15/c9b385/c9b385.png) | `#c9b385` | **Classes** | **Structure**. Class definitions and component names. |
| ![#a3be8c](https://placehold.co/15x15/a3be8c/a3be8c.png) | `#a3be8c` | **Interfaces** | **Contracts**. TypeScript interfaces and types. |
| ![#88bcbb](https://placehold.co/15x15/88bcbb/88bcbb.png) | `#88bcbb` | **Git Added** | **New**. Added lines and files. |

## Installation (Manual)

Since this theme is not yet on the Marketplace, you can install it manually:

1. Clone this repository or download the folder.
2. Copy the `metallic-void` folder to your VS Code extensions directory:
   - **Linux/Mac:** `~/.vscode/extensions/`
   - **Windows:** `%USERPROFILE%\.vscode\extensions\`
3. Restart VS Code.
4. Open the Command Palette (`Ctrl+Shift+P`), type **"Preferences: Color Theme"**, and select **Metallic Void**.

## Features

### 1. Semantic Highlighting
The theme understands code context.
- **Parameters** are Orange (`#d08770`) to distinguish them from local variables (Cyan).
- **Constants** are Lavender (`#b48ead`) to indicate immutability.
- **Object Properties** are Lavender (`#b48ead`) to create a visual hierarchy in data structures (`item.id`).

### 2. Flat UI
- Shadows are removed (`#00000000`) for a strictly 2D look.
- Popups and widgets use borders instead of elevation.
- Split views use single-pixel lines.

### 3. Integrated Terminal
- The terminal uses a custom ANSI palette that perfectly matches the editor colors.
- `ls`, `git log`, and CLI tools will look consistent with your code.

## Contributing

Feedback is welcome! If you find a language token that looks "off" or unreadable, feel free to open an Issue.

## License

[MIT](LICENSE)
