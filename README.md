#CSS for Developers

This is part of the CSS for Developers series.

  - [Part 1 - The Real Problems](https://docs.google.com/presentation/d/16-Y2qcXDytMDvBujmTY05OQU4sbz4UnENn_JKT938oA/)
  - [Part 2 - Holy Grail and SCSS](https://docs.google.com/presentation/d/16-Y2qcXDytMDvBujmTY05OQU4sbz4UnENn_JKT938oA/)
  - [Part 3 - Modular CSS](https://docs.google.com/presentation/d/16-Y2qcXDytMDvBujmTY05OQU4sbz4UnENn_JKT938oA/edit#slide=id.p)

The presentations are also available in PDF together with notes in the /pdf folder. The notes contain links to useful resources and some exercises.

##Holy Grail Layout

The Holy Grail layout is an excellent way to learn the basics of CSS layout.

We are going to implement the Holy Grail layout. The HG layout is a historic web site layout problem. The requirement is a fluid layout that has a width header, and footer and a main content area comprising three columns (navigation, content, aside).  The header and footer should move with the content when scrolled vertically - in other words they are not fixed in position.

There are many solutions with mixed results  

[Holy Grail Layout](http://en.wikipedia.org/wiki/Holy_Grail_%28web_design%29)

One of the original Holy Grail layout articles: [A List Apart - Holy Grail](http://alistapart.com/article/holygrail)

We’ll tackle the problem by first attempting to solve it using traditional (“old school”) CSS, then we’ll update our CSS using SCSS to learn some of the simple and useful features. We also solve the problem without flexbox. Finally we’ll solve the problem using modern CSS and HTML by using flexbox.

The Holy Grail layout is not really that useful today as designs have progressed and adapted to needs of varied devices.

##SCSS (Sass)

To work with the SCSS examples you require a SCSS pre-processor. Popular IDEs support SCSS via plug-ins. Alternatively you can install Node and use a Gulp task.
