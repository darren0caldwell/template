# template
I've been using this template to quickly make websites, doesn't follow MVC but I like it
The premise is that I prefer full javascript, the page never reloads.

Website is the main array object that holds all pages
to create a new page setup a page object, fill in the variables you want (if you leave them all blank, or create a webpage object with no page object that is fine).
create a new webpage and pass in the page object.
push the new webpage into the website array
once your done pushing all pages just use
Website[0].init() to get the HTML, the mutate function is available as well as sub mutate functions for the various areas like the title etc
