The main CSS stylesheet doesnt validate, but please ignore that! Both errors thrown are 
described below, with reasons for our not fixing them.

Errors:
1. It says that "background-position-y: -250px;" is bad, but it's supposed to be there! It is 
the best way to shift our fixed html background image up so that the part we want is showing.

2. It says that "@-webkit-animation" isnt implemented, but it is neccessary in order for our 
animation to work on all CSS 3 supportive browsers. 