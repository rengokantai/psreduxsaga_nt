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



## 7. Testing Redux Saga Applications
### 2 Testing Redux Saga Applications

### 3 Methods for testing Redux Saga Applications
methods
- Mock store and application state are created
- Entire saga is run from beginning to end
- At completion, new state is compared to expected value
- APIs must be injected as dependencies
