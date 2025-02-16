# React Component State Not Updating on Prop Changes

This repository demonstrates a common React bug where a component's state doesn't update correctly when its props change. The bug stems from using the wrong lifecycle method to update the state based on prop changes.  The solution uses `componentDidUpdate` which is called after an update occurs. 

## Bug Description
The `BuggyComponent.js` file shows the buggy implementation, while `FixedComponent.js` provides the solution.

## How to Reproduce
1. Clone this repository.
2. Navigate to the repository directory.
3. Run `npm install`.
4. Run `npm start`.
5. Observe the incorrect behavior in the buggy component and the corrected behavior in the fixed component.