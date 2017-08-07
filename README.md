# Material Design Slim for AngularJS Apps

[Material Design](https://www.google.com/design/spec/material-design/) is a specification for a
unified system of visual, motion, and interaction design that adapts across different devices. Our
goal is to deliver a lean, lightweight set of AngularJS-native UI elements that implement the
material design specification for use in AngularJS single-page applications (SPAs).

[Material Design Components for Web](https://material.io/components/web/) is building out generalized
implementations of each of the components, and as we wrap these for AngularJS in 
[AngularJS-MDC](https://github.com/fintechstudios/angularjs-mdc), those implementations should supersede the
angular-material implementations in both performance and browser consistency. MDC is still in pre-release, 
though, and as of yet not everything is implemented. Thus, we offer this as a stripped-down version of
Angular Materialto cover the components that are yet to be implemented in MDC.

## Installing

```bash
npm install github:fintechstudios/material-slim#1.1.4
```

Once you have all the necessary assets installed, add `ngMaterial` as a dependency for your app:

```javascript
angular.module('myApp', ['ngMaterial']);
```


## Building

Developers can easily build AngularJS Material using NPM and gulp.

* [Builds - Under the Hood](docs/guides/BUILD.md)

First install or update your local project's **npm** tools:

```bash
# First install all the NPM tools:
npm install

# Or update
npm update
```

Then run the **gulp** tasks:

```bash
# To build `angular-material.js/.css` and `Theme` files in the `/dist` directory
gulp build

# To build the AngularJS Material Docs and Demos in `/dist/docs` directory
gulp docs
```

For more details on how the build process works and additional commands (available for testing and
debugging) developers should read the [Build Instructions](docs/guides/BUILD.md).

