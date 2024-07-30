# frontend-ci-action

## Inputs
- commit-token: A Github Token with `repos` scope.
- branch-name: A branch to store test results files.

## What did this action do
1. `yarn install` & `yarn run test`
2Create or update test results files of specific branch for tests badges.

## Badge url
Will be like:
```
https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/{YourUserName}/{YourProjectName}/{NameOfYourBranchToStoreTestResults}/{NameOfYourBranchToShowBadge}-test-results.json
```
