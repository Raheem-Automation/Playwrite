# Playwrite
Playwrite_Cheat_Sheet
# Playwright Cheat Sheet

A quick reference for the most important Playwright concepts.

## Setup
```bash
npm init playwright@latest
npx playwright test          # run all tests
npx playwright test --ui     # interactive UI mode
npx playwright show-report   # open HTML report
npx playwright codegen  # record tests
```

## Key Areas Covered

| Area | What it covers |
|---|---|
| **Locators** | `getByRole`, `getByText`, `getByLabel`, `getByTestId`, chaining |
| **Actions** | click, fill, type, hover, check, selectOption, dragTo |
| **Assertions** | toBeVisible, toHaveText, toHaveURL, toHaveScreenshot |
| **Waiting** | Auto-waiting, waitForURL, waitForResponse, timeouts |
| **Hooks** | beforeEach/afterEach, describe, skip, only, fixme |
| **POM** | Page Object Model + Fixtures pattern |
| **Network** | route intercept, mock, fulfill, API testing |
| **Tracing** | Screenshots, visual regression, trace viewer |
| **Contexts** | Auth state, permissions, geolocation mocking |
| **CLI** | --headed, --debug, --grep, --last-failed |
| **CI/Parallel** | fullyParallel, serial, GitHub Actions reporter |
