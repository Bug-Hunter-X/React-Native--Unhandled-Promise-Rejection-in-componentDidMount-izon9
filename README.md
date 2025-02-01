# React Native Unhandled Promise Rejection

This repository demonstrates a common error in React Native applications: accessing state properties before they are initialized.  The `bug.js` file shows the problematic code, which attempts to access `this.state.data` before it's been populated via an API call in `componentDidMount`.  The `bugSolution.js` file provides a corrected version that uses conditional rendering to avoid accessing the property until it exists.