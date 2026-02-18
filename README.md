# github_actions
How to set up github actions and push directly to test on Android and Apple for flutter apps. This works on 18th feb 2026, will probably have to be tweaked to work for your project.


# Apple

## Regular apple errors
### Main.yaml
- Keep in mind to always check the xcode version, and the flutter version. Rule: if you update flutter or xcode locally, update here as well.
- Github actions engine loved to give me errors that did not provide any good explanation, so especially keeping check on which flutter version is stable is important. Also writing latest-stable have never worked in my case, so do specify it.

# Android

## Setup android keys 
[Instructions here](https://github.com/claratoll/github_actions/blob/main/androidkeys.md)

## Regular android errors
### Main.yaml
- no crashes bc android is perfect

### Gradle
- gradle versions can mess it all up and give unexplanable errors so do keep them updated in all files.
