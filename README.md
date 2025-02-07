# Expo CLI Android Build Failure: AGP Version Conflict

This repository demonstrates a common issue encountered when building Android apps using the Expo CLI: conflicts or missing dependencies related to the Android Gradle Plugin (AGP).

## Problem
The Expo build process fails, typically during the Android build phase, due to inconsistencies or incompatibility between the AGP version, Expo SDK version, and other project dependencies.  This often manifests as error messages indicating missing classes, version mismatches, or build failures within the Gradle build system.

## Solution
The solution typically involves ensuring all dependencies are compatible and correctly configured.  This might include updating the AGP version, updating other dependencies, or resolving configuration conflicts within the `android` directory of the project.

## Steps to Reproduce
1. Follow the instructions in `bug.js` to replicate the environment causing the build failure.
2. Attempt to build the Android app using the Expo CLI (`expo build:android`).
3. Observe the error messages reported during the build process.

## How to fix the issue
Follow the instructions in `bugSolution.js` to resolve the build failure by correcting dependencies and configurations.

## Contributing
Contributions are welcome!