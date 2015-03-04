## Website Performance Optimization portfolio project


Steps used to Optimize:
- Resized images with photoshop and compressed them using TinyPng.

- Inlined CSS & Google Fonts, I use javascript to load them after the page is displayed to avoid render blocking.

- To speed up scrolling on Pizza.html, I removed any document queries from insode the for loop.
  I created a variable and set it to the top of the page, so the loop doesnt need to make the query for every pizza element.

- To optimize the Pizza resizing, I pretty much did the same step as above. Removed all queries that were not needed in the loop, to outside the loop.

- Minified CSS and Javascript and made the appropriate adjustments to the html files.


Sites used for optimization:

https://tinypng.com/

http://www.minifycss.com/

http://www.minifyjs.com/

https://developers.google.com/speed/pagespeed/insights/

https://developers.google.com/speed/docs/insights/rules


