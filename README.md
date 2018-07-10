# nightwatch-cucumber-example
Example for [`nightwatch-cucumber`](https://github.com/mucsi96/nightwatch-cucumber) usage

## Usage

```
npm i -g ntl
git clone git@github.com:mucsi96/nightwatch-cucumber-example.git
cd nightwatch-cucumber-example
npm i
ntl
```
## Executing individual feature files or scenarios
Single feature file
```
npm run e2e-test -- features/google-search.feature
```
Multiple feature files
```
npm run e2e-test -- features/google-search features/duckduckgo-search
```
Single scenario by its line number
```
npm run e2e-test -- features/google-search.feature:9
```