## WHERE AM I?
###### A Geography Guessing Game


### Set up instructions

You will need a [google api key](https://console.developers.google.com/apis) to access google maps. If you have never done this before [instructions](https://developers.google.com/maps/documentation/javascript/get-api-key) can be found here.

I added both `localhost` and `127.0.0.1` to the credentials page to test locally, The terminal says that site should be reachable at localhost, but I was running on node v6.2.0, vs v4 which is target of `polymer-cli`.

---

## Polymer CLI

#### Install the Polymer-CLI

[Polymer-CLI NPM](https://www.npmjs.com/package/polymer-cli)

#### Viewing Your Application

```
$ polymer serve
```

#### Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

#### Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
