# This is a simple Android Jetpack Compose Template
---

## Why?
---

- This is a template for studies purposes, so it is easier to clone and start a new Study Project;
- Made CI workflow with GitHub Actions;

## GitHub Actions
---
- Created `.github/workflows/build.yml` with the following steps:
    - Checkout;
    - Setup Java JDK with `java-version: 1.8`;
    - Build with Gradle;
    - and Upload APK (The uploaded APK will be in main Actions Tab);