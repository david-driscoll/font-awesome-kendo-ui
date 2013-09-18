Font Awesome Icons + Kendo UI
===

Bringing awesome together!


This is a little integration style that will replace your standard [Kendo UI (web)](http://www.kendoui.com/) sprite based icons, into font based icons, using the most awesome, [Font-Awesome](http://fontawesome.io/).

In this initial version, some icons are not supported, but they are stubbed out.  


How-to use?
====

CSS
----
If you are using CSS from both font-awesome and kendo-ui, simply include the included css file after both your kendo-ui styles, and font-awesome styles.  The included CSS will do the rest!

Less
----
If you are using Less to compile your css, include the less file both your kendo styles and font-awesome styles have been loaded.  There are no external dependencies on either library.


What's in, what's not?
====
So far this is just the initial release, I've captured the majority of the common controls.  Things like the kendo editor, have not been captured.  I have not looked at Dataviz to see if anything needs to be done there or not.


kendo.window
----
FA doesn't have any great icons for window minimize, restore and maximize.  Those are currently in the issue queue for FA on Github, and as soon as they are completed, they will be added properly here!


kendo.treeview
----
The icons for insert top, middle and bottom have no nice equal in FA yet, this may be a request that might get fullfilled at somepoint.


kendo.editor
----
There are a rew missing pieces to this one, they're laid out in the less file if yuo want to take a gander.


kendo.slider
----
Not implemented, might not be able to that easily.


Something missing, not aligned right?
===
Feel free to drop an issue in the tracker, or if you're willing make a pull request.  The requirements are light, just a simple npm, bower for resporces and grunt for building the output css.
