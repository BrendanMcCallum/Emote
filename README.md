Emote
=====

Emote is a simple GTK3-based Emoji Picker for linux.

Emote runs in the background and, when its keyboard shortcut (`Ctrl+Alt+E`) is presed, an emoji picker window is opened. The selected emoji is copied to the clipboard.

## Development

### Requirements

Install pipenv:

```bash
sudo pip3 install pipenv
```

Install dependencies:

```bash
pipenv install -d
```

### Running

Run the development version:

```bash
pipenv run start
```

### Packaging

Create a packaged `.snap` file:

```bash
snapcraft
```