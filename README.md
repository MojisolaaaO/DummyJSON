# DummyJSON

# Overview
This project is designed to run automated Postman API tests of [DummyJSON](https://dummyjson.com) using GitHub Actions. 
[The Collection](https://mojisola-2659.postman.co/workspace/DummyJSON~296d41fd-c438-4321-9594-13b7829aba4d/api/e1cfdba9-ef4b-4510-a137-e42380bc970e?branch=main)

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

