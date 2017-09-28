<h1 align='center'>Gravnd Zero</h1>

<p align='center'>
  Minimal theme for <a href='http://github.com/getgrav/grav'>Grav CMS</a>. No dependencies, improved directory structure, optimized build process and freedom to create.
</p>

### Features

- [Laravel Mix](https://laravel.com/docs/5.5/mix) Webpack wrapper allowing the asset pipline flow smoothly
- [Browsersync](https://www.browsersync.io/) Syncs your devices and refreshes the browsers everytime you make a change

### Installation

#### [Grav Package Manager](http://learn.getgrav.org/advanced/grav-gpm) (Recommended)

``` sh
$ cd path/to/grav
$ bin/gpm install gravnd-zero
$ cd /user/themes/gravnd-zero
$ yarn
```

#### [Grav Admin Plugin](https://github.com/getgrav/grav-plugin-admin)

Log in to admin panel go to `Themes > Add` search for Gravnd Zero and click `Install`. After that, `Activate` the theme.
> Using this method you will have to manually copy files from `user/themes/gravnd-zero/_demo/pages` to `user/pages`

#### Manual

``` sh
$ cd path/to/grav/user/themes
$ git clone https://github.com/fistmenaruto/gravnd-zero.git
$ cd gravnd-zero
$ yarn
```
> Using this method you will have to manually copy files from `user/themes/gravnd-zero/_demo/pages` to `user/pages`

### Usage

1. Start your dev server

2. Run yarn/npm script

  ``` sh
  # Compile .scss, .js, .twig files and add sourcemaps.
  $ yarn dev

  # Same as dev but watches files for changes and runs Browsersync.
  # Once files are saved, they are recompiled and Browsersyn refreshes the browsers.
  $ yarn watch

  # Prepares the files for production minifying them and removing sourcemaps.
  $ yarn production
  ```

> Before starting I recommend to review settings in `webpack.mix.js`

### [Contribute](CONTRIBUTING.md)

See [CONTRIBUTING.md](CONTRIBUTING.md)

<h3 align='center'>Thank you</h3>

<p align='center'>
  To <a href='https://github.com/robbinfellow'>Robbin Johansson</a> and his <a href='https://github.com/robbinfellow/haywire-grav'>Haywire</a> Grav theme, on which this project is based on.
</p>
