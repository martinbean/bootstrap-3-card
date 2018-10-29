# Card component for Bootstrap 3

This package back-ports the _visual appearance_ of cards from Bootstrap 4, to
the Sass version of Bootstrap 3. It doesn’t include any of the Flexbox-based
columns functionality used in Bootstrap 4, to retain feature parity with
Bootstrap 3.

As this project was created to bring the visual appearance of Bootstrap 4 cards
to a Bootstrap 3 project, no amendments or additions are planned, so this
package is not actively maintained. You are welcome to fork this repository and
add any missing functionality, i.e. decks.

## Usage

This is meant to be used as a Sass component in your own Sass-based projects.
First you will need to import it using (preferably) [npm](https://www.npmjs.com/):

    $ npm install bootstrap-3-card --save-dev

There is also a [Bower](https://bower.io/) package registered if you still use
that package manager:

    $ bower install bootstrap-3-card

Import the core Bootstrap library (and any other of your own components), and
then include this component after:

```scss
// Bootstrap
@import "variables";
@import "node_modules/bootstrap-sass/assets/stylesheets/bootstrap";

// Your components

// This component
@import "node_modules/bootstrap-3-card/sass/card";
```

## License

Licensed under the [MIT License](LICENSE).
