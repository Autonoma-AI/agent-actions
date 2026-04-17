# Autonoma Agent Actions

A collection of GitHub Actions for integrating [Autonoma](https://autonoma.app) into your CI/CD pipeline. The `analyze-changes` action triggers Autonoma's diff analysis for a deployed commit — it detects the associated pull request, sends the deployment URL to Autonoma's API, and returns branch, snapshot, and deployment IDs that can be used in subsequent workflow steps.
