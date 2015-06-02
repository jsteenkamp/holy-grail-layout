#Holy Grail Layout

The Holy Grail layout is an excellent way to learn the basics of CSS layout.

We are going to implement the Holy Grail layout. The HG layout is a historic web site layout problem. The requirement is a fluid layout that has a width header, and footer and a main content area comprising three columns (navigation, content, aside).  The header and footer should move with the content when scrolled vertically - in other words they are not fixed in position.

There are many solutions with mixed results  

[Holy Grail Layout](http://en.wikipedia.org/wiki/Holy_Grail_%28web_design%29)

One of the original Holy Grail layout articles: [A List Apart - Holy Grail](http://alistapart.com/article/holygrail)

We’ll tackle the problem by first attempting to solve it using traditional (“old school”) CSS, then we’ll update our CSS using SCSS to learn some of the simple and useful features. We also solve the problem without flexbox. Finally we’ll solve the problem using modern CSS and HTML by using flexbox.

The Holy Grail layout is not really that useful today as designs have progressed and adapted to needs of varied devices.


##CSS Layout

Files: /holy-grail-layout/css-traditional 

First visit the excellent [Learn Layout](http://learnlayout.com/) step-by-step tutorial.

This will give you all everything you need and also has a section on Flexbox.

As mentioned in the Wikipedia article there are many approaches to solving the HG layout. 

I recommend trying with float and position absolute for the footer. HTML tables are not a “valid” solution!

You should be able to get close. Make sure to test with varying amounts of content in the columns and resizing your browser so vertical scrolling is activated.

The main problem that remains after getting the layout working is that the column colors do not extend to full height. 

