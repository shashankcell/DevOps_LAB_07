# Experiment 07 — Automated build checks and unit testing

**Student:** [Your name]  
**Register number:** [Your register number]  
**Course:** Collaborative Development and DevOps

## Aim

Write a small Python calculator, cover its behavior with unit tests, and run those tests automatically with GitHub Actions.

## Files

- `calculator.py` — arithmetic functions with division-by-zero handling.
- `tests/test_calculator.py` — standard-library unit tests.
- `.github/workflows/python-tests.yml` — workflow that runs the tests.

## Run locally

```sh
python -m unittest discover -s tests -v
```

A non-zero exit code indicates a failing test. Fix the implementation or test, then run the command again.

## Automation

Push the files to `main` or create a pull request targeting `main`. In GitHub, open **Actions** and inspect the test job. The workflow does not install third-party packages.

## What to record

List the test cases, the local test result, and the GitHub Actions run link and status. Do not claim the workflow passed until you have inspected its run.

## Result

Complete this section after the checks have run.

## Reference and attribution

The topic follows the build-and-testing automation theme in [Smirk1308/DevOps_LAB_07](https://github.com/Smirk1308/DevOps_LAB_07). The implementation and tests here are independently written.