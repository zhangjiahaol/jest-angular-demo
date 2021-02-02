# Jest unit tests for Angular Demo
A demo of Jest unit tests with Angular.

## Getting Started
Clone or download this repository
```bash
git clone https://github.com/mystohaxen/jest-angular-demo.git jest-angular-demo
cd jest-angular-demo
```

and run:

```bash
npm install
npm run test

./node_modules/.bin/jest --ci --coverage --coverageReporters=lcovonly --coverageReporters=cobertura --testURL=http://localhost/ --reporters=jest-junit

ls -l coverage/cobertura-coverage.xml
ls -l junit.xml

```
Related blog post to find out what this is all about: https://medium.com/mystohaxen/how-to-use-jest-unit-tests-with-angular-87509b500158
# jest-angular-demo
