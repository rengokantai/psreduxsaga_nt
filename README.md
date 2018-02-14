# psreduxsaga_nt

## 3. Introducing Redux Saga
### 4 Redux Thunk vs. Redux Saga
Redux Thunk | Redux Saga
---|---
common redux middleware| common redux middleware
created by original redux creator|Third party
Runs in any js context|only runs in ES6 env that support yield
Has no built-in solution for async calls|Uses yield and generator functions to simpify async
No way to orchestrate side-effects between thunks| redux-saga uses effects and plain actions to coordinate sagas
