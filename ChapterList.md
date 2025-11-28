# Microsoft Visual C# Step by Step – Code Samples Overview

The sample code is organised by chapter under:

`Visual CSharp Step By Step/Chapter N/`

Most chapters contain one or more Visual Studio solutions, often in both a working and a “- Complete” version.

---

## Chapter 1 – Welcome to C#

**Folder:** `Chapter 1`

- `TextHello - Complete` – Console “Hello” app; your very first C# program.   
- `WPFHello - Complete` – Simple WPF window that greets the user; introduces XAML, controls, and events.   

---

## Chapter 2 – Working with Variables, Operators, and Expressions

**Folder:** `Chapter 2`

- `PrimitiveDataTypes` / `PrimitiveDataTypes - Complete` – Declaring variables of each primitive type and displaying their values.   
- `MathsOperators` – Using arithmetic operators (`+ - * / %`) in simple calculations.   

---

## Chapter 3 – Writing Methods and Applying Scope

**Folder:** `Chapter 3`

- `Methods` – Refactors the earlier examples to show how methods structure code.   
- `DailyRate` / `DailyRate - Complete` – Writing and calling your own methods and stepping through them in the debugger.   
- `DailyRate Using Optional Parameters` (and `- Complete`) – Variant using optional parameters for cleaner method calls.

---

## Chapter 4 – Using Decision Statements

**Folder:** `Chapter 4`

- `Selection` / `Selection - Complete` – Using `if`/`else` chains to implement multi-branch logic (e.g., comparing dates).   
- `SwitchStatement` / `SwitchStatement - Complete` – Using `switch` to convert characters to their XML representations.   

---

## Chapter 5 – Using Compound Assignment and Iteration Statements

**Folder:** `Chapter 5`

- `WhileStatement` / `WhileStatement - Complete` – Reading a text file line by line with a `while` loop and displaying the contents.   
- `DoStatement` / `DoStatement - Complete` – Converting a decimal number to octal using a `do` loop.   

---

## Chapter 6 – Managing Errors and Exceptions

**Folder:** `Chapter 6`

- `MathsOperators` / `MathsOperators - Complete` – Reuses the arithmetic example to demonstrate exceptions, `try/catch`, `checked`, `finally`, and more robust error handling.   

---

## Chapter 7 – Creating and Managing Classes and Objects

**Folder:** `Chapter 7`

- `Classes` / `Classes - Complete` – Defining your own classes, constructors, fields, static members, and creating instances with `new`.   

---

## Chapter 8 – Understanding Values and References

**Folder:** `Chapter 8`

- `Parameters` / `Parameters - Complete` – Demonstrates value vs reference parameters and the use of `ref` and `out`.   

---

## Chapter 9 – Creating Value Types with Enumerations and Structures

**Folder:** `Chapter 9`

- `StructsAndEnums` / `StructsAndEnums - Complete` – Uses a `struct` to represent calendar dates and introduces enums.   

---

## Chapter 10 – Using Arrays and Collections

**Folder:** `Chapter 10`

- `Cards Using Arrays` (and `- Complete`) – Card-hand example built on arrays to hold and manipulate a hand of cards.  
- `Cards Using Collections` (and `- Complete`) – Variant that uses `ArrayList` / collections to group and manage cards.   

---

## Chapter 11 – Understanding Parameter Arrays

**Folder:** `Chapter 11`

- `ParamsArray` / `ParamsArray - Complete` – Shows the `params` keyword to create a method that accepts a variable number of `int` arguments.   

---

## Chapter 12 – Working with Inheritance

**Folder:** `Chapter 12`

- `Vehicles` / `Vehicles - Complete` – Simple vehicle class hierarchy demonstrating base/derived classes and virtual methods.   
- `ExtensionMethod` / `ExtensionMethod - Complete` – Adds an extension method to `int` to convert base-10 values to other bases.   

---

## Chapter 13 – Creating Interfaces and Defining Abstract Classes

**Folder:** `Chapter 13`

- `Drawing` / `Drawing - Complete` / `Drawing Using Interfaces - Complete` – Uses an interface/class hierarchy to “tokenize” input and demonstrate interfaces and abstract classes (mapping the `Tokenizer` example from the book).   

---

## Chapter 14 – Using Garbage Collection and Resource Management

**Folder:** `Chapter 14`

- `UsingStatement` / `UsingStatement - Complete` – Revisits earlier file I/O code and makes it exception-safe by using `using` blocks to ensure resources are released.   

---

## Chapter 15 – Implementing Properties to Access Fields

**Folder:** `Chapter 15`

- `WindowProperties` / `WindowProperties - Complete` – WPF window that shows its own size via properties, updating as the user resizes.   
- `AutomaticProperties` / `AutomaticProperties - Complete` – Demonstrates auto-implemented properties on a simple class.   

---

## Chapter 16 – Using Indexers

**Folder:** `Chapter 16`

- `Indexers` / `Indexers - Complete` – Implements an indexer to look up phone numbers by name and vice versa.   

---

## Chapter 17 – Interrupting Program Flow and Handling Events

**Folder:** `Chapter 17`

- `Clock Using Delegates - Complete` / `Clock Using Events - Complete` – Digital clock that first uses delegates, then is refactored to use events.   

---

## Chapter 18 – Introducing Generics

**Folder:** `Chapter 18`

- `BinaryTree - Complete` / `BinaryTreeTest - Complete` – Generic binary tree type-safe for any element type.   
- `BuildTree - Complete` – Generic methods that build trees from parameters of any type.   

---

## Chapter 19 – Enumerating Collections

**Folder:** `Chapter 19`

- `BinaryTree` / `BinaryTree - Complete` – Extends the generic tree to implement `IEnumerator<T>`.   
- `IteratorBinaryTree` / `IteratorBinaryTree - Complete` / `EnumeratorTest - Complete` – Uses iterators (`yield`) to generate an enumerator and demonstrates enumeration in practice.   

---

## Chapter 20 – Querying In-Memory Data by Using Query Expressions

**Folder:** `Chapter 20`

- `QueryBinaryTree` / `QueryBinaryTree - Complete` – LINQ queries over the generic binary tree to retrieve data with query expressions.   

---

## Chapter 21 – Operator Overloading

**Folder:** `Chapter 21`

- `ComplexNumbers` / `ComplexNumbers - Complete` – Implements structs (e.g., hours/minutes/seconds or complex numbers) with overloaded operators and conversion operators.   

---

## Chapter 22 – Introducing Windows Presentation Foundation

**Folder:** `Chapter 22`

- `BellRingers - Complete` – WPF app demonstrating styles, basic WPF controls, and data presentation.   

---

## Chapter 23 – Working with Menus and Dialog Boxes

**Folder:** `Chapter 23`

- `BellRingers` / `BellRingers - Complete` – Extends the BellRingers app with menus and pop-up dialogs to explore richer WPF UI features.   

---

## Chapter 24 – Performing Validation

**Folder:** `Chapter 24`

- `OrderTickets` / `OrderTickets - Complete` – WPF customer/order form showing validation rules and error feedback for user input. (This corresponds to the `CustomerDetails` validation example.)   

---

## Chapter 25 – Querying Information in a Database

**Folder:** `Chapter 25`

- `ReportOrders` – Uses ADO.NET to query the Northwind database and display order information.   
- `LINQOrders` – Uses LINQ-to-SQL / DLINQ to query the same data via entity classes.   

---

## Chapter 26 – Displaying and Editing Data by Using Data Binding

**Folder:** `Chapter 26`

- `Suppliers - Complete` – WPF app that uses LINQ-to-SQL entities and data binding to display, edit, insert, and delete Northwind product/supplier data.   

---

## Chapter 27 – Task-Based Asynchronous Programming (Samples)

**Folder:** `Chapter 27`

- `GraphDemo` variants (e.g., `GraphDemo Using Tasks`, `GraphDemo Using the Parallel Class`, `GraphDemo Canceling Tasks`, etc., all `- Complete`) – WPF graphing demos that show how to use `Task`, cancellation, and the `Parallel` class to run computations asynchronously and in parallel.

---

## Chapter 28 – Parallel Loops and PLINQ

**Folder:** `Chapter 28`

- `CalculatePI` / `CalculatePI - Complete` – Estimates π using parallel loops to demonstrate parallelization patterns.  
- `PLINQ` / `PLINQ - Complete` – Uses Parallel LINQ to perform data queries in parallel and compare with sequential LINQ.

---

## Chapter 29 – Services and Clients

**Folder:** `Chapter 29`

- `ProductInformationService - Complete` / `ProductDetailsService - Complete` – Service projects exposing product information operations.  
- `ProductClient` / `ProductClient - Complete` – Client application that calls the product services, illustrating service consumption and proxy use.

---

## Chapter 30 – (No Code Folder in Zip)

**Folder:** `Chapter 30`

- No sample project is included in this zip for Chapter 30; the material in the book focuses on creating and using a web service, and your own implementation will follow the chapter walkthrough.   

---

## Appendix – Language Interoperability

**Folder:** `Appendix`

- `PythonInteroperability` – Demonstrates calling C# from Python (and vice versa) using the Dynamic Language Runtime (DLR) style interoperability.  
- `RubyInteroperability` – Similar interoperability example using Ruby.  
- `CustomerDB.py` / `CustomerDB.rb` – Companion scripts used by the interoperability samples.

