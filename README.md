# Marvel Colors App

A handy little Mac app that gives you quick access to the standard marvel design color palette.

> Thanks to the orignal Source [Material Colors App](https://github.com/romannurik/MaterialColorsApp)

<img src="https://d13yacurqjgara.cloudfront.net/users/6295/screenshots/2594885/colors_2x.png" width="300" alt="Screenshot">

**[Download the app](https://github.com/joelcoxokc/MarvelColorsApp/releases/download/v1.1.0/MaterialColors-1.1.0.zip)**

## Build instructions

If you want to customize the app for your own needs, you can do a custom build.

  1. First install [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/).
  2. Make sure an install electron globally, run: 
        
        $ npm install -g electron

  3. Clone the repository and in the root directory, run:

        $ npm install

  4. To run the app:

        $ npm start

Note that you'll probably want to disable the auto-updating mechanism by emptying out the `checkForUpdates` method in
[main.js](https://github.com/romannurik/MarvelColorsApp/blob/master/app/main.js).
