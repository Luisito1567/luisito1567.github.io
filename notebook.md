## Table of Contents - [Vocab](#vocab)
- [Blocks](#blocks)
- [Concepts](#concepts)
- [Vocabulary](#vocabulary)
- [Code Examples](#code-examples)
  - [Print Statements](#print-statements)
- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)



- [Notebook Style Guide](#markdown-style-guide-for-coding-notebooks)

  - [Headings](#headings)

  - [Text Formatting](#text-formatting)
  - ## Code Examples
 
  ### Print Statements
  ```java
  public class Hello {
      public static void main(String[] args) {
          System.out.println("Hello World!");
      }
  }
  ```
  **System** accesses a Java class that's built into the language
  
  **out** is short for "output".
  
  **println** is short for "print line".
  ## Vocab
<details>
  <summary>algorithm</summary>
    Step-by-step instructions. 

<
 

<details>
  <summary>JAVA</summary>

  A programming language. Java and javascrip are complete different languages.
  
   <details> </details>
<summary>object oriented laguage </summary>
    Object-oriented progamming is a way of writting code where you group related data and actions into reusabel "objects" kind of like organizing tools into labeled boxes. 

<details>
  <summary>object oriented languages</summary>
    Object-oriented progamming is a way of writting code where you group related data and actions into reusabel "objects" kind of like organizing tools into labeled boxes. 

    <details>
  <summary>procedural languages</summary>
   procedural languages focuse on proceduers (functions) that operate on data in a linear top-down sequence. 

<details>
  <summary>class</summary>
   in java, a class is like a buleprint that defines the structure and behavior ( data and actions) of objects you can create from it. 

<details>
  <summary>meathod</summary>
    A method in Java is a block of code inside a class that preforms a specific task when it's called. 

<details>
  <summary>console</summary>
    The area of a computer that notes from a program can be printed to. Kind of like a notbook. 

<details>
  <summary>varibles</summary>
  A variable is like that box that holds information you want.

<details>
  <summary>strings</summary>
  A string is a set of words or number that are surrounded by quotation marks ," here is 1 string,"  
























































































































VR Robot + Playground	VR Robot, PlaygroundThe VR Robot is the virtual device you program, while the Playground is the 3D grid map where it moves and completes challenges
Programming Language + Project	Programming Language, Project The Programming Language is the set of rules (Blocks or Python) you use to write instructions, which are saved together as a Project.
Behavior + Command	Behavior, Command/ A Behavior is an action the robot performs, which is triggered by a specific line of code called a Command.
Drivetrain	Drivetrain This is the group of motors and wheels that allows the robot to drive forward, reverse, and turn around the playground.
Loop + Iteration	Loop, Iteration A Loop is a control structure that repeats a set of commands, and each individual repeat is called an Iteration.
Sensor + Bumper Sensor	Sensor, Bumper Sensor A Sensor gathers data from the environment, and the Bumper Sensor specifically detects physical impacts when the robot crashes into a wall or object.
Boolean + Condition + TRUE/FALSE	Boolean, Condition, TRUE, FALSEA Condition is a statement checked by the robot that results in a Boolean value, which can only be TRUE or FALSE.
Distance Sensor + Threshold	Distance Sensor, ThresholdThe Distance Sensor measures how far away an object is using laser light, while a Threshold is the limit value used to decide if an object is too close.
Coordinate Plane + X/Y Coordinates	The Coordinate Plane is the full grid layout of the playground, where X/Y Coordinates pinpoint the exact horizontal and vertical location of the robot.
Location Sensor This internal sensor reads the robot's exact X and Y grid coordinates and tracks its current heading angle.
Comment	This is a note written inside the code to help humans understand what the program does, which the robot completely ignores when running.
Eye Sensor This sensor can detect if an object is present and identify its specific color (like red, green, blue, or none).
Conditional Statement This is an "If-Then" structure that instructs the robot to execute certain commands only if a specific condition is true.


Sequence	the order matters because it a list of what to do step by step.
Parameters: These are the changeable values inside a block—like distance or speed numbers—that alter exactly how the robot executes that command.
Loops / Iteration: This is a control structure used to repeat a set of programming blocks multiple times without rewriting them.
Sensors: These are the hardware components—like the eye, bumper, or distance sensors—that let the virtual robot gather data from its playground.
Booleans & Conditions: This is binary information that evaluates to either TRUE or FALSE to help the robot make decisions.
Sense  Think Act: This is the continuous cycle where a robot collects sensor data, decides what to do, and then moves or reacts.
Comparisons: These are math symbols like < or > used to check if a sensor value is greater than or less than a specific target.
Coordinates: These are the X and Y grid numbers that tell you exactly where the robot is located on the playground map.
Conditionals: These are "If... Then... Else" logic blocks that guide the robot down different paths depending on whether a rule is met.
Patterns: This means finding repetitive behaviors or layouts in a challenge so you can write a cleaner, more efficient algorithm





Hat blocks-special event-handling block with a curved or flat top that starts a stack of code
 
 Stack / Command Block -connect vertically attaching above or below other stack blocks to execute instructions sequentially from top to bottom
 
  C-Block -it acts as a container or wrapper to loop actions or check conditions
 
  Reporter / Oval Block-reports specific data values like numbers or text (such as sensor measurements or variable data)
 
  Boolean / Hexagonal Block-reports a condition as either true or false
 
  Repeat Block-loops a set of commands a specific number of times before moving to the next blocka1
 
  Wait Until-pauses/ the execution of your project stack
 
  If Then Block/ the robot runs the code inside the block
 
  Forever Block- to make robots run continuous behaviors, like checking sensors or driving, without stopping until the program ends

 ## Blocks

## Concepts

## Vocabulary

- ## Markdown Style Guide for Coding Notebooks

Follow this guide to keep your coding notebook **clear, consistent, and professional**.  

This ensures your notes are easy for you (and others) to read later.

---

## Headings

**When to use:** Organize your notebook into sections (like days, topics, or projects).  

- `#` for the notebook title (use once at the top).  

- `##` for each day or major topic.  

- `###` for subsections (like "Notes", "Practice", "Reflections").  

# Example:

# My Coding Notebook

## Day 1

### Notes

### Practice

# Text Formatting

When to use: Highlight important ideas or add emphasis.

Use bold for key terms or definitions.

Use italic for emphasis or side comments.

Use inline code for keywords, functions, or commands.

 

# Example:

**Class** = a blueprint for objects  

*Remember:* always test your code  

Use `System.out.println()` to print

 

# Code Blocks

When to use: Anytime you write multiple lines of code.

Inline code for short snippets.

Fenced code blocks with language for full examples.

# Example:

```java

public class Hello {

    public static void main(String[] args) {

        System.out.println("Hello World!");

    }

}

```

# Lists

When to use: Organize steps, notes, or key points.

Numbered lists for sequences or steps.

Bulleted lists for unordered ideas.

# Example:

Define the class
Write the main method
Test your program
Variables

- Loops

- Conditionals

 

# Checklists

When to use: Track progress on assignments or tasks.

# Example:

[x] Complete coding warm-up

- [ ] Finish project draft

- [ ] Reflect on learning

 

# Blockquotes

When to use: Call out notes, reminders, or teacher comments.

# Example:

> 💡 Remember: Loops repeat code until a condition is false.

 

# Tables

When to use: Compare values, track progress, or organize data neatly.

# Example:

| Task        | Status   | Notes          |

|--------------|------------|-----------------| 

| Homework 1  | Done #  | Submitted      |

| Homework 2  | Pending  | Needs review   |

 

# Links & Images

When to use: Add references, resources, or visuals.

# Example:

[Java Docs](https://docs.oracle.com/javase/8/docs/api/)  

![Markdown Logo](https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg)

To make an image that is a link, paste the image, then add the following before it, replacing website address with the link:

<a href="website address">

And after the image info, add: </a>

# Collapsible Sections

When to use: Hide solutions, extended notes, or extra details.

# Example:

<details>

  <summary>Click to reveal solution</summary>

  

System.out.println("Answer: 42");

</details>

 

# Footnotes

When to use: Add references or side notes without cluttering the page.

# Example:

This concept is related to object-oriented programming.[^1]

[^1]: See "Objects and Classes" in your textbook.

 

# Style Rules

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

 

# Bottom Line:

Headings = Structure

Bold/Italic = Emphasis

Code blocks = Code

Lists = Steps/Ideas

Tables = Organization

Checklists = Progress

Blockquotes = Notes/Tips

Collapsible = Hide/Show detail

Keep it simple, consistent, and clear.
