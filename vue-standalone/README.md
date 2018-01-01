# Vue Standalone Static

This is a simple template that you can drag/drop onto your computer and immediately
use to practice [Vue.js](https://vuejs.org/) without installing anything at all. The purpose is to make it very simple.

**Offline-Access**: All files are purposely placed within these folders without using CDN's incase you want offline access to code.

## Instructions

Open the `public/index.html` file in your web browser. Alternatively, you can load it on your localhost if
you have it available such as: `localhost/git-repo/vue-standalone/public/`.

## Folder Structure

Although this is a static site, I still placed most items under the `public` folder, here is the structure:

```
public
  /css              <-- All of your custom CSS files, Skipped SASS to keep it simpler
  /img              <-- Image folder if/when needed.
  /js               <-- All of your custom JS files
  /vendor           <-- All third-party libs such as jQuery, Bootstrap, Vue, etc.
  index.html        <-- Main Index Page
  (anything.html)   <-- Copy the index.html and create new practice pages.
README.md           <-- The Help File :)
```

## Currently Using

- Font Awesome v5 _(minified)_
- jQuery Slim v3.1.1 _(minified)_
- Bootstrap 4 vAlpha 5 _(minified)_
  - Tether v1.4.3 _(minified)_
- Vue v2.5.13 _(minified)_


## Gallery

Under `public/img` there is a gallery of `six` photos to play with. There are thumbnails in the `thumbs` folder with the same name.

- All photos are **sized the same** and named accordingly:
  - `public/img/gallery/bridge.jpg` @ `1000 x 800`
  - `public/img/gallery/thumbs/bridge.jpg` @ `250 x 200`
  - _the public/img/gallery/CREDITS contain the authors of the royalty free photographs_

---

Open Source: Apache 2 License

(C) 2018 Jesse Boyer | <[JREAM](https://jream.com)>