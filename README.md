CI/CD pipeline example for static HTML page

Directory Structure

Ci-CD-example
 ├── .github/workflows
 └── index.html

Workflows folder contains .yml file for static webpage deployment.

Pipeline will trigger:
- On push to main branch
- Manual trigger

Machine on which this will run:
- GitHub hosted runner (Ubuntu)

Pipeline Steps:
- Checkout repository
- Integrate static webpage
- Deploy static webpage
