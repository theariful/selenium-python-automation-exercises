# Selenium Python Automation Exercises

Browser automation exercises written with Selenium WebDriver and Python — the drills behind the fundamentals: launching a driver, navigating, and reading page state back out for assertions.

## What is covered

- Launching and closing a WebDriver session cleanly
- Navigating to a target URL
- Extracting the page **title** and the **current URL**, and asserting on both
- Basic element location and interaction

Title and URL assertions look trivial, but they are the first check in almost every real test — they confirm that navigation, redirects, and authentication landed you where you expected before anything else is asserted.

## Prerequisites

```bash
pip install selenium
```

A matching browser driver must be on your `PATH` (or use Selenium Manager, which resolves it automatically in Selenium 4.6+).

## Run

```bash
python <script_name>.py
```

## Related work

| Repository | Focus |
| :--- | :--- |
| [selenium-java-junit-webform-automation](https://github.com/theariful/selenium-java-junit-webform-automation) | Selenium with Java and JUnit |
| [jmeter-api-load-and-stress-testing](https://github.com/theariful/jmeter-api-load-and-stress-testing) | Load and stress testing |
| [swagger-petstore-api-testing-collection](https://github.com/theariful/swagger-petstore-api-testing-collection) | REST API testing |
| [qa-test-documentation-templates](https://github.com/theariful/qa-test-documentation-templates) | QA documentation artifacts |
