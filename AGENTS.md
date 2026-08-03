# AGENTS.md

## Cursor Cloud specific instructions

This repository is a single static HTML page (`index.html`) with no build system,
package manager, dependencies, tests, or lint configuration.

- There is nothing to install; the update script is a no-op runtime check.
- To run/develop the site, serve the repo root with any static file server, e.g.
  `python3 -m http.server 8000` (Python 3 is preinstalled), then open
  `http://localhost:8000/`. Node 22 is also available if you prefer a Node server.
- There are no lint, test, or build commands. Editing `index.html` and reloading the
  browser is the full development loop.
