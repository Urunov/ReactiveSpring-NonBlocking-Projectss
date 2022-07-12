# ReactiveSpring-NonBlocking-Projectss

git remote add origin https://github.com/Urunov/ReactiveSpring-NonBlocking-Projectss.git

## --> Fundamental Design API 

 * Imperative Style APIs
    - Top-down approach.
    - Blocking and Synchronous.
    
 ![Screen Shot 2022-07-12 at 17 19 26](https://user-images.githubusercontent.com/11626327/178488103-325c979e-f509-4c80-8e9b-52ba869298c9.png)


<b> We should to make calls asynchroous, basically non blocking <b>

* Currently in Java we have: 
  - Callbacks
     - Complex
     - NO return 
     - Code is hard to read and maintain
     - Leads to CallBack hell.
     
  - Futures
     - Another alternative to write asynchrnous code in Java.
     - Returns Future instance.
     - Hard to compose multiple asynchronous operations.

* Completable Future
   - Introduced as part of Java 8.
   - Supports functional sytle API.
   - Easy to compose multiple Asynchrnous operations.
   - Not a greate fit asynchrnous call with multiple items. 

## 1. Reactive Spring 

Asynchronous and Non Blocking.

## 2. Thread per request.
