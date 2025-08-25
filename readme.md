# Jenkins Shared Library

This is a shared library for Jenkins pipelines, providing reusable components for CI/CD workflows.

## Components

- **MavenOps**: Maven build operations
- **ImageOps**: Docker image operations
- **postAction**: Post-build cleanup function

## Usage

In your Jenkinsfile, add this at the top:

```groovy
@Library('my-jenkins-sharedlib@main') _
