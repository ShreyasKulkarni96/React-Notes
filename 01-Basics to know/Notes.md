Basics to know before starting with React

* Lets start by understanding what is a library and a framework?
  
  LIBRARY - You control the flow
          - It is a collection of functions or tools that you can use whenever you want.
          - You control the flow of program
          - You decide when and where to use the library
          - It helps to perform specific tasks

          e.g React, Lodash

          When to use: 
                      - you want flexibility
                      - you want control over architecture
                      - you are building custom solutions
    

  FRAMEWORK - It controls the flow
            - It provides a structure and rules for building your application.
            - Framework controls the flow
            - You plug your code into it
            - It decides when your code runs
            
            e.g Angular, Next.js, Spring boot

            When to use:
                        - you want fast development
                        - you need structure and scalability
                        - you are working in large teams


* React is a library, but with tools like React router, Redux, Next.js it starts behaving like a framework.

* What is CDN ?
  CDN = Content Delivery Network
  A CDN is a network of servers that deliver files from the nearest loction to the user.

* Why do we use CDN?
  - Faster loading
  - Reduced server load
  - Easy setup
  - Good for quick projects / demos

* Why is React called "REACT"?
  Because it reacts to changes in the data.

  When state changes: 
    - React updates UI automatically
    - No manual DOM manipulation

* What is crossorigin in script tag?
  It controls how browser handles cross-origin requests

  <script crossorigin src="..."></script>

  Why it's used?
    - Required for CDN scripts
    - Helps in error tracking 
    - Enables proper CORS handling

* React vs ReactDOM
  
   React  -  BRAIN
      - core library
      - handles components, state, hooks

   ReactDOM  -  HANDS
      - connects React to browser DOM
      - Renders UI

* Async vs Defer
  
  Both are used in <script> tag
  
  * Async 

     <script async src="script.js"></script>
    
     - Loads script parallel
     - Executes immediately when ready
     - Does NOT maintain order

  * Defer
    
     <script defer src="script.js"></script>

     - Loads parallel
     - Executes after HTML parsing
     - Maintains order

* What is DOM?
  Document Object Model

  It is a programming interface that represents your HTML page as a tree of objects, so javascript can interact with it

  DOM allows JS to read, modify, add or delete HTML elements dynamically

    <body>
       <h1 id="title">Hello</h1>
    </body>

    DOM lets you change content, style, handle events and create dynamic apps

* What is Virtual DOM?
  Virtual DOM is a lightweight JS representation of the Real DOM

  Instead of directly updating the browser DOM, React
    - Created a virtual DOM
    - Compares changes
    - Updates only what is needed

    Virtual DOM is faster way to update UI by minimizing real DOM operations

    React uses diffing algorithm for this and compares the change between Virtual DOM and real DOM. Which is called as Reconcillation.

    


  






