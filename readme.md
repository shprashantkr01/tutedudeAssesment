*************** HTML STRUCTURE ************
First the body have a div conatainer whose class is .container.
Then, .container further have two div with class names .left and .right.
.left contains an img tag
.right contains a h1 followed by p followed by a form.

**************** CSS Styling ***************
first the default margin and padding is removed and overflow is set to hidden to hide scrolling.

Then the .container div's display is set to flex and height and width is set to 100vw & 100vh to use full viewport window.

As the .left div contains only div so it is given flex : 1 to give 50% of container.
then thew image is set to 100% width and height and object-fit cover to utilize full .left space while mantaining the image aspect ratio.

Then the .right conatiner is given flex:1 in order to give 50% of container space.
and its display is also set to flex to style its inner elements.

then using the direct child selectors its internal elements are styled.

similarly the form with the class .login is styled setting its display flex and using direct child selectors to style its internal elements.