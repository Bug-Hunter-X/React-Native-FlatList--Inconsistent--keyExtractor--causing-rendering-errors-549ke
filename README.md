# React Native FlatList: Inconsistent `keyExtractor` causing rendering errors

This repository demonstrates a common error in React Native's `FlatList` component when the `keyExtractor` function is not properly implemented.  The `keyExtractor` function is essential for efficient rendering and updates within `FlatList`.  An inconsistent or missing `keyExtractor` can result in incorrect item rendering, extra items, or missing items in your list.

## Problem
The provided `bug.js` file showcases a scenario where the `keyExtractor` function is either missing or inconsistent, leading to unpredictable rendering behavior.

## Solution
The `bugSolution.js` file demonstrates the correct implementation of the `keyExtractor` function.  It ensures that each item in the `FlatList` receives a unique key, guaranteeing correct and efficient rendering.

## How to Reproduce
1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install`.
4. Run `npx react-native run-android` or `npx react-native run-ios`.
5. Observe the incorrect rendering in `bug.js` and the corrected rendering in `bugSolution.js`.