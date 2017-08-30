# RC_MapSlideshow

This plugin is designed to make it easier for Muse designers to use Mapbox to tell their stories. 

You can set up your map hosted by Mapbox easily with MapSlideshow. It will allow you to view 3D buildings, play locations as slideshow, present the titles, decriptions and media for your locations and create clickable dom markers.

Originally, this project was created for my own website, http://renechen.me, you can view http://renechen.me/adventure.html as an example to implement the plugin in Adobe Muse. 

To use RC_MapSlideshow in your website project:

you can download example.geojson and RC_MapSlideshow.mulib, which is packed with all needed elements, such as navigation buttons, title container, decription container and media container.

Update 1.02, August 30th, 2017

Now the text box of title and description can recognize HTML tags, such as <a/> as hyper-link. e.g. "description": "Office for HR and Finance <a href='http://www.apple.com'>Go To Apple</a>" will be shown in the description box as "Office for HR and Finance Go To Apple".

Update 1.01 July 3, 2017

Addressed an issue that when used in fluid website, the map canvas, in certain breakpoints, initially won't be sized properly.

System Requirement:

1. Adobe Muse 2015.1+
2. An Mapbox account to create your own map with your style

Useful tools to generate and edit geojson
1. Mapbox Dataset to creat and generate geojson file, but the generated file will lost the sequence by which you inpput the locations. However you can make your Dataset into a layer of your map here directly.
2. http://www.cleancss.com/json-editor/ to edit the sequence of the location in your geojson.


To make RC_MapSlideshow better:

you can download source_code.mucow. You need the following development environment:
1. Brackets
2. Extension: Brackets New Project Creator
3. Extension: MuCow Language Support


