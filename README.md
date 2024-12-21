# React Native Layout Calculation Issues

This repository demonstrates a common bug in React Native related to layout calculations. The bug occurs when a component attempts to access its layout dimensions before they have been calculated. This often leads to inconsistent rendering or crashes.

The `LayoutBug.js` file contains the buggy code, while `LayoutBugSolution.js` provides a fix using the `onLayout` event to ensure layout calculations complete before accessing dimensions. 