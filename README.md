# DummyJSON

# Overview
This project is designed to run automated Postman API tests using GitHub Actions. 

# Features
- Automated Postman API testing using Newman (Postman's CLI tool)
- Continuous Integration via GitHub Actions
- HTML Report Generation and Deployment to GitHub Pages
- Easy access to test results via a public URL

# Workflow Summary
- Postman API Tests: Each time a change is made to the collection or environment file
and pushed to the main branch, the GitHub Actions workflow runs Postman API tests.
- HTML Report Generation: After running the tests, an HTML report is generated using Newman HTML reporter.
- GitHub Pages Deployment: The generated report is deployed to GitHub Pages and is accessible via [Test Report](https://mojisolaaao.github.io/DummyJSON/report.html).

