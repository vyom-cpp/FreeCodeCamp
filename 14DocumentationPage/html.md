```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial scale="1.0">
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
<main id="main-doc">
  <section class="main-section" id="Introduction">
    <header>Introduction</header>
    <p>JavaScript is a cross-platform, object-oriented scripting language. It is a small and lightweight language. Inside a host environment (for example, a web browser), JavaScript can be connected to the objects of its environment to provide programmatic control over them.</p>
  </section>
  <section class="main-section" id="JavaScript_and_Java">
    <header>JavaScript and Java</header>
    <p>JavaScript and Java are similar in some ways but fundamentally different in some others. The JavaScript language resembles Java but does not have Java's static typing and strong type checking. JavaScript follows most Java expression syntax, naming conventions and basic control-flow constructs which was the reason why it was renamed from LiveScript to JavaScript.</p>
  </section>
  <section class="main-section" id="Hello_World">
    <header>Hello World</header>
    <p>To get started with writing JavaScript, open the Scratchpad and write your first "Hello world" JavaScript code:</p>
    <code>function greetMe(yourName) { alert("Hello " + yourName); }
greetMe("World");</code>
  </section>
  <section class="main-section" id="Variables">
    <header>Variables</header>
    <p>You use variables as symbolic names for values in your application. The names of variables, called identifiers, conform to certain rules.
<br/>
<br>
A JavaScript identifier must start with a letter, underscore (_), or dollar sign ($); subsequent characters can also be digits (0-9). Because JavaScript is case sensitive, letters include the characters "A" through "Z" (uppercase) and the characters "a" through "z" (lowercase).
<br/>
<br>
You can use ISO 8859-1 or Unicode letters such as å and ü in identifiers. You can also use the Unicode escape sequences as characters in identifiers. Some examples of legal names are Number_hits, temp99, and _name.</p>
  </section>
  <section class="main-section" id="Declaring_Variables">
    <header>Declaring Variables</header>
    <p>You can declare a variable in three ways:<br/><br>
    <code>var x = 42.</code>
With the keyword var. For example,</p>
<code>let y = 13.</code>
  </section>
  <section class="main-section" id="Variable_Scope">
    <header>Variable Scope</header>
    <p>When you declare a variable outside of any function, it is called a global variable, because it is available to any other code in the current document. When you declare a variable within a function, it is called a local variable, because it is available only within that function.</p>
    <code>if (true) { let y = 5; } console.log(y); // ReferenceError: y is
not defined</code>
  </section>
  <section class="main-section" id="Global_Variables">
    <header>Global Variables</header>
    <p>Global variables are in fact properties of the global object. In web pages the global object is window, so you can set and access global variables using the window.variable syntax.</p>
  </section>
  <section class="main-section" id="Constants">
    <header>Constants</header>
    <p>You can create a read-only, named constant with the const keyword. The syntax of a constant identifier is the same as for a variable identifier: it must start with a letter, underscore or dollar sign and can contain alphabetic, numeric, or underscore characters.</p>
    <code>const PI = 3.14;</code>
  </section>
  <section class="main-section" id="Data_Types">
    <header>Data Types</header>
    <p>The latest ECMAScript standard defines seven data types:</p>
    <li>Boolean. true and false.</li>
    <li>null. A special keyword denoting a null value. Because JavaScript is case-sensitive, null is not the same as Null, NULL, or any other variant.</li>
    <li>undefined. A top-level property whose value is undefined.</li>
    <li>Number. 42 or 3.14159.</li>
    <li>String. "Howdy"</li>
  </section>
  <section class="main-section" id="Reference">
    <header>Reference</header>
    <p>All the documentation in this page is taken from MDN</p>
  </section>
</main>
<nav id="navbar">
  <header>JS Documentation</header>
  <a href="#Introduction" class="nav-link">Introduction</a>
  <a href="#JavaScript_and_Java" class="nav-link">JavaScript and Java</a>
  <a href="#Hello_World" class="nav-link">Hello World</a>
  <a href="#Variables" class="nav-link">Variables</a>
  <a href="#Declaring_Variables" class="nav-link">Declaring Variables</a>
  <a href="#Variable_Scope" class="nav-link">Variable Scope</a>
  <a href="#Global_Variables" class="nav-link">Global Variables</a>
  <a href="#Constants" class="nav-link">Constants</a>
  <a href="#Data_Types" class="nav-link">Data Types</a>
  <a href="#Reference" class="nav-link">Reference</a>
</nav>
  </body>
</html>
```