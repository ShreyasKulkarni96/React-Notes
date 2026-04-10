* What is JSX?
  JSX stands for JavaScript XML. JSX allows us to write HTML elements in JavaScript and place them in the DOM without any createElement()
  and/or appendChild() methods. JSX makes it easier to write and add HTML in React. JSX converts HTML tags into react elements.

  const element = <h1>Hello Shreyas</h1>

  It will get converted to:

  const element = React.createElement("h1", null, "Hello Shreyas");

  So JSX is syntactic sugar over React.createElement
  It improves: 
              - readability
              - maintainability
              - developer velocity

              JS -> (Babel) -> JS -> (Parcel bundles) -> Browser

* Babel 
  Babel convert JSX -> JavaScript which browser can understand
  Syntax transformer

* Bundler 
  - Bundles file
  - Running babel
  - Dev server
  - Hot Reload
  - Minification

  Bundler is to build system + pipeline orchestrator

* React is component based architecture
  Components = units of abstraction
  They should be:
                - reusable
                - testable
                - isolated



  