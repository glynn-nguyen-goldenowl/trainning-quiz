# Question list about: Kotlin language
## What is a program?
<ol type="a">
  <li>A specific task</li>
  <li>A tool that helps you write Kotlin code</li>
  <li>A series of instructions that a computer system executes to accomplish some action</li>
  <li>A defined set of instructions that tells your computer to print “Happy Birthday!”</li>
</ol>

**Answer: C**

## Which keyword do you use to define a function in Kotlin?
<ol type="a">
  <li>fun</li>
  <li>func</li>
  <li>function</li>
  <li>main</li>
</ol>

**Answer: A**

## Which of the following do you need to create a Kotlin program that prints a line of text? 
(Choose as many answers as you see fit.)
<ol type="a">
  <li>comment describing what your program does</li>
  <li>a main() function</li>
  <li>curly braces {} around the instructions to the system</li>
  <li>a call to print() or println()</li>
  <li>a repeat() statement</li>
</ol>

**Answer: B,C,D**

## What do you expect this Kotlin code to do?
```
fun main(args: Array<String>) {
  println("Hello, world!")
  println("It's a sunny and warm day!")
}
```

<ol type="a">
  <li>Print one line of text</li>
  <li>Print two lines of text</li>
  <li>Print three lines of text</li>
  <li>Print two lines of text separated by a blank line</li>
</ol>

**Answer: B**
## How would you modify this main() function so that it prints a 6-layer cake for someone's 4th birthday?
```
fun main() {
  val age = 24
  val layers = 5
  printCakeCandles(age)
  printCakeTop(age)
  printCakeBottom(age, layers)
}
```

<ol type="a">
  <li>Set val age to 6, set val layers to 4</li>
  <li>Set val age to "4", set val layers to "6"</li>
  <li>Set val age to 4, set val layers to 6</li>
  <li>Leave the code as-is</li>
</ol>

**Answer: C**

## Which of these options correctly calls the function, below, and passes it valid input arguments?
```
fun createMessage(name: String, location: String, age: Int) {
  println("My name is ${name}. I am from ${location}, and I am ${age} years old.")
}
```

<ol type="a">
  <li>createMessage("Amy", "Australia", 20)</li>
  <li>createMessage("Evan", England, 9)</li>
  <li>createmessage("Tom", "Thailand", “40”)</li>
  <li>createMessage(Heather, “Haiti”, 7)</li>
</ol>

**Answer: A**

## Which of the following is false about collections and higher order functions in Kotlin?

<ol type="a">
  <li>Lists, maps, and sets can all use higher order functions.</li>
  <li>Lists are unordered, while maps and sets are ordered data types.</li>
  <li>Like the elements in a set, the keys in a map must be unique. However, multiple keys can map to the same value.</li>
  <li>Higher order functions such as map and filter can take lambda functions as parameters.</li>
</ol>

**Answer: B**

## Given the following code, what is the result of oneWordCities[1]?
```
val cities = listOf("Jeddah", "Bengaluru", "Shenzhen", "Abu Dhabi", "Mountain View", "Tripoli", "Bengaluru", "Lima", "Mandalay", "Tripoli")
val oneWordCities = cities.toSet().toList().filter { !it.contains(" ")}.sorted()
```

<ol type="a">
  <li>Tripoli</li>
  <li>Abu Dhabi</li>
  <li>Jeddah</li>
  <li>Bengaluru</li>
</ol>

**Answer: C**

