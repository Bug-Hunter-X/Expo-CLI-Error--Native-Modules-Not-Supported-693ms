# Expo CLI Error: Native Modules Not Supported

This repository demonstrates a common error encountered when using the Expo CLI with packages that rely on native modules.  The error message is usually vague, making debugging challenging.  This example shows the problem and how to resolve it using Expo's managed workflow and SDK alternatives.

## Problem

Attempting to use a package that requires native modules (like a camera library) within an Expo managed workflow results in an error similar to:  `Error: Native modules are not supported in this environment`.

## Solution

The solution involves replacing the native module with an Expo-compatible alternative or ejecting from Expo's managed workflow (generally discouraged). This example demonstrates using Expo's Camera API as an alternative.