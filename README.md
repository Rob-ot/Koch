I really wanted to make a recursive fractal renderer so I made some koch triangle demos.

Every demo contains a drawLine function that takes a start and end point, drawLine calls itself 4 times to draw each sub-line. It stops recusring when the line it is trying to draw is smaller than detailLevel (usually 1px).

It uses the JavaScript library sylvester for some vector math and other things.
