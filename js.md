# Javascript

Javascript is the only language currently that can be run in the web browser in the frontend and used to run a backend web server using NodeJS. So to use Javascript for backend purposes you need NodeJS.

## Installation

- [INSTALL ON MAC](https://www.newline.co/@Adele/how-to-install-nodejs-and-npm-on-macos--22782681)
- [INSTALL ON LINUX](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04)
- [INSTALL ON WINDOWS](https://phoenixnap.com/kb/install-node-js-npm-on-windows)

## First Steps

[USE THIS JAVASCRIPT PLAYLIST TO SUPPLEMENT WHAT YOU LEARN IN CLASS](https://www.youtube.com/playlist?list=PLY6oTPmKnKbZDZ9cRrRby4Wnr4GIJj5O3)

## Other Important Libraries To Learn About

- axios: popular data fetching library
- date-fns: popular library for working with dates in javascript
- chalk: library for making your terminal output... colorful
- [Javascript Animation Libraries](https://www.codeinwp.com/blog/best-javascript-animation-libraries/)
- [Javascript Data Visualization Libraries](https://www.monterail.com/blog/javascript-libraries-data-visualization)

### The Big Front-End UI Frameworks

1. [React](https://www.youtube.com/playlist?list=PLY6oTPmKnKbba6LlpF7kcnsyWdlwePt_V)
2. [Vue](https://www.youtube.com/playlist?list=PLY6oTPmKnKbbsEAIDfFAlhAVbSCIt2Bxx)
3. [Angular](https://www.youtube.com/playlist?list=PLY6oTPmKnKbahNK_YUsjTzP5U-FkGA544)
4. [Svelte](https://www.youtube.com/playlist?list=PLY6oTPmKnKbZpyj6WhUsjri1Tw_BO-obP)
5. [StencilJS](https://www.youtube.com/playlist?list=PLY6oTPmKnKbazpUTMcGmvMtgU5sr0Ip-V)
6. [Web Components](https://www.youtube.com/playlist?list=PLY6oTPmKnKbaNVkXHOHWxgdKEZLGKuFP9)

## Trouble Shooting Notes

- Environmental variables work differently on windows so scripts with env variables for example `PORT=3000 node server.js` will error on windows. To fix this install the cross-env library and pre-fix your script like this to work on all operating systems `cross-env PORT=3000 node server.js`
