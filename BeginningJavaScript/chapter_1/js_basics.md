#BEGINNING JAVASCRIPT

Javascript language is an __*interpretive*__ language rather than a __*complied*__ language.... Difference?

* __INTERPRETIVE:__ The computer doesn't really understand JS per say, in fact it needs something to interpret it. Computers only really understand binary. As the browser goes through the JS it passes it to a special programme called an interpreter, which converts the 'unreadable' language into machine code, which the computer does understand. This conversion happens EVERY TIME the code is run, and therefore has to be repeated each time as it is not 'saved'.

* __COMPILED:__ The programme code is converted into machine code before it is actually run, and it only needs to be done once. The programmer uses a compiler to convert the code that she wrote into machine code which is run by the user [eg.C++].

JS runs inside the web page, inside the browser. Initially called livescript, it is extremely widespread and popular not to mention versatile. It can be used both on and off webpages and front or backend.

Users tend to use JS mainly for user interaction especially with regards to the web. Gathering user information and validating their answers/ actions.

##Script tag & Saving

This area in the HTML web page points to the where the external scripting elements are through the 'src' attribute, aka, the JS files that are to be used in the webpage.
For example:

```javascript
<script type="text/javascript" src="Desktop/JS/example.js"></script>
```
###*Painting the page Red!*

```html
THIS IS NOT IDEAL PRACTICE AND FOR EXERCISE PURPOSES ONLY
<html>
  <body bgcolor="BLUE">
  <p>Paragraph 1</p>
    <script type="text/javascript">
    // Script block 1
    alert("First Script Block");
    </script>
  <p>Paragraph 2</p>
    <script type="text/javascript">
    // Script block 2
    document.bgColor = "RED";
    alert("Second Script Block");
    </script>
  <p>Paragraph 3</p>
    <script type="text/javascript">
    // Script block 2
    document.bgColor = "ORANGE";
    alert("Third Script Block");
    </script>
  </body>
</html>


```
Everything in the <scrpit> tags are javascript and the computer knows because of the 'type" explanation.
What would normally be referred to as the *page* is now referred to as the *document* in JS, followed by a '.' and a particular property, in this case, background colour : ```bgColor```.

As above and in the __test__ file, there are more elements to notice, the comments [ made by using // ], the ```alert()``` function - which is *modal*. This means it creates a pop up/ message box [ one that WONT GO AWAY until the user clicks the ok button ].

It is important to note that the background colour set in the first paragraph is done in HTML. Properties set in HTML are *static*, a value can be set only once, and never again be changed by using HTML. JS is dynamic, the opposite.–

A __*function*__ takes some information, processes it, and gives you a result.
