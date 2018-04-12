# \<playground\>



## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve --open` to serve your application locally.

## Viewing Your Application

```
$ polymer serve --open
```

## Building Your Application

```
$ polymer build 
```
To have an es5 build compatible with most/all browsers:
```
 polymer build --preset es5-bundled 

```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
