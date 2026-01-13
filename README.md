# Branch Visualizer v1.0
This is a branch visualizer application using HTML, CSS, and JS
https://d3js.org/

#v1.0
-CRUD Nodes

# Running This Repository with `live-server`

This project can be run locally using **live-server**, a simple development server with live reload capability. This is useful for static sites or frontend-focused repositories.

---

## Prerequisites

Make sure you have the following installed:

* **Node.js** (LTS recommended)
* **npm** (comes with Node.js)

Verify installation:

```bash
node -v
npm -v
```

---

## Option 1: Run with `npx` (Recommended)

This option does **not** require global installation.

```bash
npx live-server
```

By default, this will:

* Serve the current directory
* Open the app in your default browser
* Watch for file changes and auto-reload

---

## Option 2: Install `live-server` Globally

If you plan to use `live-server` frequently:

```bash
npm install -g live-server
```

Then run:

```bash
live-server
```

---

## Running from a Specific Folder

If your entry files (e.g. `index.html`) are inside a subfolder:

```bash
live-server ./public
```

---

## Custom Port

To specify a custom port:

```bash
live-server --port=3000
```

---

## Disable Auto Browser Open

```bash
live-server --no-browser
```

---

## Using npm Scripts (Optional)

You can add a script to `package.json` for convenience:

```json
{
  "scripts": {
    "dev": "live-server"
  }
}
```

Then run:

```bash
npm run dev
```

---

## Common Issues

### Port Already in Use

Use a different port:

```bash
live-server --port=8081
```

### Changes Not Reloading

* Ensure files are inside the served directory
* Avoid editing files outside the project root

### Permission Errors (Linux / macOS)

If installing globally fails:

```bash
sudo npm install -g live-server
```

Or use the `npx` method instead.

---

## Notes

* `live-server` is intended for **development only**
* Not suitable for backend APIs or production use
* For frameworks (React, Vue, etc.), prefer their official dev servers

---

## License

Use this project according to its license.

