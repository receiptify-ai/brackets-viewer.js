# brackets-viewer.js
A simple library to display tournament brackets (pools, single elimination, double elimination)

## How to use?

Import the library using [jsDelivr](https://www.jsdelivr.com/):

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Drarig29/brackets-viewer.js/dist/brackets-viewer.min.css" />
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/Drarig29/brackets-viewer.js/dist/brackets-viewer.min.js"></script>
```

Or using [npm](https://www.npmjs.com/package/brackets-viewer):

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/brackets-viewer/dist/brackets-viewer.min.css" />
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/brackets-viewer/dist/brackets-viewer.min.js"></script>
```

Now, you can use it with data generated using [brackets-manager](https://www.npmjs.com/package/brackets-manager) just like in the `/demo` folder.

To quickly test, you can use `json-server`:
- Run the npm script named `db` to serve the static database file `/demo/db.json`
    ```bash
    npm run db
    ```

- Use directly the `db.json` file generated by unit tests in the `brackets-manager` project
    ```bash
    npx json-server --watch path/to/brackets-manager/db.json
    ```

## How to build?

Install all npm dependencies:

```bash
npm install
```

Build with webpack:

```bash
npm run build
```
