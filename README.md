Licensed under the MIT License. 

Copyright 2017 RYAN TUBBS rmtubbs@gmail.com 

===================================================================================

RYAN TUBBS' PERSONAL WEBSITE

This site is still partly under construction, but I wanted to get a version up online 
for testing. 

I assembled this site using Bootstrap v4.0.0-beta.2. I started with the basic Bootstrap Jumbotron
template and heavily customized the components to get the effect I wanted. You may notice that there is 
no separate CSS file. Instead, I linked to Bootstrap's content delivery network (CDN) CSS stylesheet. 
I had never used a CDN stylesheet before, and I wanted to see what all the fuss was about. The difference 
between a standard CSS file and a CDN stylesheet is that the CDN is loaded into the HTML file via an 
https request rather than being served from the same location as the HTML file, as would occur with a 
traditional CSS file. 

In theory, this arrangement allows for a quicker and more simplified development approach - no need to fiddle 
with setting up a CSS file, just paste the CDN address into your HTML <head> and start appending your
HTML elements with Bootstrap's numerous class definitions to get the styles you want. As long as you are 
satisfied with Bootstrap's predefined class style definitions, this approach works quite well. And I was,
indeed, able to achieve most of the styling modifications I wanted by using this method. However, there 
were several effects I was not able to create using the predefined class definitions, and I found myself
having to add inline style declarations for things like opacity transitions and a @media query to prevent 
background-attachment:fixed from loading on mobile devices. 

For my purposes, this really wasn't that big of a deal, but I can see how it might be too confusing for 
larger projects with multiple developers. Still, it was nice to not have to continuously switch back and 
forth between the HTML files and the CSS files. Have a look at my HTML files to see if you think this 
approach might work for your project. 

Stylistically, I was looking for a format that would allow me to create what was essentially a heavily 
annotated résumé. My employment history doesn't exactly scream "Developer", so I wanted a format that 
provided enough room for me to write about my transferable skills and such in some detail. I chose 
Bootstrap's "card" component (the white sections of the site with all the text) for this, along with a 
circular image component so visitors could see just how amazing I look in a suit. I wrapped both of these
components within a Bootstrap Flexbox container that switches from a horizontal to a vertical alignment to
fit the viewport. I'm generally pleased with the end result, but (as usual) I wrote more than I thought I would, 
so some of the card sections have a little bit of a "wall-of-text" feel to them. 

At some point I'll get around to adding the Portfolio and Blog sections mentioned on the home page! 

If you like what you see, feel free to modify and use the files for your own site. Just be sure to tell
everyone how awesome I am for creating it, or make me an offer I can't refuse.  


