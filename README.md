# Free UK Gen Project Template

This is a starting point for any projects that want to make use of the Free UK Gen Core Frontend resources.

It uses Bower to get the core repo and some other bits, Grunt to compile it all plus any local resources and then Jekyll to serve all that with the example index.html file.

A more thorough explanation of this will follow at some point but in essence you can copy the files in this repo into your project and just run:

```shell
$ npm install
$ bower install
$ grunt
$ jekyll serve
```

Then to apply an upgrade from the core, just run:

```shell
$ bower update
$ grunt
$ jekyll serve
```
