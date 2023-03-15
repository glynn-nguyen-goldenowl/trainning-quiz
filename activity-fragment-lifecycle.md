# Question list about: activity's & fragment's lifecycle

## If you open an app, and then leave the app using the back button, in which order were the following activity lifecycle methods called?

<ol type="a">
  <li>onStart(), onCreate(), onDestroy(), onStop()</li>
  <li>onDestroy(), onStart(), onCreate(), onStop()</li>
  <li>onCreate(), onStart(), onStop(), onDestroy()</li>
  <li>onStart(), onCreate(), onStop(), onDestroy()</li>
</ol>

**Answer: C**

## Which activity lifecycle method would be called if a dialog appears onscreen, partially obscuring an activity?


<ol type="a">
  <li>onPause() because the activity is still displayed, but no longer has focus.</li>
  <li>onStop() because the activity does not need to respond to user input while the dialog is onscreen.</li>
  <li>onResume() because the activity needed to respond to user input to display the dialog.</li>
  <li>onDestroy() because the activity does not need to exist so long as it doesn’t have focus.</li>
</ol>

**Answer: A**

## Which of the following is true about the lifecycle of a single activity?
Choose as many answers as you see fit.

<ol type="a">
  <li>onStart() can be called multiple times, while onCreate() can only be called once.</li>
  <li>onStop() can be called multiple times, while onPause() can only be called once.</li>
  <li>onDestroy() is called when the app enters the background.</li>
  <li>onResume() is called when the activity gains focus.</li>
</ol>

**Answer: A, D**

## An activity contains the following code in onCreate(). What will happen when this code is executed, if the intent property is null?
```
val message = intent.extras?.getString("message"
).toString()
```

<ol type="a">
  <li>The app will crash because it attempted to access the extras property on a null object.</li>
  <li>The app will crash because it attempted to access a null object.</li>
  <li>The app will not crash because the extras property is accessed unsafely using ?.</li>
  <li>The app will not crash because the extras property is accessed safely using ?.</li>
</ol>

**Answer: B**

## Which of the following tasks can be performed in onCreate()?
Choose as many answers as you see fit.

<ol type="a">
  <li>Configuring views, such as setting the layout manager of a recycler view.</li>
  <li>Determining the items to be shown in the options menu.</li>
  <li>Setting the onClickListener for items in the options menu.</li>
  <li>Getting extras from the intent that launched the activity.</li>
</ol>

**Answer: A, D**

## In which method should you handle what happens when a button in the app bar is pressed?
<ol type="a">
  <li>onCreateOptionsMenu()</li>
  <li>openOptionsMenu()</li>
  <li>onOptionsItemSelected()</li>
  <li>onPrepareOptionsMenu()</li>
</ol>

**Answer: C**

## Which of the following is false about intents?

<ol type="a">
  <li>Both implicit and explicit intents allow your app to launch another activity.</li>
  <li>Explicit intents require you to specify the class of the activity you want to show.</li>
  <li>Intents are performed using the startActivity() method.</li>
  <li>An implicit intent always results in the system asking the user which app to open.</li>
</ol>

**Answer: D**























