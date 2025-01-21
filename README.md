# Expo Web Module Not Found Error

This repository demonstrates a common error encountered when developing Expo apps for the web: 'Module not found' errors when importing modules that are not compatible with the web platform.  This error typically arises from attempting to use native React Native modules in your web code.

## Problem

The `bug.js` file demonstrates how trying to import a native module (in this case, a placeholder) will fail in a web environment.  This could manifest with any number of native modules, causing the error on web build. 

## Solution

The `bugSolution.js` file shows how to resolve this issue using conditional imports.  This involves checking the platform (web or native) and then importing either the web-compatible alternative or the native module accordingly.