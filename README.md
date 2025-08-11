# Fiora Editor

Fiora Editor is a modern-looking prototype video editor GUI built with Python's Tkinter library. This project provides a stylish, dark-themed interface for basic video editing operations, serving as a foundation for further development. **Note:** This version is a GUI prototype and does not perform real video processing yet.

## Features

- **Dark Theme:** Custom dark mode styling using `ttk.Style`.
- **Top Menu Bar:** File, Edit, and Help menus with common actions.
- **Left Toolbar:** Quick access to tools (Cut, Move, Add Text, Adjust) and Import/Export buttons, each with emoji icons.
- **Video Preview Area:** Central placeholder for video display.
- **Timeline:** Scrollable timeline with placeholder video clips.
- **Properties Panel:** Collapsible sections for Adjustments (brightness, contrast, etc.) and Color Mixer (RGB sliders).
- **Responsive Layout:** Uses `PanedWindow` and grid weights for flexible resizing.
- **Status Bar:** Displays current action or tool.
- **Keyboard Shortcuts:** Ctrl+Q to quit, Ctrl+S to save (placeholder).

## Getting Started

### Prerequisites
- Python 3.x
- Tkinter (usually included with Python)

### Running the App
1. Clone or download this repository.
2. Ensure `icon.ico` is present in the project directory.
3. Run the main script:
   ```bash
   python video_editor_gui.py
   ```

## Project Structure
- `video_editor_gui.py` — Main GUI application.
- `icon.ico` — Application icon.

## Limitations
- **No real video editing:** All tool actions are placeholders. Video import/export and editing features are not implemented yet.
- **Prototype only:** Intended as a UI/UX demonstration and starting point for a full editor.

## Screenshots
*(Add screenshots here if available)*

## License
This project is provided as-is for educational and prototyping purposes.
