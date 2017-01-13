# Dr Olfson for Tyson Steele
### By Joe Karasek _*1/17/16*_

## Setup

Install node dependencies:

    yarn install

## Usage

Compile site:

    npm run compile

Compile site, start watches, and serve:

    npm start

Deploy site: (*Note*: You will need to setup your siteConfig.py file to deploy)

    npm run deploy

## Sass

See [sassdoc](http://sassdoc.com/) docs at `./sassdoc` (at http://localhost:3002/sassdoc after `npm start`)

Add more sassdoc annotations like `/// @param` by seeing [docs here](http://sassdoc.com/annotations).

## Troubleshooting

Delete `node_modules` and re-install:

    rm -rf node_modules
    npm install

