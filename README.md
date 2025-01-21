# React Router v6 Nested Route Rendering Issue

This repository demonstrates a common issue encountered when working with nested routes in React Router v6.  The problem involves nested routes not rendering correctly, even though they are defined in the route configuration.

The `App.js` file contains the buggy implementation.  The solution, which addresses the rendering problem, is provided in `AppSolution.js`.

## Problem

The original code defines nested routes, however, navigating to these nested routes does not display the expected components.  The parent route renders, but the child components are not mounted. 

## Solution

The solution involves ensuring the correct structure and usage of `Routes` and `Route` components within React Router v6 to correctly handle nested route rendering.  The `AppSolution.js` file showcases the corrected implementation.