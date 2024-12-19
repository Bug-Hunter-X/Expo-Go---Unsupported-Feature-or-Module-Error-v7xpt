# Expo Go: Unsupported Feature or Module Error

This repository demonstrates a common issue in Expo development where attempting to utilize a feature or module not supported by the current Expo Go version or SDK leads to runtime errors.  The example shows how to identify and resolve such issues.

## Bug Description:

The `unsupportedFeature.js` file illustrates code that tries to access an unsupported module, resulting in an error when run in Expo Go.  The specific error message will depend on the unsupported module and Expo SDK version.

## Solution:

The `unsupportedFeatureSolution.js` file provides a solution by either (1) using an Expo-compatible alternative, (2) upgrading the Expo SDK, (3) ejecting from Expo (if feasible), or (4) waiting for the feature to gain official Expo support.