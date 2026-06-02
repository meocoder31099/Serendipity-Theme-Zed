![Midnight](https://raw.githubusercontent.com/Serendipity-Theme/assets/main/githubHeader.png)

# Serendipity for Zed.

the color palette is designed to be easy on the eyes, with enough contrast to make individual elements distinguishable but not so bright as to be jarring in a darkened coding environment.

# Install via Zed Extensions

1. Open the **Command Palette** with <kbd>⌘</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (macOS) or <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (Windows, Linux)
2. Open the **Extensions** view with the `zed: extensions` command
3. Search for `Serendipity Themes`
4. Click on **Install**.
5. Open the **Command Palette** again
6. Open the **Theme selector** with the `theme selector: toggle` command
7. Search for `Serendipity` and choose an `Serendipity` variant.

## Available Options

- **Serendipity Morning** (light)
- **Serendipity Sunset** (dark)
- **Serendipity Midnight** (dark)
- **Serendipity Midnight Electric** (dark)

### Morning

![Morning Preview](https://github.com/meocoder31099/Serendipity-Theme-Zed/blob/main/assets/previews/morning.png?raw=true)

### Sunset

![Sunset Preview](https://github.com/meocoder31099/Serendipity-Theme-Zed/blob/main/assets/previews/sunset.png?raw=true)


### Midnight

![Midnight Preview](https://github.com/meocoder31099/Serendipity-Theme-Zed/blob/main/assets/previews/midnight.png?raw=true)

### Midnight Electric

![Midnight Preview](https://github.com/meocoder31099/Serendipity-Theme-Zed/blob/main/assets/previews/midnight-electric.png?raw=true)



Starting from version `v1.1.0`, all **No Italics** theme variants have been removed. All themes now use italics for certain language tokens by default. To **disable** italics for all themes, add this snippet to your `settings.json`:

1. Open the **Command Palette** with <kbd>⌘</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (macOS) or <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (Windows, Linux).
2. Open your `settings.json` by running the `zed: open settings file` command.
3. Add this snippet to your `settings.json`:

```json
"theme_overrides": {
  "Serendipity Morning": {
    "syntax": {
      "attribute": { "font_style": "normal" },
      "comment": { "font_style": "normal" },
      "comment.doc": { "font_style": "normal" },
      "emphasis": { "font_style": "normal" },
      "function": { "font_style": "normal" },
      "function.method": { "font_style": "normal" },
      "link_text": { "font_style": "normal" },
      "property": { "font_style": "normal" },
      "variable": { "font_style": "normal" },
      "variable.special": { "font_style": "normal" },
      "variable.parameter": { "font_style": "normal" },
    },
  },
  "Serendipity Sunset": {
    "syntax": {
      "attribute": { "font_style": "normal" },
      "comment": { "font_style": "normal" },
      "comment.doc": { "font_style": "normal" },
      "emphasis": { "font_style": "normal" },
      "function": { "font_style": "normal" },
      "function.method": { "font_style": "normal" },
      "link_text": { "font_style": "normal" },
      "property": { "font_style": "normal" },
      "variable": { "font_style": "normal" },
      "variable.special": { "font_style": "normal" },
      "variable.parameter": { "font_style": "normal" },
    },
  },
  "Serendipity Midnight": {
    "syntax": {
      "attribute": { "font_style": "normal" },
      "comment": { "font_style": "normal" },
      "comment.doc": { "font_style": "normal" },
      "emphasis": { "font_style": "normal" },
      "function": { "font_style": "normal" },
      "function.method": { "font_style": "normal" },
      "link_text": { "font_style": "normal" },
      "property": { "font_style": "normal" },
      "variable": { "font_style": "normal" },
      "variable.special": { "font_style": "normal" },
      "variable.parameter": { "font_style": "normal" },
    },
  },
  "Serendipity Midnight Electric": {
    "syntax": {
      "attribute": { "font_style": "normal" },
      "comment": { "font_style": "normal" },
      "comment.doc": { "font_style": "normal" },
      "emphasis": { "font_style": "normal" },
      "function": { "font_style": "normal" },
      "function.method": { "font_style": "normal" },
      "link_text": { "font_style": "normal" },
      "property": { "font_style": "normal" },
      "variable": { "font_style": "normal" },
      "variable.special": { "font_style": "normal" },
      "variable.parameter": { "font_style": "normal" },
    },
  },
}
```

Serendipity Theme created by [Micheal Andreuzza](https://github.com/michael-andreuzza).
[Twitter](https://twitter.com/Mike_Andreuzza)
