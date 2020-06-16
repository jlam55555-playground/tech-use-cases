# tech-use-cases
Compilation of notes on different technologies

This is a living document, all paraphrased and my own impressions. Most of this has been inspired by a splurge on Pluralsight videos on a variety of topics. It's very scattered right now, and mostly here to organize my thoughts.

|Name|Categories|Description|Use cases/Benefits/Features|
|---|---|---|---|
|Angular (2+)|Front-end web application framework|Popular MVVM framework based largely around modules, services, components|Large community and support; built-in reactivity, testing libraries, many convenience modules; TypeScript enabled and ES6 modules; Angular modules allow for modular design, lazy-loading, tree-shaking, importing (separately-compiled) third-party libraries; convenient CLI|
|Angular Material|Front-end UI framework, angular library|HTML/CSS/JS library for Angular following the Material style guide|Used as the official model for Material style; good documentation; very sleek and modern; comes with many flex utilities; directives, components, (S)CSS classes; requires a bit more setup than Bootstrap, a higher learning curve, and more custom CSS|
|Ansible|Automation/ deployment tool|Comes with many modules to run tasks and the inherent ability to distribute to an "inventory" of (remote) hosts|Large module library; detecting changes and hooks; vaults for sensitive files|
|Bootstrap|Front-end UI framework|HTML/CSS/JS library for easily creating consistent UI styles|Smaller learning curve than Angular Material; almost all work done by CSS classes, very little need to write custom CSS classes, HTML, or JS|
|Groovy|JVM GPL|A dynamic JVM language with a flexible, Ruby-like syntax and the ability to interface directly with Java libraries|metaprogramming allows for use as a DSL (notable examples include Gradle and Ansible); dynamic nature allows for easy integration with dynamic data formats such as XML and JSON with defining schemas; syntax is flexible and familiar both to Ruby and Java (however, Ruby-like syntax is not always very intuitive to Java developers and vice versa); JVM allows for use with Java libraries and performance of compiled bytecode; "optional" type declarations vs. inference allows for flexibility in coding style; closures are a powerful, dynamic feature similar to methods in other languages; ability to compile statically to improve performance|
|JavaServer Pages (JSP)|CGI scripting|Shorthand code syntax to generate dynamic webpages that get compiled to Java servlets|Shorthand syntax shorter than writing HTML in servlet code directly; almost the performance of servlets|
|Jenkins|CI/CD tool|Allows you to define sequential stages to build a project on some event|Large plugin library; good integration with Ansible, Git, Docker, etc.|
|jQuery|DOM library|Popular JS convenience library for DOM manipulation|Large user base and plugin library; convenience methods for AJAX, UI components (as a plugin), event listeners, selectors, animations|
|lodash, underscore.js|JS library|Util library for JS|many utility functions not provided by JS (and some optimized versions of native JS functions), e.g., uniq, curry, debounce, merge, etc., and many other functions for arrays/objects/collections, functions, and type checks and conversions; allows imperative and declarative programming styles, as well as chaining|
|Maven|JVM build tool, dependency management|Defines a building/packaging lifecycle for Java applications, and a consistent dependency (artifact) structure|Very strong convention that is widely supported across Java applications; many dependency and plugin repositories and wide IDE support; defines a default lifecycle that makes building/packaging easy without much configuration|
|NPM|Package manager|Manage Node.JS projects and dependencies|largest package ecosystem in the world; module system (using a CommonJS-like syntax by default); support for newer (ES6) features with flags|
|PowerShell|Scripting language|Scripting language for Windows|Comes with Windows, but also has a (less-featured) version, Powershell Core, for Windows/MacOS/Linux; largely designed with remote access in mind; integration with .NET; good documentation|
|Redux (and ngrx)|JS library|Manages the state of application, maintaining consistency with immutable state changes and observable data members|strong philosophy of immutable state changes; good for maintaining global application state when state members are needed across disparate components; ngrx has built-in support for Angular's reactivity|
|RxJS|JS library|Reactive programming for JS|heavily used by Angular to build its reactive components, has many builtin operators, many useful types (e.g., `Observable`, `Subject` (and various subclasses)); utilities to map and chain/pipe operators|
|TypeScript|JS superset|Superscript of JavaScript (that transpiles to JS) with strong types and (typically) ESNext features|Command-line tool and tsconfig to build and configure app; Wide support and integration with popular frameworks (e.g., React, Angular); Diverse data structures (e.g., interfaces, enums) and powerful typing (including generics, special types like `this`, `unknown`, union types); offers type guards and linting capabilities for IDE development|
|Workers (web and service)|JS feature|Ways to run JS outside of the main thread of a web application|Web workers (dedicated and shared) allow for concurrency in a web application, offloading some of the computations from the main thread; service workers act as a proxy for web applications and may persist even offline, allowing for caching, responding to push/sync/fetch requests, which in turn can provide offline experiences and behavior even when the app or even the browser is closed| 

##### Things to add:
I'll try to add to this as I learn new stuff.

\* = interested, but gotta learn these (better) first

- JS frameworks:
  - React *
  - Vue
  - Aurelia *
- Node.js libraries:
  - express
  - socket.io
- JS libraries:
  - THREE.js
- Other web frameworks:
  - Laravel *
  - Ruby on Rails *
  - Django *
  - Java Spark Framework (not Apache Spark)
  - Spring.io *
- Python libraries:
  - matplotlib
  - numpy
  - pandas *
  - pyqt5
  - pyside2
- Shell:
  - bash *
  - zsh *
- SCM/VC:
  - Git/GitHub
  - svn
