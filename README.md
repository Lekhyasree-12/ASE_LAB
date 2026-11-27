# Simple Java GitHub Actions Demo

A small Maven project with one Java class, one JUnit 5 unit test, a Checkstyle code check, and a GitHub Actions workflow.

## Run locally

Requires JDK 17 and Maven.

```bash
mvn clean verify
```

This runs Checkstyle during Maven's `validate` phase and then runs the JUnit test.

## GitHub Actions

Push this project to GitHub. The workflow at `.github/workflows/ci.yml` runs on every push to any branch and on pull requests.

Open your repository on GitHub and select **Actions** to see the run. A green check means the workflow passed.
