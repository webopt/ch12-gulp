# gulp Boilerplate!

This is some gulp boilerplate for you, with an example website ready for you to use. This repo is referred to in Chapter 12 of the book [Web Performance in Action](https://manning.com/books/web-performance-in-action?a_aid=webopt&a_bid=63c31090). To really understand everything this repo does, you should read that chapter. Chances are though, that if you're looking at this, you've read the book. So thank you for that. :)

To start, you need Node and `npm`. Clone and get this repo going like so:

```
git clone https://github.com/webopt/ch12-gulp.git
cd ch12-gulp
npm install
```

Source files are stored and edited in the `src` folder. When the `gulp build` command is run, all files are processed and built into the `dist` folder. After you do this, you can spin up a little local webserver by running the `http.js` file like so:

```
node http.js
```

When this runs, a local web server should be up and running at [http://localhost:8080](http://localhost:8080) for you to peruse.

Have fun! You're free to use the gulp boilerplate as you like, except for the site files in `src`. They're just there for illustrative purposes. Empty out that folder and put your own stuff in there if you're going to use this for anything.

- Jeremy Wagner
- Website: https://jeremywagner.me
- Twitter: [@malchata](https://twitter.com/malchata)
- Facebook: https://facebook.com/webperf