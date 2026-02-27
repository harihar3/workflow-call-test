# workflow-call-test
# Reusable Workflow Test

This repository is created to test GitHub Actions reusable workflow behavior.

Goal:
- Validate how `workflow_call` handles `github.event_name`
- Pass the original event from caller workflow
- Ensure apply job runs only on push to main

This is a personal test before implementing the logic in the main project.
