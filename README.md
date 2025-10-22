# Game Selector

This is a tiny static demo that shows a list of games read from `gamelist.json`.

How to run locally:

1. In the project root, start a simple static server. For example, with Python 3:

```bash
python3 -m http.server 8000
```

2. Open your browser to http://localhost:8000/index.html

Click "Play" on any card to open the game in a new window. If popups are blocked, allow popups for the page.

Files added:
- `gamelist.json`: sample games with embedded HTML content
- `index.html`: the main page that fetches the JSON and renders the UI
# Game-selector