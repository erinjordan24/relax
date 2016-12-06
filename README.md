# Relax: UPDATED by Shane Demskie

Relax is a Free (as in speech and beer) clone of [Noisli](http://noisli.com).

To use it, you have several options:

* Go to [the associated Github page](https://github.com/demsks/relax) for this project.
* put these files and static resources somewhere on a web server. It can be local or remote.

Browse the single ``index.html`` page using a modern browser.

## Features

* A markdown text-editor with syntax highlighting, preview, and a minimalistic styling toolbar,
* The text is autosaved every 500ms and stored in the localStorage container,
* You have many sounds available if you want to build a cool ambiance while you're writing (fireplace, wind in the leaves, seashore...),
* Store and load files using the localStorage database UPDATE***: Fixed functionality and organization of save file feature, 
* Download the markdown file to your disk using the download icon.,
* UPDATE***: you can now edit the individual volume of each sound to set the perfect ambiance of your work environment. got rid of the icons for sounds cause they were hard to see,
* UPDATE***: you can now change the color of the background. Research has shown that certain colors can effect productivity differently. The backgroud of the editor also changes along with the background of the page,




### Missing features

(a.k.a. TODOs)
* UPDATE***: Need server to upload files from cp. Will require moving page away from github pages 

### Hacking on features

If you want to be able to produce the uglified/minified sources, you'll have to install the required dependencies like this:

```shell
npm install
```

The Makefile allows you to minify the js and the css files, using the following command:

```shell
make minify
```

Or you may chose to minify the JS or the CSS files:

```shell
make minify_js
make minify_css
```


## Note on privacy

The edited text in this interface is stored on your localStorage database.

You can check the source code, nothing is stored on the server. I will never **EVER** read your documents. It's all yours.

It also means this content is associated to the "domain name" you're on (whether it is github pages, your local static HTTP server, your own remote web server, etc) **AND** your web browser.

If you switch from a machine to another or if you swap from Firefox to Chrome or vice-versa, your content won't show up. And even if you're on the same machine/browser and use a different URL to access this interface, your localStorage database will be different. Use the "download" feature to safely copy your content from a machine to another and sync it your way if you intend to transfer it on another pair (URL / client).

## License

This project uses:

* [Editor.js, derived from this project](https://github.com/lepture/editor),
  by Hsiaoming Yang.
* [icomoon icons](http://icomoon.io/),
* [Glyphicons icons](http://glyphicons.com/),
* [Meteocons icons](http://www.alessioatzeni.com/meteocons/),
* The other font icons are made using the great
  [Fontello tool](http://fontello.com/), and come from Font Awesome, Entypo,
  Typicons, Maki, Elusive,
* [JQuery](http://jquery.com),
* [JPlayer](http://jplayer.org/),
* Fonts are [Ubuntu Mono](http://font.ubuntu.com/),
  [Lato](http://www.latofonts.com/lato-free-fonts/),
  [Roboto Slab](http://www.google.com/fonts/specimen/Roboto+Slab), provided by
  [Google Webfonts](https://www.google.com/fonts/)
* Responsive grid by the [.fitgrd project](http://www.fitgrd.com/)

## Sounds:

* [Rain in forest](http://www.freesound.org/people/inchadney/sounds/22132/) - by inchadney CC-BY,
* [rbh thunder storm](http://www.freesound.org/people/RHumphries/sounds/2523/) (storm with rain) - by RHumphries, CC-BY,
* [Storm](http://www.freesound.org/people/Erdie/sounds/23221/) by Erdie, CC-BY,
* [SummerEveningInMyGarden](http://www.freesound.org/people/acclivity/sounds/30832/), by acclivity - CC-BY-NC,
* [AMBIENT LOOP - Perfectly Clear - Wilderness Hillside - FILTERED](http://www.freesound.org/people/Arctura/sounds/39829/), by Arctura - CC-BY,
* [Vent - wind(1)](http://www.freesound.org/people/Glaneur%20de%20sons/sounds/104952/) by Glaneur de sons - CC-BY,
* [oceanwavescrushing.wav](http://www.freesound.org/people/Luftrum/sounds/48412/) by Luftrum - CC-BY,
* [fireplace](http://www.freesound.org/people/martats/sounds/138018/) by martats - CC-0,
* [131024_brook_black_forest.wav](http://www.freesound.org/people/reinsamba/sounds/204195/) by reinsamba - CC-BY,


Apart from that, the rest of the code (HTML/CSS/JS) is mine and is published
under the terms of the [WTFPL](http://www.wtfpl.net/).
