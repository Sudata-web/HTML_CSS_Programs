HTML :-----

- HTML stands for Hyper text markup language. 
- It is used to structure a website or web pages. 
- HTML is not a programming language it's a markup language because it's holds a skeleton structure of a web pages so we called HTML as a markup language. 
- All HTML is written through some tag lines. 
- The main tag of HTML element is <html>. 

Head Tag :---- 

- in head tag we have some tag like <title> tag , meta elements and some external css links. 
- Basically <title> tag contain our website title on the title bar. 
- in meta elements we attched our meta content like responsiveness & unicode value etc.. 
- we attached some external style sheet through <link> tag. 

Body Tag :----- 

- Body tag contains all the page structure. 
- Basically we do design and development in body tag only. 

Heading :----- 

- Heading is the main element in HTML page. 
- there are 6 types heading are there in HTML. (h1-h6)
- h1 is the bigger heading & h6 is the smaller heading, we can use it by our requirement. 

Paragraph :----- 

- paragraph play a major role to describe our data or infomation brieflly. 
- Basically it denoted by <p> tag. 

Break Tag :---- 

- break tag is used to break the line or terminate the line into a new line. 
- break tag is denoted by <br> tag. 
- it is a single tag structure. 

HR tag :---- 

- HR tag stand for horizontal line. 
- it is create a horizontal line to separate html element. 
- it is denoted by <hr> tag. 
- it is also a single tag. 

Image Tag :----

- when we want to put a image to our html element we need a <img> tag for that. 
- <img> is also single tag. 
- in that tag , we have some elements to configure our image , these are called attributes of <img> tag. 
- we can use src, height, width & alt, are the attributes of image tag. 

Anchor Tag :---- 

- it is used to attached some outer side links inside our web page. 
- Anchor tag contains 2 attribute like href & target. 
- Anchor tag is denoted by <a> tag. 
- HREF - hyper reference means reference a point or a page to a new page. 
- target attribute have 2 value :- 
    _blank : it is used to open ourtside links to a another tab.
    _self : it is used to open outside links to the same tab. 

HTML Formatting :---- 

- to format our text in a proper way. 
- there are 10 types of formatting are there... 

1. <b> -> bold the text
2. <i> -> italic the text
3. <em> -> emphasized the text
4. <small> -> smaller the text
5. <strong> -> stronger the text
6. <mark> -> marked / highlight the text
7. <ins> -> inserted the text
8. <del> -> deleted the text
9. <sub> -> subscript the text
10. <sup> -> superscript the text

Table in HTML :---

- As we drow our normal table like that html holds a table like structre to store data in a organized way. 
- <table> is the main tag of html table. 
- Inside it we have :
    -> <tr> - table row
    -> <th> - table heading 
    -> <td> - table data
- HTML table is row wise structuring. 

List in HTML :---

- as per the day to day life, when we store some data in a proper format we need a list, like that html provide us a list to store our info./data. 
- there are 2 types of list in HTML. 

1. Ordered List :- 

- when we store some data in a organized way , it's called ordered list. 
- it is denoted by the <ol> tag. 
- inside <ol> tag we have <li> tag (list items) to store the data inside it. 

2. Unordered List 

- when we store some data on unorganized way, it's called unordered list. 
- it is denoted by the <ul> tag. 
- inside <ul> tag also we have <li> tag.

block lavel element:--

- we used block level element in html because we need to structure the whole website in a single frame so we configure the whole frame in a small small block structure. 

ex. <div>, <p>, <nav>, <Main>, <section>, <header>, <footer>, <Navbar> etc... 

Inline Element :-

- inline element means it fit within the existing line or ot take only the required space in existing line. 

ex. <span>, <a>, <strong>, <mark>, <b>, <i>

Form tag in HTML :- 

- An html form is used to collectsome user inputs for the data storage purpose.
- <form> tag is the main tag of html form
- inside <form> tag, we have level & input tag for take the user input. 
- there are multiple input are there in HTML form.. 


1. <input type="text">
2. <input type="eamil">
3. <input type="passwors">
4. <input type="checkbox">
5. <input type="radio">
6. <input type="submit">
7. <input type="date">
8. <input type="time">
9. <input type="range">
10. <input type="file">
11. <input type="image">
12. <input type="url"> etc.....

Practice Task :- 

- create simple portfolio website... thats contains
1. name 
2. image
3. description
4. educational qualification stating from LKG (Table)
5. Your strength (OL)
6. Your Weekness (UL)
7. your tech skills 
8. your all social media handles (a) 
9. design a form based on Vishal mega mart bill. 
10. you can store it on github and share the link on wp group. 






*********************************** SCC:--------------------------

- SCC stands for cascadding style sheet.
-we use to design / styling our web pages.
-scc is also not a programming language,it'styling language.

-syntax:--

- selector{property:value;}

ex: h1{
    color:blue;
}

-- there are 3 types of css we used.. 
1. inline css :- 

- we used inline css inside the tag. 
- inline css have highest priority than other type of css. 
- we can put our styling by cretaing a <style> attribute inside the tag. 

2. internal css :- 

- we used internal css inside the head tag, by creating a <style> tag inside it. 
- internal css are mostlly used on small codebase. 

3. external css :- 

- we used external css by creating a separate css file and link that file on our main html page. 
- we can link the external css file by <link> tag. 
- it is most popular and widelly used to write css in proper format. 

Selector in CSS :- 

- we used css selector for selecting an items for the shake of designing. 
- there are mainlly 5 types of selector are there... 

1. ID selector :- 

- ID selector is a type of selector that used for unique design. 
- it is denoted by the symbol "#". 

2. Class selector :- 

- class selector is a type of selector that used for similar design in multiple elements. 
- it is denoted by the symbol "."

3. Group selector :- 

- Group selector is a type of selector that used for design more than one element by creating a group like structiure. 

4. Universal selector :- 

- universal selector is a type of selector that used to design whole html element in one style. (universally designed)
- it is denoted by the symbol "*".


5. Element selector:---
-Element selector is a type that used to design one by one element.
-it is denoted by simple "tag name".

properties of CSS:----

1. color: red /green/blue....
2. background color : red/blue....
3. text-align : left/center/right...
4. text-decoration : underline/overline/line-through
5. font-weight : normal/bold/bolder/100/200/500
6. font-style : normal/italic/oblique
7. font-size : 10px/20px/30px
8. font-family : arial/verdant/times new roman  /san-sari/italic
9. padding : 10px/20px/30px
10. margin : 10px/20px/30px
11. border : 1px solid black
12. border-radius : 10px/20px/30px
13. background-image : url("image.jpg")
14. background-repeat : repeat/ no-repeat
15. background-position : center/center/center
16. line-height :1/2/3/4....
17. text-transform : uppercase/lowercase/capitalize
18. display : block/inline/table






























linear gradient:------(18-06-2025 *wed day*)
-A linear gradient create a smooth transition between two or more colors.
-Along a stret line. (horizontal,vertical,diagonal..etc).
-instead of a solid color, you can use linear-gradient: to blend color beautifully.
-its used to create a gradient effect on the background of an element.
-syntax:- background: linear-gradient(direction, color1, color2, ...);
-Example: background: linear-gradient(to right, red, blue);
-Example: background: linear-gradient(to left, red, blue, green);

direction keywords:---
-to right- ( left to right )
-to left- ( right to left )
-to top- ( bottom to top )
-to bottom- ( top to bottom )
-to top right- ( top to right )
-to top left- ( top to left )
-to bottom right- ( bottom to right )
-to bottom left- ( bottom to left )
-Example: background: linear-gradient(to right, red, blue);
-Example: background: linear-gradient(to left, red, blue, green);

-we can use angles also. (degree)
-Example 0 Degree left to right.
         90 degree then top to bottom.
         180 degree right to left.
         270 degree bottom to top.
-Example: background: linear-gradient(45deg, red, blue, green);

- background: linear-gradient(135deg, #ff4e50, #f9d423);
      =135 degree move top left to bottom right.

Multicolor Gradient:---
-You can use multiple colors in a linear gradient.
Example:-background: linear-gradient(to right, red, orange, yellow, green, blue, indigo, violet);

-using angles.
-Example: background: linear-gradient(45deg, red, orange, yellow, green, blue);
-it create a diagonal gradient from top left to bottom right.

Example with Gradient stops:-
-Gradient stops are used to specify the color at each point in the gradient.
-Example: background: linear-gradient(to right, red 0%, blue 50%, green);
-background: linear-gradient(to right, red 30%, blue 70%);
-this controls were each colors starts or ends -
-red takes 30% of the gradient and blue takes 70% of the end gradient.

position                    color description
-->0-30%                     -->30-70%
-->solid red                 -->bled from red to blue
                             -->70-100% (solid blue)

What is a Radial Gradient:---
-Radial gradient is a type of gradient were colors radiate out from a central point.
-Unlike a linear gradient (which transition along a line) a radial gradient forms a circle or an ellipse color progression.
-syntax:-
background: radial-gradient(shape size at position, color-stop1, color-stop2, ...);
1>parameter explanation
2>shape- circle or ellipse
3> by default it is ellipse
4>side- closet side, closest corner, farthest side , farthest corner.
  Farthest Corner :-
  -it is the default value.
  -it is the farthest corner of the ellipse from the center.

5>position- were the center of the gradient is (center, top, left, right, bottom)
6> color stops- colors and point were the transition happen.
-Example: background: radial-gradient(circle at center, red, blue);


Q) why use this?
-using % in gradient allows you to control exactly were color transition happen.
-it's specially use full for.
 1> creating victual balance
 2> highlighting certain portion
 3> making UI element look more natural
 
 Q) How to use gradient in CSS?
 -You can use the linear-gradient() function in CSS to create a linear gradient.
 -Example: background: linear-gradient(to right, red, blue);
 -You can also use the background-image property to apply a gradient to an element.
 -Example: background-image: linear-gradient(to right, red, blue);

 Q) what is the default gradient direction?
 - The default gradient direction is to bottom.
 -Example: background: linear-gradient(red, blue);
 -This will create a gradient that goes from top to bottom.

 Q) Can you use Angles linear gradients?
 -Yes, you can use angles with linear gradients.
 -Example: background: linear-gradient(45deg, red, blue);

 Q) what are gradient stops?
 - Points were color changes happen.
    -like red 20% , blue 80%.

Q) can gradient apply to text?
-Yes, you can apply a gradient to text.
->with the text-shadow property.
->Example: text-shadow: 0 0 10px linear-gradient(to right, red,blue);
background-clip: text and -webkit-text-fill-color: transparent

Q) what is the diffence between linear and radial gradient?
-Linear changes is the line direction.
-radial changes is the circle or elliptical direction.
-Example: background: linear-gradient(to right, red, blue);
        : background: radial-gradient(red, blue);
Q) can we combine Multiple gradients?
-Yes, you can combine multiple gradients.
-using comma separation for layers.
-Example: background: linear-gradient(to right, red, blue), linear-gradient(to bottom, grey);

Q) Is linear gradient a valid color value?
-Yes, linear gradient is a valid color value.
-it is treated like a background image not a color.
-Example: background: linear-gradient(to right, red, blue);

Q) Dose linear gradient work in all browsers?
-Yes, linear gradient works in all modern browsers.
-But older browser may not support it.
-Example: background: linear-gradient(to right, red, blue);
-older browser may not support it.


Media Queries:--
Q) What is media query?
-media query in css allowes contain rendering to addapt to different screen size and orientation.(like mobile, tablet, desktop.)
-Example: @media (max-width: 768px) {
    -there are many types of media query.
    -like max-width, min-width, max-height, min-height, orientation, aspect-ratio
    Q) What is the difference between max-width and min-width?
    - max-width is the maximum width of the screen.
    - min-width is the minimum width of the screen.
    -Example: @media (max-width: 768px) {
Q) Can you use multiple media queries in one CSS file?
-Yes, you can use multiple media queries in one CSS file.
-Example: @media (max-width: 768px) {
    -media query can be nested inside each other.
Q) what is the media screen and all ?

        



REACT:-----
Q)what is promise in react?
-Promises in React—they're a key part of handling asynchronous operations, like fetching data from an API or reading from a file.
-Promise is a function that returns a value that may not be available yet, but will be resolved.
-A Promise has 3 states:---
pending – operation is still ongoing

fulfilled – operation completed successfully

rejected – operation failed

-Summary
Method	Use Case
.then()	:-Handle promise resolution and chaining/resolve
.catch():-	Handle errors in promise/reject
async/await	:-Syntactic sugar for cleaner promise handling/pending
Multiple requests	:-Promise.all()

All HOOKs in react:------
Q) What is a hook in React?
- A hook is a special function in React that allows you to "hook into" React state and lifecycle methods from functional components.
- Hooks are a way to use state and other React features without having to write a class component.

-*- There are several types of hooks in React, including:
- useState: allows you to add state to a functional component
- useEffect: allows you to run side effects in a functional component
- useContext: allows you to access context in a functional component
- useReducer: allows you to manage state in a functional component
- useMemo: allows you to memoize a value in a functional component
- useCallback: allows you to memoize a function in a functional component
- useLayoutEffect: allows you to run side effects in a functional component, similar to useEffect,
- useDebugValue: allows you to add a value to the React DevTools debug menu
- useImperativeHandle: allows you to expose a value to a parent component
- useReducer: allows you to manage state in a functional component
