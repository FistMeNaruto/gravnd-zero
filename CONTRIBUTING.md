## Contribute
Contributions are welcome from everyone.

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
$ yarn run dev / watch / production
```

### Yarn scripts

`yarn run dev` Compiles the .scss, .js and .twig files and adds sourcemaps.
`yarn run watch` same as `dev` but watches files for changes and runs Browsersync. Once files are saved, they are recompiled and this triggers Browsersync to refresh the browser(s).
`yarn run production` same as `dev` but prepares the files for production minifying them and removing sourcemaps.