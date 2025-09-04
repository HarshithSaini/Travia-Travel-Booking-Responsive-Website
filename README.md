# Travia-Travel-Booking-Responsive-Website

## Travel Responsive Project

A simple responsive travel website with multiple pages (`home.html`, `tours.html`, `destinations.html`, `about.html`, `contact.html`).

### Quick start

- Option 1 — open directly:
  - Double‑click `home.html` to open in your browser.

- Option 2 — VS Code Run button (recommended):
  - Open this folder in VS Code.
  - Press F5 or use Run and Debug → "Run Travel Site".
  - This starts a static server on port 5501 and opens `http://localhost:5501/home.html`.

- Option 3 — manual local server (Node.js):
  - Install Node.js LTS.
  - From the project folder, run:

```bash
npx --yes http-server . -p 5501 -c-1
```

Then visit `http://localhost:5501/home.html`.

### Project structure

- `home.html` is the default entry page
- `tourism.css` contains the styles
- `script1.js` contains site scripts
- `images/` contains all assets used across pages

### Troubleshooting

- Address already in use (EADDRINUSE):
  - Another process is using the port. Either close it or start on a different port, for example:

```bash
npx --yes http-server . -p 5510 -c-1
```

Update `.vscode/launch.json` `url` and `.vscode/tasks.json` `command` if you want the VS Code Run button to use the new port.

- Task hasn’t exited / problemMatcher warning in VS Code:
  - The task is configured as a background server. Choose "Remember my choice" → "Debug Anyway" once, or keep the provided problemMatcher. The Run configuration will wait until the server is ready.

### Editing

- Update HTML files to change content and sections
- Update `tourism.css` for layout, colors, and responsive rules
- Update `script1.js` for interactivity

### License

Personal/educational use. Replace with your preferred license if publishing.


