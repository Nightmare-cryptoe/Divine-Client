# Divine Client

A starter launcher shell for a legally obtained Eaglercraft 1.12-compatible client.

## Current state

The repository originally contained only an empty `index.html`; it did not contain an Eaglercraft engine, JavaScript bundle, WebAssembly module, assets, or build configuration. This commit adds a responsive launcher UI and local asset-selection flow, but it cannot include the game engine itself.

## Run locally

Open `index.html` in a browser or serve the repository with any static web server:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Next steps

Add a compatible client build and connect its documented startup API in `index.html`. Features should be tested in single-player or on servers where the owner explicitly permits client modifications. This project does not implement anti-cheat bypasses, packet manipulation, combat automation, or other unfair-advantage features.
