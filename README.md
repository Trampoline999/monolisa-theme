# Stellar Dust Theme

A beautiful, dark custom theme for Visual Studio Code featuring customized highlights and editor styling for a focused coding experience.

## Features

- **Three Variations**: Includes `Stellar Dust`, `Stellar Dust Modern`, and `Stellar Dust Deep Blue` to suit your preference.
- **Eye-friendly**: Deep, rich blue background designed to reduce eye strain.
- **Syntax Highlighting**: Custom semantic highlighting for better code readability and structure recognition.
- **Unique Palette**: A carefully selected color palette tailored for long coding sessions.

## Installation

1. Open the **Extensions** sidebar in VS Code (`Cmd+Shift+X` or `Ctrl+Shift+X`).
2. Search for **"Stellar Dust"**.
3. Click **Install**.
4. Navigate to **Preferences: Color Theme** (`Cmd+K Cmd+T` or `Ctrl+K Ctrl+T`).
5. Select **"Stellar Dust"**, **"Stellar Dust Modern"**, or **"Stellar Dust Deep Blue"** from the dropdown menu.

## How to Disable Italics

If you prefer not to have italicized text (such as parameter variables or comments), you can disable italics by adding the following configuration to your VS Code `settings.json`:

```json
"editor.tokenColorCustomizations": {
    "textMateRules": [
        {
            "scope": [
                "variable.parameter",
                "comment"
            ],
            "settings": {
                "fontStyle": ""
            }
        }
    ]
}
```

## Feedback

Found a bug or have a suggestion? Feel free to share your feedback!

## Enjoy!

Happy coding! 🚀
