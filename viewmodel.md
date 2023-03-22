# Question list about: Jetpack viewmodel
## Which of the following are reasons to use a ViewModel?
Choose as many answers as you see fit.

<ol type="a">
  <li>A ViewModel and its data can survive orientation changes in an Activity/Fragment.</li>
  <li>A ViewModel allows you to separate code that updates the UI from code that doesn’t need to rely on the UI or its lifecycle.</li>
  <li>A ViewModel prevents your data from updating the UI automatically.</li>
</ol>

**Answer: A,B **

## A ViewModel is destroyed after which of the following ?
<ol type="a">
  <li>always after onStop</li>
  <li>always after onDestroy</li>
  <li>after onDestroy, if it not a configuration change.</li>
</ol>

**Answer: C**

## True or False: You should execute time-consuming tasks and I/O requests in your Activity/Fragment.
<ol type="a">
  <li>True</li>
  <li>False</li>
</ol>

**Answer: B**

## Why should you initialize and store LiveData in your ViewModel instead of a UI Controller?

<ol type="a">
  <li>Both the ViewModel and LiveData are lifecycle aware.</li>
  <li>To ensure that the LiveData isn’t destroyed when the UI Controller is destroyed.</li>
  <li>To hide or separate implementation details making your app more flexible.</li>
  <li>All of the above</li>
</ol>

**Answer: D**

## Which of the following allows you to use observe for changes?
<ol type="a">
  <li>a LiveData object</li>
  <li>any mutable object</li>
  <li>any property in a ViewModel</li>
  <li>any property in a ViewModel or LiveData object</li>
</ol>

**Answer: A**

## True or False: It’s OK for a ViewModel to directly reference a View or LifecycleOwner class.
<ol type="a">
  <li>True</li>
  <li>False</li>
</ol>

**Answer: B**

## True or False: You can use the same ViewModel for multiple Activities or Fragments to share data.

<ol type="a">
  <li>True</li>
  <li>False</li>
</ol>

**Answer: A**

## What is the correct way to access the shared view model using the Kotin property delegate approach?
<ol type="a">
  <li>val viewModel: OrderViewModel by viewModels()</li>
  <li>val viewModel: OrderViewModel by activityViewModels()</li>
  <li>val viewModel: OrderViewModel by sharedViewModels()</li>
  <li>val viewModel: OrderViewModel by fragmentViewModels()</li>
</ol>

**Answer: B**

## The ___ is the combination of UI elements and UI state.

<ol type="a">
  <li>ViewModel</li>
  <li>Architecture of an app</li>
  <li>UI</li>
  <li>Unidirectional Data Flow pattern</li>
</ol>

**Answer: C**

## Which of the following are Jetpack libraries that could be used in the data layer? Select all that apply.
Choose as many answers as you see fit.

<ol type="a">
  <li>Room</li>
  <li>ViewModel</li>
  <li>DataStore</li>
  <li>Navigation</li>
</ol>

**Answer: A,C **

## True or false? All UI events coming from the ViewModel should be modeled as state.
<ol type="a">
  <li>True</li>
  <li>False</li>
</ol>

**Answer: A**

## True or false? The UI behavior logic or UI logic should be present in ViewModels.

<ol type="a">
  <li>True</li>
  <li>False</li>
</ol>

**Answer: B**

## The ___ layer avoids code duplication and encourages splitting responsibility to avoid large classes.

<ol type="a">
  <li>UI</li>
  <li>Domain</li>
  <li>Data</li>
</ol>
**Answer: B**



























