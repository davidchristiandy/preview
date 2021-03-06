![PReview Logo](https://user-images.githubusercontent.com/1614415/40420806-b9ede03a-5eb3-11e8-9eb3-39aabfec668f.png)

# PReview

[![CircleCI](https://circleci.com/gh/traveloka/preview/tree/master.svg?style=svg)](https://circleci.com/gh/traveloka/preview/tree/master)

> Browser extension to help make your GitHub PR review experience better

## Install

Install via [Chrome Web Store](https://chrome.google.com/webstore/detail/jgmndkkhollhdepgnhinofidfjojlkod)

## Local Setup

```sh
# clone repo
git clone git@github.com:traveloka/preview.git
cd preview

# install dependencies
yarn

# run locally
yarn start
```

This will create `build/` directory with necessary files inside of it. To test it locally, you need to install the extension to the browser by following these steps:

1.  Open `chrome://extensions/`
2.  Check **Developer mode**
3.  Click on **Load unpacked extension**
4.  Select the `build` directory.

Then, simply refresh your PR files page

## License

MIT
