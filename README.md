# Quick Browser Test Environment

This repo gives you a quick starting point for mocking up quick javascript 
tests that you want to run in the browser.

This would be good for a quick TDD session. As you edit `index.js` the 
browser(s) will update the results each time you save, allowing for quick
visual feedback and iteration.

![Screenshot](https://i.cloudup.com/PsjtTPJKWe.jpg)

## Getting started

```bash
git clone git@github.com:jmorrell/quick-browser-js-test-environment.git
cd quick-browser-js-test-environment
npm install
npm start
```

This should open up the test page in your default browser. Then start editing `index.js`.
The browser will update as you save `index.js`. Opening up other browsers to the same
URL will have them play along too!

## Test Syntax

Test syntax relies on [tape](https://github.com/substack/tape)

