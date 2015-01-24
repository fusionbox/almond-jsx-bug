# Example for https://github.com/jrburke/almond/issues/101

Steps:

1. Build the file.

    $ node r.js -o build.json

2. Open it in the browser.

    $ google-chrome index.html

If successful, it should print AB on the screen.
If unsuccessful, "Uncaught TypeError: undefined is not a function" will appear
in the console.
