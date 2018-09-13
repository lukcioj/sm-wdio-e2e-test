# sm-wdio-e2e-test

An example of test automation with use of WebdriverIO framework

## Getting Started

### Prerequisites

```
Node.js
npm/yarn
```

### Installing

Just:
```
yarn
```

## Running the tests

#### all tests
when providing an URL for baseUrl param please note that there should be no extra chars like `/`
```
yarn test --baseUrl=http://testedwebsite.com
```

#### specific spec 
```
yarn test --baseUrl=http://your-tested-website.com --spec=prizesList.spec.js
```

### Reporting
project uses allure reporter for reporting, run:
```
yarn allure
```
and check `./reports/allure-output` directory

### Other useful scripts
Use command below to identify coding and styling issues 
```
yarn lint
```

## Authors

* **Łukasz J** - [lukcioj@github](https://github.com/lukcioj)



