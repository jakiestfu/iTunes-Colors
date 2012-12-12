iTunes-Colors
=============

Recreates the color-effect used in iTunes

This is based off of the work of Charles Leifer, and his incredible article on finding dominant colors using Python and K-Means (as well as Javascript and HTML5) can be found at <a href="http://charlesleifer.com/blog/using-python-and-k-means-to-find-the-dominant-colors-in-images/" target="_blank">http://charlesleifer.com/blog/using-python-and-k-means-to-find-the-dominant-colors-in-images/</a>.

I've taken the liberty of wrapping up his javascript port in a nice little object that uses deferrence and the when property to give things a nice callback-flow.

## Usage:

`````
Colors.analyze(imgElement, function(colors){
  console.log(colors);
});
`````

jQuery is required, but it is not used much, so you can hack it off if you'd like (of course).
