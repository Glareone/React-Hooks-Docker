# React in Kubernetes. React app Dockerfile + nginx example
### Kubernetes
[Docker file for React Production in Azure Kubernetes](https://github.com/Glareone/React-Hooks/blob/master/Dockerfile.standalone)  
[nginx file which is suitable for React standalone in Azure Kubernetes](https://github.com/Glareone/React-Hooks/blob/master/nginx.conf)  

### Redshift
* In order to make it suitable for RedShift you need to update dockerfile and Deployment:
  - `runAsNonRoot: true`  
  - Dockerfile USER. Better explained here: https://juffalow.com/blog/javascript/non-root-containers-in-kubernetes

# React Hooks

Interesting Sites:  
* [USE HOOKS](https://usehooks.com/)
* [RW;ERUCH](https://www.robinwieruch.de/blog)

## Simple Examples

#### [Beginner] Use State
[Use State Example](https://codesandbox.io/s/glareone-usestate-initial-28q54)

[UseState with PrevState](https://codesandbox.io/s/usestate-prevstate-xcjh0?file=/src/App.js)

#### [Beginner] Use Effect
[Use Effect Example](https://codesandbox.io/s/glareone-useeffect-example-uxzsf)

* [] in the end means "to run only once in the very beginning"
* [user] to raise every time when property "user" changes.
* without declaring second parameter in useEffect - runs after any changes (possibly mupliple runs)

#### [Beginner] Use Reducer
[Use Reducer Example](https://codesandbox.io/s/glareone-usereducer-example-b7jt3)

#### [Beginner] Use Ref
[Use Ref Example](https://codesandbox.io/s/glareone-useref-example-jb0li?file=/src/App.js)

#### [Intermediate] Custom Hook (useState custom hook, useFetch custom hook)
[Use Custom Hooks Example](https://codesandbox.io/s/glareone-custom-hooks-example-22h2i?file=/src/App.js)  
[UseFetch Custom Hook (Call to Github) Example](https://codesandbox.io/s/glareone-usefetch-bb3cr?file=/src/App.js)  

#### [Intermediate] SetInterval and how to properly handle it using custom Hook
[SetInterval]https://codesandbox.io/s/lingering-mountain-hq9rpy?file=/src/useHook.js

## Context

#### [Intermediate] Simple useContext createContext Example
[useContext CreateContext Example](https://codesandbox.io/s/glareone-context-example-liej5?file=/src/AppInner.js)
[Simple useContext + Custom Hook for Context](https://codesandbox.io/s/glareone-context-customhook-example-th6bg?file=/src/AppInner.js)

#### [Intermediate][Javascript] Context + Reducer (Redux Pattern, contextApi)
[UseReducer with Context, Redux Pattern](https://codesandbox.io/s/glareone-context-reducer-1t99i?file=/src/components/Blog/blog.js)  
[UseFetch + UseReducer + UseContext, Redux Pattern](https://codesandbox.io/s/glareone-context-reducer-with-custom-hook-cxpcx?file=/src/hooks/useFetch.js)  

#### [Advanced][Typescript] Context + combineReducers + Multiple Storages + SCSS (ContextAPI) 
[UseReducer, combineReducers, ContextAPI](https://codesandbox.io/s/glareone-contextapi-combinereducer-multiplestore-typescript-eyf97h)   
[UseReducer, combineReducers, ContextAPI, SCSS](https://codesandbox.io/s/glareone-contextapi-combinereducer-multiplestore-scss-typescript-gcw6be)   
IN PROGRESS: [env, Login with Okta](https://codesandbox.io/s/glareone-contextapi-combinereducer-multiplestore-scss-env-config-typescript-f02sd3)  



