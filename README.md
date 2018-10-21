# Next.js + Fonts
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fninetynine%2Fnext-fonts.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fninetynine%2Fnext-fonts?ref=badge_shield)


Import fonts in [Next.js](https://github.com/zeit/next.js)
(woff, woff2, eot, ttf, otf & svg)

This package was original taken from [here](https://github.com/rohanray/next-fonts) but it was unmaintained, so I am continuing maintenance here

## Installation

```
npm install --save @ninetynine/next-fonts
```

or

```
yarn add @ninetynine/next-fonts
```

## Usage

Create a `next.config.js` in your project

```js
// next.config.js
const withFonts = require('@ninetynine/next-fonts')
module.exports = withFonts()
```

Optionally you can add your custom Next.js configuration as parameter

```js
// next.config.js
const withFonts = require('@ninetynine/next-fonts')
module.exports = withFonts({
  webpack(config, options) {
    return config
  }
})
```




## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fninetynine%2Fnext-fonts.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fninetynine%2Fnext-fonts?ref=badge_large)