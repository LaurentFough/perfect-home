# Perfect Home
Replace your new-tab page and home page with your bookmarks.
No ads, no speed dials, no frequently visited or other "frecence" bullshit!
Just your own, predictable grid of links.

**Download from [mozilla addons page](https://addons.mozilla.org/en-US/firefox/addon/perfect-home/)**

**[![Screenshot](_stuff/screen-main.png)](https://addons.mozilla.org/en-US/firefox/addon/perfect-home/)**

## FEATURES
- [x] Drag & drop tiles to reorder
- [x] Command palette (filter flat list) (currently Cmd+P on mac - when focus is on page)
- [x] Use custom images for tiles (right-click on a tile -> custom thumbnail)
- [x] Style page with custom css - paste your css in settings
- [x] Requires only 1 permissions (bookmarks)!
- [x] Settings export/import
- [x] Docked Folders


## Usage
- Select a folder from your bookmarks
- Enjoy!


## Customization
See [a tutorial here](customization-tutorial.md)

## Build locally
1. `npm i`
2. To test the extension in a temporary firefox profile, use the test script:
    ```sh
    npm start
    ```
3. To build a zip artifact (that can be uploaded to mozilla addons):
    ```sh
    npm run ext-build
    ```

## Creating test-profile in Firefox
1. Open `about:profiles`
2. Create `test-profile`
3. Set your previous profile as "default" again
