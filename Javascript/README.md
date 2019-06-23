- ## ES5
    - ### Basic Language Features
      - [Expressions Versus Statements](http://2ality.com/2012/09/expressions-vs-statements.html)

      - [Control Flow Statements](http://www.culttt.com/2012/10/29/javascript-control-flow-structures/) and [Blocks](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/block)

      - #### Comments
        - How to write good comments

        - Why comment should not be written

        - Links: [[1](https://medium.freecodecamp.org/code-comments-the-good-the-bad-and-the-ugly-be9cc65fbf83), [2](https://dzone.com/articles/5-best-practices-commenting), [3](https://blog.codinghorror.com/code-tells-you-how-comments-tell-you-why/)]

      - #### [Strict Mode](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode)

      - #### [JavaScript’s Type System](http://2ality.com/2013/09/types.html)
        
        - Static Versus Dynamic

        - JS Types

        - Static Typing Versus Dynamic Typing
        
        - Static Type Checking Versus Dynamic Type Checking
        
        - Coercion
        
        - [An explanation of JavaScript’s weird type system](https://medium.com/dailyjs/the-why-behind-the-wat-an-explanation-of-javascripts-weird-type-system-83b92879a8db)

      - #### Primitive Values Versus Objects

        - [JavaScript Primitive vs. Reference Values](http://www.javascripttutorial.net/javascript-primitive-vs-reference-values/)

        - [The Difference Between Boolean Objects and Boolean Primitives in JavaScript](http://adripofjavascript.com/blog/drips/the-difference-between-boolean-objects-and-boolean-primitives-in-javascript.html)

      - #### undefined and null
        - [What’s the difference between Null & Undefined?](https://codeburst.io/javascript-whats-the-difference-between-null-undefined-37793b5bfce6)

      - #### [Equality Operators: === Versus ==](https://codeburst.io/javascript-showdown-vs-7be792be15b5)

      - #### [Logical Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_Operators)

      - #### [Truthy vs Falsy values](http://adripofjavascript.com/blog/drips/truthy-and-falsy-values-in-javascript.html)

      - #### [Bitwise Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Bitwise_Operators)

        - [Using JavaScript’s Bitwise Operators in Real Life](https://codeburst.io/using-javascript-bitwise-operators-in-real-life-f551a731ff5)

      - #### String
        - Unicode

          - Code Points

          - Size in bytes of a single char

          - [Unicode and javascript](http://speakingjs.com/es5/ch24.html)

        - Constructing Strings

        - Manipulation

        - Concatenation

      - #### Statements
      
        - Loops

          - for

          - while

          - do while

          - for in

        - if else

        - Switch

        - debugger statement
        
      - #### Functions ([details](https://github.com/PestoTech/curriculum/tree/master/Functions%20in%20JavaScript%20(ES5)#roles-of-functions))

        - #### [Roles of functions](https://github.com/PestoTech/curriculum/tree/master/Functions%20in%20JavaScript%20(ES5)#roles-of-functions)

        - #### [Defining Functions](https://github.com/PestoTech/curriculum/tree/master/Functions%20in%20JavaScript%20(ES5)#defining-functions)

            - [Function Expressions](https://github.com/PestoTech/curriculum/tree/master/Functions%20in%20JavaScript%20(ES5)#function-expressions)

            - [Function Declarations](https://github.com/PestoTech/curriculum/tree/master/Functions%20in%20JavaScript%20(ES5)#function-declarations)

            - [The Function Constructor](https://github.com/PestoTech/curriculum/tree/master/Functions%20in%20JavaScript%20(ES5)#the-function-constructor)

        - #### [Params vs Arguments](https://github.com/PestoTech/curriculum/tree/master/Functions%20in%20JavaScript%20(ES5)#params-vs-arguments)
        - #### [Hoisting](https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20%26%20closures/ch4.md)

        - #### [More Control over Function Calls: call(), apply(), and bind()](https://github.com/PestoTech/curriculum/tree/master/Functions%20in%20JavaScript%20(ES5)#more-control-over-function-calls-call-apply-and-bind)

        - #### [Arguments Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/arguments)

        - #### [Closures](https://github.com/PestoTech/curriculum/tree/master/Functions%20in%20JavaScript%20(ES5)#closures)

      - #### global/window object

        - [console](https://developer.mozilla.org/en-US/docs/Web/API/Console)
          
          - log
          
          - formatted output
        
        - [setTimeout](https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/setTimeout)

          - [A good question on setTimeout](https://medium.com/coderbyte/a-tricky-javascript-interview-question-asked-by-google-and-amazon-48d212890703)

        - [setInterval](https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/setInterval)

        - [clearInterval](https://developer.mozilla.org/en-US/docs/Web/API/WindowOrWorkerGlobalScope/clearInterval)

      - #### [Objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects)

        - Property Accessors ([Dot and square notation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Property_accessors))

        - [`this` in objects](http://2ality.com/2014/05/this.html)
          - Losing this When Extracting a Method
          - Functions Inside Methods Shadow this
          - Other [gotchas when using this](http://javascriptissexy.com/understand-javascripts-this-with-clarity-and-master-it/)

        - [Inheritance](https://www.digitalocean.com/community/tutorials/understanding-prototypes-and-inheritance-in-javascript)

          - [Prototypal Chain](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)

          - Sharing Data Between Objects via a Prototype

          - Setting and Deleting Affects Only Own Properties

          - [Javascript inheritance by examples](http://2ality.com/2012/01/js-inheritance-by-example.html)

        - Object reflective methods

          - [.keys](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys)

          - Check out all the methods of Object [here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object)

        - Accessors ([Getters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/get) and [Setters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/set))

        - [Property Attributes and Property Descriptors](http://2ality.com/2012/10/javascript-properties.html)

        - [Protecting Objects](http://2ality.com/2013/08/protecting-objects.html)

          - Sealing

          - Extensions

          - Freezing

          - Protection Is Shallow

      - #### Exception Handling

        - What Is Exception Handling?

        - Exception Handling in JavaScript

          - throw

          - [try-catch-finally](Languages  Edit  Advanced try...catch)

        - Error Constructors

        - Stack Traces
        
        - All these are explained [`here`](http://speakingjs.com/es5/ch14.html)

      - #### Arrays
        - Forms of objects

          > Arrays are list-like objects whose prototype has methods to perform traversal and mutation operations. Neither the length of a JavaScript array nor the types of its elements are fixed. Since an array's length can change at any time, and data can be stored at non-contiguous locations in the array, JavaScript arrays are not guaranteed to be dense; this depends on how the programmer chooses to use them. In general, these are convenient characteristics; but if these features are not desirable for your particular use, you might consider using typed arrays.

          Arrays cannot use strings as element indexes (as in an associative array) but must use integers. Setting or accessing via non-integers using bracket notation (or dot notation) will not set or retrieve an element from the array list itself, but will set or access a variable associated with that array's object property collection. The array's object properties and list of array elements are separate, and the array's traversal and mutation operations cannot be applied to these named properties.

        - Array Methods

          - [Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)

          - [Reduce](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)

          - [Filter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)

          - [forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)

        - [mutating and non-mutating methods](https://lorenstewart.me/2017/01/22/javascript-array-methods-mutating-vs-non-mutating/)

      - #### [Regular Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)

        - Quantifiers

        - Capture Groups

        - Flags

        - [.test](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/test)

        - [.match](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match)

        - [.exec](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/exec)

        - [A simple tool to play with regex](http://regexr.com/)

        - [Javascript regex in depth](http://speakingjs.com/es5/ch19.html)

      - #### [Date object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date)

        - Epoch time

        - [Understanding Date and Time in JavaScript](https://www.digitalocean.com/community/tutorials/understanding-date-and-time-in-javascript)

      - #### [JSON](https://www.json.org/)

        - [Working with JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)

        - [parse](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/parse)

        - [stringify](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify)

        - [difference between objects and JSON](https://stackoverflow.com/questions/8294088/javascript-object-vs-json)

    - #### Modules
      - [JavaScript Modules: A Beginner’s Guide](https://medium.freecodecamp.org/javascript-modules-a-beginner-s-guide-783f7d7a5fcc)

      - [In-depth](http://exploringjs.com/es6/ch_modules.html)

    - #### Shallow copy and Deep Copy

      - [Copying objects in javascript](https://scotch.io/bar-talk/copying-objects-in-javascript)

      - How to deep copy

      - Why it's required

    - #### [instanceof](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/instanceof), [typeof](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/typeof), [new](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/new)

      - [More about 'new'](https://codeburst.io/javascript-for-beginners-the-new-operator-cee35beb669e)

    - #### Pure, total and partial functions
      - [What are pure functions and why use them?](https://medium.com/@jamesjefferyuk/javascript-what-are-pure-functions-4d4d5392d49c)

      - [Pure versus impure functions](https://toddmotto.com/pure-versus-impure-functions)

      - Partial Functions

      - Functional perspective

        - [Decoupling methods from their objects](https://hackernoon.com/functional-javascript-decoupling-methods-from-their-objects-aa3ca13d7ae8)

        - [Function Composition For Every Day Use.](https://hackernoon.com/javascript-functional-composition-for-every-day-use-22421ef65a10)

      - Why it's better than loops

        - [map vs forEach vs for](https://ryanpcmcquen.org/javascript/2015/10/25/map-vs-foreach-vs-for.html)

        - [Rethinking JavaScript: Death of the For Loop](https://hackernoon.com/rethinking-javascript-death-of-the-for-loop-c431564c84a8) (Also read comments from the author for more context and why loops are a better choice in some cases)

    - #### Built In Modules

      - Boolean

      - Date

      - Error

      - Function

      - JSON

      - Math

        - NaN

        - Infinity

      - Number

    - [Concurrency Model and Event Loop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/EventLoop)

  - ## ES6
    - #### [Let](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let) and [Const](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const)
      - Lexical Scope vs Function Scope
      - Why const?
      - Only references are const
      - Temporal Dead Zone
      - [Variables and scoping in ECMAScript 6](http://2ality.com/2015/02/es6-scoping.html)
    - #### [Template Literals](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)
    - #### [Arrow Functions Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
      - this is lexical instead of bind
      - [versus normal functions](http://exploringjs.com/es6/ch_arrow-functions.html#sec_arrow-func-vs-normal-func)
    - #### [for-of](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of)
    
    - #### [default parameters](https://css-tricks.com/using-default-parameters-es6/)
    
    - #### [Named Params](http://exploringjs.com/es6/ch_parameter-handling.html#sec_named-parameters)
    
    - #### [Rest Params](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters)
    
    - #### [Tagged Templates](https://medium.freecodecamp.org/es6-tagged-template-literals-48a70ef3ed4d)
    
    - #### [De-structuring Assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)
    
    - #### [Shorthand Properties](https://www.eventbrite.com/engineering/learning-es6-enhanced-object-literals/)
    
    - #### [ES6 Modules](http://exploringjs.com/es6/ch_modules.html)

      - CJS

      - AMD

    - #### [Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)

      - [then](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/then)

      - [catch](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/catch)

      - [finally](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/finally)

      - [all](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/all)

    - #### [Classes in ES6](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

      - How it's same as new Function

      - [In-Depth](http://exploringjs.com/es6/ch_classes.html)

    - #### [Computed Object properties](https://www.eventbrite.com/engineering/learning-es6-enhanced-object-literals/)
    - #### [Object.assign](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign)
    - #### [Async/Await](http://exploringjs.com/es2016-es2017/ch_async-functions.html) (Promises)
      - How it's based on Promises
    - #### [Symbols](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol)
    - #### [Maps](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map) and [WeakMaps](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakMap)
    - #### [Sets](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set) and [WeakSets](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WeakSet)
    - #### [Iterator Protocol](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Iteration_protocols#The_iterator_protocol)
    - #### [Proxy](https://codeburst.io/understanding-javascript-proxies-by-examining-on-change-library-f252eddf76c2)
    - #### [Generators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator)
    - #### [Iterators and generators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Iterators_and_Generators)
    - #### [function*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function*)
    - #### [yield](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield)
    - #### [yield*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/yield*)
  - ## Style Guides
    - #### [AirBnB](https://github.com/airbnb/javascript)
      - [Breathing air into AirBnB’s JavaScript Style Guide](https://medium.freecodecamp.org/adding-some-air-to-the-airbnb-style-guide-3df40e31c57a)
      
      - [5 JavaScript Style Guides — Including AirBnB, GitHub, & Google](https://codeburst.io/5-javascript-style-guides-including-airbnb-github-google-88cbc6b2b7aa)
    - #### [Google](https://google.github.io/styleguide/jsguide.html)
    - #### [Standard JS](https://standardjs.com/rules.html)
