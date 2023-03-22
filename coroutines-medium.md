# Question list about: coroutines and use cases
## What are the benefits of using coroutines?
Choose as many answers as you see fit.

<ol type="a">
  <li>Callback-free, sequential code</li>
  <li>Structured concurrency (e.g. run async operations in a scope)</li>
  <li>Built-in cancellation support</li>
  <li>Faster execution of background work</li>
</ol>
**Answer:A,B,C**

## What can call a function marked with the suspend modifier without causing a compile error?
Choose as many answers as you see fit.
<ol type="a">
  <li>Any Kotlin function</li>
  <li>Other suspending functions</li>
  <li>Only public functions</li>
  <li>Coroutines</li>
</ol>

**Answer: B,D**

## What is the recommended CoroutineScope to use in ViewModel to launch UI-related coroutines?
<ol type="a">
  <li>mainScope</li>
  <li>viewModelScope</li>
  <li>uiScope</li>
  <li>It’s not recommended to start coroutines from the main thread.</li>
</ol>

**Answer: B**

## To specify where a coroutine should run, which of the following are the three predefined dispatchers you can choose from?
Choose as many answers as you see fit.

<ol type="a">
  <li>Dispatchers.Background</li>
  <li>Dispatchers.Default</li>
  <li>Dispatchers.IO</li>
  <li>Dispatchers.Main</li>
  <li>Dispatchers.Network</li>
</ol>
**Answer: B,C,D**

## For testing coroutines, which of the following statements are true about the runBlockingTest function?
Choose as many answers as you see fit.

<ol type="a">
  <li>It blocks until the coroutine started by runBlockingTest finishes.</li>
  <li>It's a non-blocking call.</li>
  <li>It should be used in user-facing app code.</li>
  <li>It executes any suspending functions it calls immediately.</li>
  <li>It can be a flaky test depending on how long the coroutine takes.</li>
</ol>

**Answer: A,D**





















