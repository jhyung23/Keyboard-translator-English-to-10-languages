# ============================================================
#                     MASTER TRANSLATOR
# ============================================================
# A high-performance, system-wide translation utility.

# --- 1. OVERVIEW ---
Master Translator is a productivity tool for Windows that allows
you to translate text as you type or learn foreign languages 
instantly by highlighting text.

# --- 2. KEY FEATURES ---

* TURBO LEARNING MODE: 
  Highlight text and press [Ctrl + Alt + E] for an instant 
  English translation in the bottom-left corner.

* TYPING TRANSLATION:
  - Line Mode: End a sentence with "..." to replace it.
  - Box Mode: End with ".." to translate the whole block.

* HOTKEY REMAPPER: 
  Change shortcuts via a GUI menu in the system tray.

* SMART FILTERS: 
  Prevents translating URLs, file paths, and code accidentally.

* PERSISTENCE: 
  Automatically saves your language, sound, and hotkey 
  preferences to 'settings.ini'.

# --- 3. INSTALLATION ---

1. Ensure Python 3.8+ is installed.
2. Open terminal in the project folder and run:
   pip install keyboard pyautogui pyperclip pystray pillow deep_translator
3. Run the script as ADMINISTRATOR:
   MasterTranslator.exe

# --- 4. DEFAULT HOTKEYS ---

- [Ctrl + Alt + T] : Enable / Disable App
- [Ctrl + Alt + E] : Learning Mode (Selected Text -> English)
- [Ctrl + Alt + 1] : Set Language to Korean
- [Ctrl + Alt + 2] : Set Language to Chinese (Simplified)
- [Ctrl + Alt + 3] : Set Language to Chinese (Traditional)
- [Ctrl + Alt + 4] : Set Language to Japanese
- [Ctrl + Alt + 5] : Set Language to French

# --- 5. TRAY ICON STATUS ---

- BLUE ICON : App is Active and Ready.
- GRAY ICON : App is Disabled.
- RED ICON  : Connection Error (Check Internet).

# --- 6. TROUBLESHOOTING ---

* APP NOT TYPING: Ensure you are running as Administrator.
* HOTKEY CONFLICT: If keys don't work, use the "Edit Hotkeys" 
  menu to choose a unique combination.
* CLIPBOARD: The app temporarily uses your clipboard; 
  avoid copying other items while a translation is processing.

# ============================================================
# Created by: jhyung
# ============================================================
