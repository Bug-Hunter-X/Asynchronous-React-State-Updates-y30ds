# Asynchronous React State Updates
This example demonstrates a common issue in React where developers accidentally rely on synchronous behavior of state updates.  React's state updates are asynchronous; the value of `count` is not immediately updated after calling `setCount`. 

The solution shows how to use functional updates or useEffect hook to address this issue.