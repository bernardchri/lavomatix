![Lavomatix starter kit](./logo.jpg)

# LAVOMATIX

#### JS/CSS bundler
A simple and conventionnal project structure easy to use.
> scss and babel-preset-env ready with laravel-mix agnostic bundler
> [Laravel Mix](https://laravel-mix.com/docs/2.1/installation)

###  /!\ Word In Progress

### INSTALLATION

```
git clone https://github.com/bernardchri/lavomatix.git front
cd front
rm -rf .git
npm install
cp .env_sample .env
```

the ".env" file contains relative configurations. Feel free to edit it.


### USAGE

These scripts will generate files in the ".env" configuration location

```npm run dev``` to generate a dev bundle

```npm run watch``` to launch BrowserSync and watch **./src**

```npm run build``` to generate a prod ready dist folder, minified and sourcemapped

### CAVEATS

- todo

#### Credits and documentation
[Laravel Mix](https://laravel-mix.com/docs/2.1/installation)

### install usefull lib
- npm install intersection-observer (polyfill intersection observer)
- npm install tiny-slider (slider)
- npm install body-scroll-lock
- npm install gsap
- npm install textFit ( resize text )
- npm install vanilla-tilt (tilt effect)
- npm install body-scroll-lock ( bloc scroll)


