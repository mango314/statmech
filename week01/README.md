# CALCULATING PI

Werner Krauth in his lecture discusses the Metropolis-Hastings algorithms for sampling shapes.  In this case, the circle. 
He shows us two examples
 * pebbles in the Monte-Carlo beach
 * helicopters landing in the Monte-Carlo helipad
What I didn't catch the first time I hear these lectures in 2013 - these two algorithms are the same - they are computing the same 
number pi.
 * pebbles in the Monte-Carlo beach is equivalent to **rejection sampling** : picking number totally at random and if fits the
 target we accept and otherwise we reject
 * the Monte-Carlo helipad is a type of random walk algorithm were we reject 
For reasons I find rather hard to articulate, I feel digs right into the heart of spin models, which 
Krauth is an expert.  I have gravely understimated him as a master of pedagogy.

### Buffoon Needle Problem

Another very famous way to calculate pi is to do the Buffon Needle Problem.  This experiment involves throwing toothpicks
on a grid and accepting if the line segment intersects the line.  It is also an example of rejection
probablity and the acceptance probability is also pi.  This also leads us into the field of geometric probability (or integral geometry).

* [Integral Geometry and Geometric Probability](http://www.amazon.com/Integral-Geometric-Probability-Cambridge-Mathematical/dp/0521523443)
* [Introduction to Geometric Probability](http://www.amazon.com/Introduction-Geometric-Probability-Lezioni-Lincee/dp/052159362X)

![](http://mathworld.wolfram.com/images/eps-gif/BuffonLaplaceNeedle_700.gif)
