# Question list:
## Which of the following are some of the pitfalls of directly using threads in your code?
Choose as many answers as you see fit.

<ol type="a">
  <li>Race conditions</li>
  <li>Inconsistent output</li>
  <li>Unresponsive UI</li>
  <li>Thread is deprecated</li>
</ol>

**Answer:A,B,C**

## Which statement below is true about coroutines?

<ol type="a">
  <li>Once started, a coroutine cannot be canceled.</li>
  <li>A coroutine always runs on the main thread.</li>
  <li>A coroutine may or may not execute.</li>
  <li>Coroutines avoid the need to create new threads, by running every task on the same thread.</li>
</ol>

**Answer:C**


## True or False: If a function already calls a suspend function, then it does not need to be marked as a suspend function itself.

<ol type="a">
  <li>True</li>
  <li>False</li>
</ol>

**Answer:B**

## Which of the following are suspend functions?.
Choose as many answers as you see fit.

<ol type="a">
  <li>async()</li>
  <li>The lambda passed into async()</li>
  <li>runBlocking()</li>
  <li>The lambda passed into runBlocking()</li>
</ol>

**Answer:B,D**

## Which statement below is false about async() and runBlocking()?

<ol type="a">
  <li>Both functions take a CoroutineScope (a suspend function) as a parameter.</li>
  <li>Both functions return a Deferred</li>
  <li>You'll typically not use runBlocking in Android app code.</li>
  <li>When using async, you need to use await() to access the returned value.</li>
</ol>

**Answer:B**


## True or False: In most apps, you would create coroutines using the global scope.

<ol type="a">
  <li>True</li>
  <li>False</li>
</ol>
**Answer:B**

## What is responsible for determining which thread is used behind the scenes by a coroutine?

<ol type="a">
  <li>CoroutineScope</li>
  <li>Dispatcher</li>
  <li>Job</li>
  <li>GlobalScope</li>
</ol>

**Answer:B**

## True or False: A Job is a cancelable unit of work performed by a coroutine.

<ol type="a">
  <li>True</li>
  <li>False</li>
</ol>

**Answer:A**













