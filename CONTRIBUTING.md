## Contribute
First off, thank you for considering contributing to Gravnd Zero theme! All contributions are welcome, be it a bug report or fix, feature request or implementation.

### Bug reports
Create an [issue](https://github.com/fistmenaruto/gravnd-zero/issues) with detailed information regarding the problem.

### Feature requests
Feature requests are more than welcome! Create an [issue](https://github.com/fistmenaruto/gravnd-zero/issues) or make a [pull request](https://github.com/fistmenaruto/gravnd-zero/pulls) to `develop` branch with detailed information/description of your request.

### Development
``` sh
$ cd ~/grav/user/themes
$ git clone https://github.com/fistmenaruto/gravnd-zero.git gravnd-zero
$ cd gravnd-zero
$ yarn
$ yarn dev / watch / production
```

#### Yarn scripts

``` sh
# Compile .scss, .js, .twig files and add sourcemaps.
$ yarn dev

# Same as dev but watches files for changes and runs Browsersync.
# Once files are saved, they are recompiled and Browsersyn refreshes the browsers.
$ yarn watch

# Prepares the files for production minifying them and removing sourcemaps.
$ yarn production
```