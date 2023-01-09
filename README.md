# Expo Preview Branches 🚀

A Github Action to automatically generate preview branches using EAS (Expo Application Services) as part of a CI/CD workflow, creating live deployments that allow the reviewer to functionally check any changes in the app. Automatically pushes updates to `main` after merge and cleans up the preview deployment.

## Setup

1. Follow the Expo [docs](https://docs.expo.dev/eas-update/github-actions/) on setting up EAS CLI within your Github actions. This will require you to add a secret called `EXPO_TOKEN` which is mentioned in the Expo docs above. 
2. Copy the entirety of `.github` folder into your app and push the changes. 

Alternatively, you should be able to add the pre-existing action from the Github Marketplace. However, if you want to customise the workflow, then you'll need to follow the steps above. 

