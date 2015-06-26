[![build status](https://circleci.com/gh/kukareka/sphere-weather/tree/master.svg?style=shield&circle-token=1c6805a71d2119080cad94be68baa4f2be863c23)](https://circleci.com/gh/kukareka/sphere-weather/tree/master)

# Sphere Weather

Simple weather element for [Polymer 1.0](https://www.polymer-project.org/1.0/).

## Install

Install element via [Bower](http://bower.io/):

    bower install https://github.com/kukareka/sphere-weather.git

## Play

Use this link to play with the element online: 

http://kukareka.github.io/sphere-weather/components/sphere-weather/demo/index.html

To add new city - enter city name and click the "+" button or press ENTER.

## Use

Sample code to embed the element:

    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, minimum-scale=1.0, initial-scale=1.0, user-scalable=yes">
        <title>Sphere Weather Demo</title>
        <script src="../../webcomponentsjs/webcomponents-lite.js"></script>
        <link rel="import" href="../sphere-weather.html">
        <style>
            sphere-weather {
                margin: auto;
                max-width: 600px;
            }
        </style>
      </head>
      <body>
        <sphere-weather></sphere-weather>
      </body>
    </html>

## Test

Use this link to run the tests online: 

http://kukareka.github.io/sphere-weather/components/sphere-weather/test/index.html

If you are using Polyserve: `http://localhost:8080/components/seed-element/test/`

### web-component-tester

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester).
Install it via:

    npm install -g web-component-tester

Then, you can run your tests on _all_ of your local browsers via:

    wct

#### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).

`wct test/some-file.html` will test only the files you specify.

## TODO

- Don't create new tab if a city already exists. Open existing tab instead.
- Close inactive tabs in one click. Now it needs additional click to activate the tab.
- Vertically center text and "loading" spinner in tab (via flex layout).
- Improve input validations.
- Improve documentation.
- Refactor tests and improve test coverage.
 
