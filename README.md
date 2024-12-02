# DummyJSON

# Overview
This project is designed to run automated Postman API tests using GitHub Actions. Each time a change is made to the collection or environment files, the tests are executed, and the results are published as an HTML report on GitHub Pages.

# Features
- Automated Postman API testing using Newman (Postman's CLI tool)
- Continuous integration via GitHub Actions
- HTML report generation and deployment to GitHub Pages
- Easy access to test results via a public URL

# Workflow Summary
- Postman API Tests: Every time a change is pushed to the main branch or a pull request is created, the GitHub Actions workflow runs Postman API tests on the collection and environment files.
- HTML Report Generation: After running the tests, an HTML report is generated using Newman HTML reporter.
- GitHub Pages Deployment: The generated report is deployed to GitHub Pages and is accessible via [Test Report](https://mojisolaaao.github.io/DummyJSON/report.html) for easy access to the results.

