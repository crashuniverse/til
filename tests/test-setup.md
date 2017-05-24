# Test setup

A typical test setup has 5 concerns.

1. Test suite
2. Test runner
3. DOM utility
4. Assertion
5. Coverage reports

A few selections of piece of softwares can form a test setup to address these concerns. They are:

Test Suite | Test Runner | DOM utility             | Assertion              | Coverage reports
---------- | ----------- | -----------             | ---------              | ----------------
Jasmine    | Karma       | Enzyme, React DOM Utils | Jasmine inbuilt expect | Istanbul, Coveralls
Mocha      | Karma			 | Enzyme, React DOM Utils | Chai/expect, should, assert, expect.js | Istanbul, Coveralls
Jest			 | Jest			   | Enzyme, React DOM Utils | Jest inbuilt assertion | Istanbul, Coveralls
