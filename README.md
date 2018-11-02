# Readify Signature Generator

This app can be used to create Readify's Email Signature.


## Setup
- Clone repo
- Open index.html in a modern browser

## Tech Stack
### ReactJS
Note, in the interest in time, this app  uses the development version of react, served over CDN. 

Because of this it uses a browser version of babel. If you care about performance or stability, 
you should probably build the app locally and then server a minified version with production react

## Looks great, how can I use if for my company?
All the components in App.js have their brand information extracted into a `brandInfo` variable in the render method.
Just replace the information in their with your own content and you are good to go! 

## Licence 
MIT, See: [LICENSE](https://github.com/Readify/readify-signatures/blob/master/LICENSE)