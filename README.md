# React 19  useOptimistic Hook


useOptimistic is a React Hook that lets you show a different state while an async action is underway. 
It accepts some state as an argument and returns a copy of that state that can be different during 
the duration of an async action such as a network request. You provide a function that takes the 
current state and the input to the action, and returns the optimistic state to be used while the action 
is pending.This state is called the “optimistic” state because it is usually used to immediately present 
the user with the result of performing an action, even though the action actually takes time to complete.


![uastate](https://github.com/user-attachments/assets/a7f9caa0-7a50-4c55-8254-8793953b5239)
