Disclaimer, We no longer use this library internally and are focusing our efforts on open sourcing and maintaining projects that we do use and can meaningfully contribute to. Sorry for any frustrations with this project (we're happy to link to any fork that has an excited, commited maintainer).

pace
====

An automatic web page progress bar.

We also have a [Wordpress Plugin](https://wordpress.org/plugins/pace).

Pace will automatically monitor your Ajax requests, event loop lag, document ready state and elements on your page to decide on the progress.

If you use AMD or Browserify, require pace.js and call `pace.start()` as early in the loading process as is possible.

### Example
```html
<head>
  <script src="/pace/pace.js"></script>
  <link href="/pace/themes/pace-theme-barber-shop.css" rel="stylesheet" />
</head>
```
