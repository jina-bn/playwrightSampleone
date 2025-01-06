# playwrightSampleone
This is a basic framework for Playwright Javascript for web application testing. Playwright Test was created specifically to accommodate the needs of end-to-end testing. 
Installation: 

## npm init playwright@latest 

Choose between TypeScript or JavaScript (default is TypeScript) 

Playwright will download the browsers needed as well as create the following files 

playwright.config.ts 
package.json 
package-lock.json 
tests/ 
 example.spec.ts 
tests-examples/ 
 demo-todo-app.spec.ts 

playwright.config  - Add configuration for Playwright including modifying which browsers you would like to run Playwright on 

tests folder contains a basic example test to help you get started with testing 

npx playwright test  

By default tests will be run on all 3 browsers, chromium, firefox and webkit using 3 workers 

npx playwright show-report - an HTML Reporter will be generated, which shows you a full report of your tests allowing you to filter the report by browsers, passed tests, failed tests, skipped tests and flaky tests. You can click on each test and explore the test's errors as well as each step of the test. By default, the HTML report is opened automatically if some of the tests failed. 

npx playwright test –ui - Run your tests with UI Mode for a better developer experience with time travel debugging, watch mode and more. 

npx playwright –version 

## System requirements 

Node.js 18+     Windows 10 
