********* How to run this locally ********
step 1: clone the repository.
step 2: install vs code live server extension
step 3: click go live and your website will start on local host.

******** html Structure ********
contains two major sections header and hero section.
header contains the navbar and hero section contains the text and the image.

layout is created using the css flexbox property.

the hamburger menu is created using a hidden checkbox techniques that i learned from chat gpt as i did not know how to create hamburger without js.

first a checkbox was added along with hamburger setting its display to hidden.
then using pseudo selector
#menu-toggle:checked ~ .nav-links{
  display:flex;
}
to toggle hamburger menu on and off when checked. 