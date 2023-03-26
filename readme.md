<!-- -----------Question 2--------------- -->

A. List five significant features of React

<!-- ----Answer----- -->

1. JSX

- JSX stands for JavaScript XML. It is a JavaScript syntax extension,
- React uses JSX to combine javascript and html together.

2.  Components

- ReactJS application is made up of multiple components, and each component has its own logic and controls. These components can be reusable.

3.  One-way Data Binding

- ReactJS is designed in such a manner that follows unidirectional data flow or one-way data binding.

4.  Virtual DOM
5.  Simplicity and Performance

<!-- ------Question 3-------- -->

B. List five major advantages of React

- Reusable components
- React is easy to learn, and Improved Performance
- Easy Creation of Dynamic application
- React provide tools dedicated for Debuging
- React is a Unidirectional data flow

<!-- -------Answer----------- -->

<!-- -----------Question4----------- -->

C. What is the name of the Software Engineer that created React? Also, which company owns React?

<!-- -------------Answer------- -->

- Jordan Walke
- FaceBook

<!-- ------Question 5------------ -->

D. What are the notable differences between HTML & JSX? Give at least 3 of them

<!-- -----------Answer---------- -->

1.

- In JSX, you must return a single Parent Element or Root Element or it wont Compile.
<div></div> can be used or Fragment <></>
while
- In HTML, you are free to do whatever you want as you don’t have to return a single parent element.

2.

- JS can be implemented directly in JSX i.e In JSX, it is possible to write JavaScript directly. You can do this by putting the JavaScript in curly braces {...}.
  Whereas
- In HTML, you need a script tag or an external JavaScript file to implement JavaScript:

3.

- All tags can self-close in JSX i.e Tags can self-close in JSX , it is possible to have
<div></div> as <div /> and <span></span> as <span />. Also It is important to always close self-closing tags with slash before the right angle bracket, that is <br />
whereas
- Self-closing tags in HTML can self-close without the slash before the right angle bracket, that is <br /> could work as <br>.

4.

- To define class names and for attributes in JSX, you don't do it as class or for as it is normally used in HTML, because both are reserved keywords in JavaScript. You do it as "className" and for attributes for labels you write "HTMLFor":

5.

- You need to write all HTML attributes and event references in camelCase while writing JSX. So, onclick becomes onClick, onmouseover becomes onMouseOver

<!-- --Question 6--------- -->

E. Why can’t browsers read JSX?

<!-- Answer---------- -->

Because JSX is not valid JavaScript, browsers can’t read it directly; they do not know what to do with it, so there is need for a transpiler to translate it to React.createElement() calls. We need transpilers (a compiler that translates one form of syntax into another) like Babel or TypeScript to compile JSX into a browser-compatible version.
