# Philosophy #

I started this project explicitly as a means for learning about PHP and MySQL.  That means that there are some decisions that I made (like with getters/setters and CamelCase variable names) that are different than if I were doing an open source project that (possibly many) people might work on.  This still colours my view of things, and until other people get involved, I'm likely to carry on that way.

For example, I want some practice with MySQL.  Even though it might not be the best thing for an open source project, I might move all the geometry, population, and area data into a database.

For example, I make the coloured areas with KML instead of with tiles, as I did with my [Census Bureau mashups](http://maps.webfoot.com).  I think tiles actually make more sense -- especially when there are a lot of polygons -- but I wanted to learn something new.

For example, I can imagine generating Javascript/HTML that makes encoded GPolygons.  (I've actually done some work on that already.)  It's kind of a stupid way to do things -- it turns out being much slower than with KML -- but I'd kind of like to "complete the set" of code to generate polygons: tiles, KML, and GPolygons.  (Using GOverlays might be yet another way; I'll have to look into that at some point.)
