# My Coding Notebook

## Table of Contents

- [Flutter Notes](#flutter-notes)
  - [What is Flutter?](#what-is-flutter)
  - [Practice](#practice)
  - [Layout and Design Widgets](layout_and_design_widgets)
  - [Definitions with Structures](#flutter-definitions-with-structures)
  - [Code Definitions](#code_definitions)
- [Key Notes and Definitions](#key-notes-and-definitions)

## Flutter Notes

| Term | Definition and Description | Base Structure | Real Life Example | App Example |
|------|----------------------------|----------------|-------------------|-------------|
|Main| A function that runs when your app starts. It tells Flutter what app to show. | `void main() => runApp(MyApp());` |  |  |
|MaterialApp| The widget that sets up your whole app’s look and navigation. | `MaterialApp(...)` |  |  |
|Scaffold| A widget that gives you the basic layout: background, navigation bar, floating button, etc. | `Scaffold(...)` |  |in showcase.dart return Scaffold( body: Column( mainAxisAlignment: MainAxisAlignment.start, children: [|
|Column| A widget that holds and displays your content in a straight line from top to bottom. | `Column(...)` |  |  |
|Row| A widget that shows things side-by-side. | `Row(...)` |  |  |
|Conatainer| A box that holds other widgets. You can add color, padding, borders, or size. | `Container(...)` |  |  |
|Text| A widget to display text on the screen. | `Text('Hello')` |  |  |
|Image.network| A widget to show an image using a link from the internet. | `Image.network('https://...')` |  |  |
|ElevatedButton| A clickable button that floats above content. You choose what happens when it's clicked. | `ElevatedButton(onPressed: ..., child: ...)` |  |  |
|onPressed| The code that gets run when a button is tapped or something happens. | `onPressed: () => doSomething()` |  |  |
|StatelessWidget| A class that creates widgets that never change. Good for static screens. | `class HomeScreen extends StatelessWidget` |  |  |
|StatefulWidget| A class for widgets that can change while the app is running. | `class MyWidget extends StatefulWidget` |  |  |
|Navigator| Lets you move from one screen to another using route names. | `Navigator.pushNamed(context, '/about')` |  |  |
|Padding| Makes space around a widget inside its container. | `Padding(padding: EdgeInsets.all(8.0), child: ...)` |  |  |
|Center| Aligns content in the center of the screen or container. | `Center(child: ...)` |  |  |
|Wrap| Automatically puts widgets onto a new line when there's no space. | `Wrap(children: [...])` |  |  |
|@overide| This marks a method as one that’s replacing a method in a parent class. | `@override` |  |  |
|Build| The special function in every widget that describes what gets drawn on the screen. | `Widget build(BuildContext context) {...}` |  |  |
|Build| Required in every widget class to describe what to show. | `build` |  |  |
|BuildContext| A variable that helps the widget know where it is and lets it communicate with the app. | `BuildContext context` |  |  |
|super.key| A keyword used to pass a value to the parent widget. | `super.key` |  |  |
|const| A keyword that means the value won't change and is set once. | `const` |  |  |
|Scanner | Creates a scanner object to take input from user  | Scanner in = new Scanner(System.in); |  |  |
| important Scanner | Gies access to Scanner class, required at top | import java.util.Scanner; |  |  |
| print line statement | prints what's in the parentesis, adds line after | System.out.println("");  |  |  |
| print statement | prints the content in the parentesis | System.out.print(""); |  |  |
| Overloaded method/function or constructor | Uses the same ame, but has different parametrs | Pizza(), Pizza(String toppigs) 2 constructors, first is a default cheese pizza, 2nd has 1 topping |  |  |
| dot notation |



<img width="1381" height="721" alt="image" src="https://github.com/user-attachments/assets/ffa7aa92-7299-4e93-abfe-bd20465cec27" />








### What is Flutter?
- Definition: A Firebase made by Google for building that work on web, Android, and IOS - with one codebase.
- Why is it useful? If you build the app once and optimize it for all devices and operating systems, it can save time and money as well

---

### Key Notes and Definitions

| Term             | Definition                                      | Example / Notes                          |
|------------------|--------------------------------------------------|-------------------------------------------|
| Widget           |                                                  |                                           |
| MaterialApp      |                                                  |                                           |
| Scaffold         |                                                  |                                           |
| StatelessWidget  |                                                  |                                           |
| StatefulWidget   |                                                  |                                           |
| Navigator        |                                                  |                                           |
| AppBar           |                                                  |                                           |
| Column           |                                                  |                                           |
| Row              |                                                  |                                           |
| Container        |                                                  |                                           |
| Text             |                                                  |                                           |
| Image.network    |                                                  |                                           |

---

### 🎨 Layout and Design Widgets
- How do you center a widget?
- How do you align something to the left or right?
- What widget adds space around content?




| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |
|------|------------|--------------------------|-------------------|-------------|
| Sequencing | Define an order for when steps in an algorithm are completed | Follows 1, 2, 3 | which step comes first in making a grilled cheese | Get bread, add butter, add cheese |
| Algorithms | Define step by step processes to follow when completing a task or solving a problem | no syntax | Make a grilled cheese | Verify user |
|Variable| A named container used to store a value that may change. | `var x = 5;` |Username is Chapin  |App example later  |
|Constant| A fixed value that cannot change once set. | `const PI = 3.14;` |  |  |
|Data Type| The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` |Objectives|  |
|String| A sequence of characters used to represent words or text. | `"Hello World"` |  |  |
|Integer| Whole number values. | `int age = 16;` |Streak numbers|  |
|Double| Number values with decimals. | `double age = 16.2;` |Math|  |
|Boolean| A value that can be true or false. | `bool isLoggedIn = false;` |Pop-ups|  |
|List| A collection of values in a specific order. | `List<String> names = [];` |Organization|  |
|Null| A special value that means “nothing.” | `String? name = null;` |No value, Unfinished loading|  |
|Funtion| A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` |  |  |
|Parameter| The information passed into a function to change how it works. | `greet(String name)` |  |  |
|Return| The result a function gives back. | `return total;` |  |  |
|Scope| Where a variable or function can be used. | (No set syntax — concept-based) |  |  |
|Class| Blueprint for creating objects with specific structure and behavior. | `class Dog {}` |  |  |
|Object| A specific version of a class. | `Dog myDog = Dog();` |  |  |
|Property| A variable that belongs to a class/object. | `String name;` |  |  |
|Method| A function that belongs to a class. | `void bark() {}` |  |  |
|Constructor| A special function used to set up a class when it’s created. | `Dog(this.name);` |  |  |
|Abstraction| Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) |  |  |
|Overide| Changing how a built-in or inherited function behaves. | `@override` |  |  |
|Void| A function that does not return a value. | `void printMessage() {}` |  |  |
|index| location value of each character in a String or list, starting at 0 | "Hello index of 'e' is 1 |  |  |
| Substring | Part of a longer String | "llo" is a sbString of "Hello" |  |  |







[String notes](#string-notes)
### String Notes
 - Strings have indices (plural for index,) which start at 0. "Hello" has indices 0(H) 1(e) 2(1) 3(1) 4(o)
 - Final index in a String length is -1


### String Methods Table


<img width="1208" height="401" alt="image" src="https://github.com/user-attachments/assets/6b2344c3-a939-4693-b010-0f29e4ae7ba0" />




[Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)
## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  
This ensures your notes are easy for you (and others) to read later.

---

## 🔹 Headings
**When to use:** Organize your notebook into sections (like days, topics, or projects).  
- `#` for the notebook title (use once at the top).  
- `##` for each day or major topic.  
- `###` for subsections (like "Notes", "Practice", "Reflections").  

✅ Example:


# My Coding Notebook
## Day 1
### Notes
### Practice

🔡 Text Formatting
When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.

 

✅ Example:

**Class** = a blueprint for objects  
*Remember:* always test your code  
Use `System.out.println()` to print

 

💻 Code Blocks
When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

✅ Example:

```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

🧾 Lists
When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

✅ Example:

1. Define the class
2. Write the main method
3. Test your program

Variables
- Loops
- Conditionals
 

✅ Checklists
When to use: Track progress on assignments or tasks.

✅ Example:

[x] Complete coding warm-up
- [ ] Finish project draft
- [ ] Reflect on learning

 

➡️ Blockquotes
When to use: Call out notes, reminders, or teacher comments.

✅ Example:

> 💡 Remember: Loops repeat code until a condition is false.

 

📊 Tables
When to use: Compare values, track progress, or organize data neatly.

✅ Example:

| Task        | Status   | Notes          |
|-------------|----------|----------------|
| Homework 1  | Done ✅  | Submitted      |
| Homework 2  | Pending  | Needs review   |

 

🔗 Links & Images
When to use: Add references, resources, or visuals.

✅ Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  
![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

 

📂 Collapsible Sections
When to use: Hide solutions, extended notes, or extra details.

✅ Example:

<details>
  <summary>Click to reveal solution</summary>
  
System.out.println("Answer: 42");

</details>

 

📝 Footnotes
When to use: Add references or side notes without cluttering the page.

✅ Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.

 

🎯 Style Rules
Consistency matters more than creativity

Always use headings to structure your notes.

Always use code blocks for multi-line code.

Clarity first

Bold key terms.

Use lists instead of long sentences when outlining steps.

Professional tone

Don’t mix casual notes with formal work in the same section.

Use blockquotes for reflections or teacher feedback.

Track your learning

Use checklists to mark what’s done.

Use collapsible sections if you want to hide answers until review time.

 

✅ Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.
