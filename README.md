### يفترض في من يريد متابعة خارطة الطريق ان يكون خريج حاسبات او هندسة حاسبات او اي تخصص قام بشرح اساسيات علوم الكمبيوتر او دورة اوفلاين او اونلاين
### لكل من ليس له علاقة ب علوم الحاسب ويريد متابعة خارطة الطريق الرجاء اكمال دورة CS50 من جامعة هارفرد فهي تمثل تمهيد جيد للبدء في التراك

رابط الدورة:  [CS-50 Harvard](https://cs50.harvard.edu/x/2023/#welcome)<br>
رابط دورة : [Introduction To Programming MIT](https://ocw.mit.edu/courses/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/)

  ## الشهر الأول
```mermaid
graph LR
    A[1st Week االاسبوع الاول]--> B((Square Rect))
    B[2nd Week االاسبوع الثاني]--> C((Square Rect))
    C[3rd Week االاسبوع الثالث]--> D((Square Rect))
    D[4th Week االاسبوع الرابع]--> E((الاساس الاول))
```

```mermaid
timeline
    title  1st Week | الاسبوع الاول 
    Day1 : CSharp [001] Intro. to .NET
         : What is Full Stack Developer
         : Why .NET
         : Understanding .NET
         : What is Visual Studio
         : Install Visual Studio
         : Explore Visual Studio
         : Difference Between Solution & Project
         : Source Code Vs. Machine Code
         : Explore .csproj file
    Day2 : CSharp [002] Solution & Project
         : Adding Item to Solution
         : Application Vs Class Library
         : Referencing a project
         : Add Item to Project
         : Namespace Vs classes
         : Class per file / multiple class per file 
    Day3 : .NET CLI [001] Intro to DOTNET CLI
         : Overview .NET Framework
         : Where to execute CLI commands
         : Basic DOS Commands
         : dotnet Driver
         : dotnet options
         : dotnet commands
         : dotnet build
         : dotnet run
         : dotnet project to project reference
         : dotnet add solution
    Day4 : DOTNET CLI [002] Intro to VS. Code
         : Visual Studio Vs. VS Code
         : Install VS. Code
         : Installing Omnisharp Extension
    Day5 : CSharp [003] Variables 
         : Declaration
         : Assignment
         : Initialization
         : Numerical data types
         : String Data Type (essentials)
         : String Concatenation
         : var keyword and literal suffix
         : dynamic keyword
  Day6/7 : Revision | مراجعة
         : Do Example on Visual Studio
         : Do Example on VS.Code
         
```
###  الهدف من الاسبوع الاول
- التعرف منصة الدوت نت واصداراتها المختلفة
- كيفية تهيئة جهاز الكمبيوتر الخاص فيك للبدء في عمل تطبيقات دوت نت عليه
- التعامل مع بيئات التطوير
- كيفية عمل البرنامج والتعامل مع السوليوشن والمشروع باستخدم ال GUI و Command Line
- التعامل مع عناصر التطبيق
- عمل اول تطبيق باستخدام بيئات التطوير المختلقة (Visual Studio / VS. Code)
- الفرق بين الكود المصدري (Source Code) ولغة الالة (Machine Code)
- التعرف على مبادئ واساسيات المتغيرات والتعامل معها
- معرفة الفرق بين ال (namespace) و (class)

 ```mermaid
timeline
    title 2nd week | الاسبوع الثاني
    Day1 : CSharp [004] Boolean Types & Operators
         : Equality Operators
         : Comparison Operators
         : Conditional Operators
         : Short circuit & logical operators 
         : Ternary Operator
    Day2 : CSharp [005] Arrays in CSharp
         : What is an Array
         : How It's stored
         : Declaration One Dimension
         : Initialization One Dimension
         : Multi Dimensional Array
         : Jagged Array
         : Indices and Ranges
         : Bound Checking
    Day3 : CSharp [006] Expressions in C#
         : Expression Types
         : Binary Operators
         : Null Coalescing "??"
         : Null conditional "?."
         : Statement vs Statement blocks
         : statement Expression
         : Selection statement
         : Iterations
         : jump statements
    Day4 : Problem Solving 1
         : Simple calculator
         : Sum Array elements
         : Find Average of numbers
         : Find max number in array
         : Find Min Number in Array
    Day5 : Problem Solving 2
         : FizzBuzz
         : Reverse String
         : Valid Palindrome
  Day6/7 : Revision | مراجعة
         : Self Practice    
```
###  الهدف من الاسبوع الثاني
- التعامل مع (Logical Operators) و (Comparison Operators) و (ُEquality Operators)
- تطبيق ال Short Circuit evaluation
- التعامل مع Ternary Operator
- التعرف على المصفوفات (Array) والتعامل مع اشكالها المختلفة (Single/Multi Dimention & Jagged) واعدادها واستخدامها وتهيئتها
- التعامل مع Array Indexes & Array Ranges والتحقق من مدى المصفوفة.
- التعامل مع Selection Statement او ما يعرف بجمل الاختيار 
   1. جملة IF
   2. جملة If/Else
   3. جملة Switch
- التعامل مع Iteration Statement او ما يعرف بجمل التكرار
   1. جملة while    
   2. جملة do-while
   3. جملة for
   4. جملة foreach
- التعامل مع Jump Statement او ما يعرف بجمل القفز
   1. جملة break 
   2. جملة continue
   3. جملة goto
   4. جملة return
- حل 8 من المشاكل (Problem Solving Easy Task)  
   
 ```mermaid
timeline
    title 3nd week | الاسبوع الثالث
    Day1 : Grokking Algorithm Book Chapter 1
         : Introduction
         : Binary Search
         : Big O Notation
         : Sequential Search in CSharp  
         : Binary Search in CSharp  
    Day2 : Grokking Algorithm Book Chapter 2
         : How Memory works
         : Arrays
         : Inserting in the middle 
         : Deletion
         : Selection Sort 
    Day3 : Apply Grokking Algorithm Ch. 2 Code
         : How Memory works
         : Inserting in the middle of Array
         : Deletion from an index
         : Selection Sort in CSharp
         : Implement Selection Sort in CSharp
    Day4 : CSharp [007] Casting & Type Conversion
         : Data Types are objects
         : Implicit and Explicit Casting
         : Boxing and Unboxing
         : Parse() Method
         : TryParse() Method
         : Convert Class
         : BitConverter And Value Types
    Day5 : Problem Solving 1
         : Reverse Integer
         : Roman To Integer  
  Day6/7 : Revision
```
###  الهدف من الاسبوع الثالث
- الفهم الاساسي لأهمية علم الخوارزميات
- فهم مشكلة البحث بالطريقة البحث التسلسلي  Sequential Search والبحث الثنائي Binary Search
- فهم كيفية قياس Big O Notation لحساب وقت تنفيذ الخوارزمية
- تعلم كيفية تحويل البيانات Casting & Type Conversion
- تطبيق الامثلة الموجودة في اول فصلين من كتاب Grokking Algorithm
- حل 3 مشاكل من المستوى السهل 

 ```mermaid
timeline
    title 4th week | الاسبوع الرابع
    Day1 : CSharp [008] OOP - Fields
         : OOP What & Why and How? 
         : Example without OOP
         : Example with OOP
         : Class Vs. Object
    Day2 : OOP [001] Introduction
         : OOP [002] Procedural Vs. OOP
         : OOP [003] OOP Pillars
         : OOP [004] Class Data Structure
         : OOP [005] Access Modifiers
         : OOP [006] Class Members
         : OOP [007] Class Vs. Object
    Day3 : CSharp [009] OOP - Methods
         : Instance Vs. Static Member
         : Method Syntax
         : Caller Vs. Callee
         : Argument Vs. Parametewr
         : Pass By Value/Reference
         : Method Signature
         : Method Overloading
         : Expression Bodied Method
         : Local Method
         : Static Method 
    Day4 : CSharp [010] Constructors in C#
         : constructor What, Why and How 
         : this keyword
         : Add Constructor
         : Implicit Constructor
         : Overload Constructor
    Day5 : CSharp [011] Properties
         : Properties What, Why & How
         : Property Syntax
         : get, set accessors
         : Property and validation
         : Readonly property
         : Expression Bodied Property
         : Property Deep Dive
         : Automatic Property
  Day6/7 : Revision
```
###  الهدف من الاسبوع الرابع
- اهمية ال OOP
- الفرق بين البرمجة الاجرائية (Procedural) والبرمجة الشئيية (OOP)
- ما هو الكلاس (الفئة) وما هي مكوناته (Class Members)
- الفرق بين ال Class Vs. Object
- التعرف على المكونات التالية للكلاس
  1. الحقول والثوابت
  2. الدوال Methods
  3. الكونستركتر Constructor
  4. البروبرتي Property
- الفرق بين اعضاء الكلاس Instance و static


## الشهر الثاني
```mermaid
graph LR
    A[5th Week االاسبوع الخامس]--> B((Square Rect))
    B[6th Week االاسبوع السادس]--> C((Square Rect))
    C[7th Week االاسبوع السابع]--> D((Square Rect))
    D[8th Week االاسبوع الثامن]--> E((الاساس الثاني))
```

```mermaid
timeline
    title  5th Week | الاسبوع الخامس
    Day1 : CSharp [017] Nested Types
         : Why Nested types
         : Composite Relationship
         : Composite object initialization 
    Day2 : CSharp [018] Debugguing in C#
         : Error Types
         : Syntax Error
         : Runtime Error
         : Handling Exception
         : Logical Error
         : Debugger and tracing (Essentials
    Day3 : CSharp [019] Structs
         : Definition of struct 
         : Class Vs Struct
         : Mutable Vs. Immutable (essentials)
         : Readonly struct
         : DateTime struct  
    Day4 : Code Take away [003] Immutable Vs. Mutable Objects
         : Naive mutable class
         : Private setter
         : Immutable class read only properties
         : Immutable struct
         : Immutability PROS and CONS
         : Examples from dotnet
    Day5 : OOP [008] Reference Type Vs Value Type
         : Function Locals, Parameter
         : Value Type Vs. Reference Type
         : Reference types allocation
         : Garbage Collector
         : Nested Object Allocation
         : Stack vs. Heap
         : When to use (Struct/Class)
         : Value Type always on stack !!?
  Day6/7 : Revision
```
###  الهدف من الاسبوع الخامس
- الانواع المتداخلة (Nested Types)
- استكشاف الاخطاء ومعالجتها (Debugging and Tracing)
- التعرف على Struct
- الفرق بين (Reference Type) و (Value Type)
- الفرق بين (Immutable) و (Mutable)


```mermaid
timeline
    title  6th Week | الاسبوع السادس
    Day1 : CSharp [012] Indexers
         : Indexers What, Why and How
         : Single Dimensional Map
         : Multiple Dimensional Map
         : Validating Suduko Example
    Day2 : CSharp [013] Delegates
         : Delegates What, Why and How
         : Anonymus Delegate
         : Lambda Expression
         : Multicast Delegate
         : Report Example
    Day3 : CSharp [014] Events
         : Events What, Why and How
         : Events and Delegates
         : Event Declaration
         : Publish Event
         : Subscriber Vs. Publisher
         : Event Subscribe/Unsubscribe
         : Lambda Expression call backs
    Day4 : CSharp [015] Operator Overloading
         : Operator Overloading What, Why and How
         : Predefined Operator
         : Supported Operators
         : Operator Overloading Syntax
         : (In Pair) Operator Overloading Syntax
    Day5 : CSharp [016] Finalizers
         : Finalizers What, Why and How
         : Object scope
         : Garbage Collection
         : Explicit Vs. Implicit GC
         : GC.Collect() 
  Day6/7 : Revision | مراجعة  
```
###  الهدف من الاسبوع السادس
- التعرف على Class Members
  1. الفهارس Indexers
  2. الاحداث Events
  3. ال Operator Overloading
  4. ال Finalizers
- التعرف على Delegate

```mermaid
timeline
    title  7th Week | الاسبوع السابع 
    Day1 : OOP [003] OOP Pillars
         : OOP [009] Encapsulation
         : Encapsulation What, Why and How
         : Encapsulation using methods
         : Encapsulation using Properties
         : Encapsulation using readonly
    Day2 : CSharp [021] Inheritance
         : Inheritance What, Why and How
         : Abstract class
         : Sealed class
         : Virual Methods
         : Abstract Members
         : Sealed Members
         : Base Object class
         : Real world Example (Payroll)
    Day3 : CSharp [022] Interface
         : Interface What, Why and How
         : Abstract Vs. Concrete Types
         : Implicit Interface Implementation
         : Explicit Interface Implementation
         : Tight Vs. Loose Coupling
         : Real World Example       
    Day4 : OOP [010] Abstraction 
         : Abstraction What, Why and How
         : OOP [011] Polymorphism
         : Abstraction What, Why and How
    Day5 : OOP [012] Inheritance (Revisited) 
         : Inheritance What, Why and How 
  Day6/7 : Revision | مراجعة  
```
###  الهدف من الاسبوع السابع
- التعرف على اعمدة ال OOP
  1. ال Encapsulation
  2. ال Abstraction
  3. ال Polymorphism
  4. ال Inheritance
- التعرف على العديد من انواع الكلاس (Sealed, Abstract, Static)
- اعضاء الكلاس (sealed, virtual, abstract)
- التعرف على method overriding
- معرفة اساسيات الفرق بين Tight Vs. Loose Coupling
ٍ- التطبيق العملي لمسائل تلامس الواقع (نظام رواتب) ونظام (بنكي)
