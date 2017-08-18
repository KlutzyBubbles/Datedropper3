# Datedropper3
The smallest and powerful jQuery UI datepicker

Fork modified by Lee Tzilantonis, for JQuery Mobile.

I found that the date dropper was a perfect solution for me but the compatibility with JQuery Mobile was lacking, so in this fork contains fixes for:
 - Inputs not bluring after datedropper hides
 - Syntax and logic errors with scrollable features
 - Conflicting theme data tags replaced with data-dp-theme
 - Null element references when using draggable UI
 
 Although this 'version' (dont know if you can call it that) of date dropper was modified for JQuery Mobile i am very positive that it will work on pages without JQuery Mobile (although JQuery is still needed). In the custom-functions folder you will find my personal modified files with any extra functions i find useful to me. I will try to document the changes of those files here:
 
 18/08/2017 - Added getDateUnformatted() which gets the unformatted (mm/dd/yyyy) date string or $.val() if the element isnt an initialised date dropper
 
 If the methods of adding these functions seems sketchy thats because they are, i am low on time and definitely do not have time to re code this library just for myself.
 
 ## How to use
 
 To use this plugin its very simple, follow the documentation the wonderful creators of this plugin have so greatfully made at http://felicegattuso.com/projects/datedropper/#docs and remember that the only difference is that <code>data-theme</code> is replaced with <code>data-dp-theme</code>
 
 HAVE FUN :D
