# Question list: view basic
## Select all answers that are true for this XML layout when displayed on the screen.
Choose as many answers as you see fit.
```
<androidx.constraintlayout.widget.ConstraintLayout
    android:layout_width="match_parent"
    android:layout_height="match_parent">
    <TextView
        android:id="@+id/textViewA"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="A"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
    <TextView
        android:id="@+id/textViewB"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="B"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
</androidx.constraintlayout.widget.ConstraintLayout>
```

<ol type="a">
  <li>TextView A appears vertically stacked on top of TextView B.</li>
  <li>The starting edge of TextView A is aligned to the starting edge of the parent view.</li>
  <li>The starting edge of TextView B is aligned to the starting edge of the parent view.</li>
  <li>TextView B is horizontally and vertically centered within the parent.</li>
  <li>The tops of TextView A and TextView B are aligned to top of the parent view.</li>
  <li>The width of TextView A matches the width of the parent ConstraintLayout.</li>
</ol>

**Answer: B,E**

## Which line(s) of XML code will produce an error?
```
   <TextView
2        android:layout_width="wrap_content"
3        android:layout_height"wrap_content"
4        android:padding="8dp"
5        android:text="@string/title"
6        android:textSize=18sp />
```
Choose as many answers as you see fit.

<ol type="a">
  <li>Line 1 - Missing closing tag > after <TextView.</li>
  <li>Line 3 - Missing = symbol after android:layout_height attribute.</li>
  <li>Line 4 - The android:padding attribute does not exist for a TextView.</li>
  <li>Line 5 - You should use @str/title to refer to a string resource.</li>
  <li>Line 6 - Missing quotations around the attribute value 18sp.</li>
</ol>

**Answer: A,E**

## Which of the following statements about app icons are true?
Choose as many answers as you see fit.

<ol type="a">
  <li>It is sufficient to provide a single bitmap image of your app icon in your project to make it appear high quality on a range of Android devices.</li>
  <li>mdpi, hdpi, xhdpi, xxhdpi, and xxxhdpi are density qualifiers for resource directories to indicate that these are resources to be used on devices with a specific screen density.</li>
  <li>Adaptive icons are made up of a foreground and background layer, and an OEM mask will be applied on top of them.</li>
  <li>Vector drawables only work for a certain screen density and should not be scaled.</li>
</ol>

**Answer: B,C**

## Which of the below steps are part of changing the color of your app theme?
Choose as many answers as you see fit.

<ol type="a">
  <li>Modify the themes.xml (night) file.</li>
  <li>Set the primary and secondary color theme attributes of your app theme.</li>
  <li>Define the colors used in your app as color resources in the colors.xml file.</li>
  <li>Set the background color of your app in the activity's layout file.</li>
  <li>Set the color attribute on all your UI components.</li>
  <li>Change the name of your theme to your preferred color.</li>
</ol>

**Answer: A,B,C**

## Why use the Material Components for Android library?
Choose as many answers as you see fit.

<ol type="a">
  <li>It provides widgets that follow the Material Design guidelines such as text fields and switches.</li>
  <li>It provides default Material themes that you can use directly or extend and then customize.</li>
  <li>It automatically suggests ways for your app to look better.</li>
  <li>It helps you more quickly build beautiful user experiences.</li>
</ol>

**Answer: A,B,D**

## Why does a RecyclerView need an Adapter?
<ol type="a">
  <li>To adapt data to display on a specific device type</li>
  <li>To create a new ViewGroup</li>
  <li>To adapt data from a data source into JSON.</li>
  <li>To create new ViewHolders and bind data to them.</li>
</ol>

**Answer:D**

## Which of the following are advantages to using RecyclerView?
Choose as many answers as you see fit.
<ol type="a">
  <li>RecyclerView comes with built-in layout managers.</li>
  <li>RecyclerView lets you use packages to organize your code.</li>
  <li>RecyclerView helps save processing time, which can help scrolling through a list smoother.</li>
  <li>RecyclerView is designed to be efficient for lists by reusing views that have scrolled off the screen.</li>
  <li>RecyclerView automatically incorporates Material Design components.</li>

</ol>

**Answer:A,C,D**
















