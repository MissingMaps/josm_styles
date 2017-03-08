# Using paint styles

Paint styles are ways of changing how data is viewed in JOSM. You can use them to highlight certain things to fix, things that might not come up in the validation checks. 

There’s a paint style you can add to JOSM to help you find a few errors that are common to HOT and Missing Maps tasks:
 - buildings with names
 - buildings not tagged ``building=yes``
 - roads that are named
 - roads that are named for a description (like ``highway=residential``, ``name=residential``) 
 - buildings that are connected to roads or other features


Like the validation warnings, the paint style doesn’t necessarily show what is wrong, but it shows what you’ll need to look at to see if it’s wrong.

To add the paint style, click on the Windows menu and go to Map Paint Styles… which will open a menu on JOSM:

![](https://i.imgur.com/EuOOoiE.png)

Then click the paint style settings button at lower right.

Click the plus sign at upper right to add a new one. 

![](https://i.imgur.com/fw04Miq.png)

Type a name like Missing Maps Validation or whatever you'd like, and put https://github.com/MissingMaps/josm_styles/archive/master.zip in the URL field, and the paint style will appear in your Map Paint Styles window. 

There are four colors you may see from this paint style, corresponding to the errors mentioned earlier: 
 - buildings with names are yellow
 - buildings not tagged ``building=yes`` are orange
 - roads that are named are green
 - roads that are named for a description (like ``highway=residential``, ``name=residential``) are red.
 - buildings that are connected to roads or other features are red triangles
 - buildings that are connected to other buildings are orange triangles

This paint style lets you got through and find these issues quickly and see if they should be fixed or not.

![](https://i.imgur.com/xLqP5Ah.png)
![](http://i.imgur.com/7OHaoOj.png)
