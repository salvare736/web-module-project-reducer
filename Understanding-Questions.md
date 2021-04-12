# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

    Ans) Upon pressing the '1' button, the dispatch function invokes the 'addOne' function, which returns an invocation of the 'reducer' function with a type of 'ADD_ONE'. Within the conditional, the 'reducer' function carries out the appropriate operation and returns the result ('state.total + 1' in this case). This change in state is detected by the reducer in the 'App.js' file and the necessary UI elements re-render to display the updated data.
