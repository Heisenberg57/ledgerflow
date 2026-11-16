# LedgerFlow — Engineering Learning Log

## Day 2: Playwright Fundamentals

### Concepts explored
- Playwright test registration using `test()`
- Assertions using `expect()`
- Browser page fixture
- Asynchronous execution with `async/await`
- Playwright auto-retrying assertions
- Cross-browser test execution

### Practical investigation
- Intentionally modified the expected page title.
- Observed assertion failure diagnostics.
- Examined expected versus actual values.
- Investigated assertion timeout and retry behaviour.
- Restored the original assertion.

### Key takeaway
A test failure does not automatically indicate an application defect. Assertion diagnostics provide evidence that should be investigated before deciding on a fix.

### Next session
Explore Playwright locators, DOM interaction and locator strategies.