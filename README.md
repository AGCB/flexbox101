# flexbox101
agcb trying to understand flexbox




##...like shoes hanging from Telephone Wires
A useful analogy for me has been a wooden box w/ a 
string tied across from one end to the other.
Beads are hanging from the string like shoelaces on Electric Wires. 
The Box is the Parent.
The String is the Main Axis and the
beads on the string represent the children.
The Parent Container and It's Children.
It's children that live on a string.


This, with CSSGrid and the Box Module are the current and near-future.

Starting on the next line i will lay out all possible declarations...
#First the Parent Containers.
<ol>
<li>display: flex; /* or inline-flex */</li>
<li>flex-direction: row | row-reverse | column | column-reverse;</li>
<li>flex-wrap: nowrap | wrap | wrap-reverse;</li>

<li>justify-content: flex-start | flex-end | center | space-between | space-around;</li>
<li>align-items: flex-start | flex-end | center | baseline | stretch;</li>
<li>flex-flow: row wrap;</li>
</ol>

#Now the Children.
<ol>
	<li>order: <integer>;</li>
	<li>flex-grow: <number>; /* default 0 */</li>
	<li>flex-shrink: <number>; /* default 1 */</li>
	<li>flex-basis: <length> | auto; /* default auto */</li>
	<li> align-self: auto | flex-start | flex-end | center | baseline | stretch;</li>
	<li>flex: none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]</li>

</ol>

# Both ending w/ the ShortHands
<ul>
	<li>One for the Children, and One for the Parent.</li>
	<li>Flex direction and flex wrap can be combined with the shorthand property FLEX-FLOW</li>
	<li>Grow, Shrink, and Basis can be done as simply....FLEX:</li>
</ul>



### Contributions
Many thanks to [thomaspark](https://github.com/thomaspark/flexboxfroggy), [Chris](https://css-tricks.com/snippets/css/a-guide-to-flexbox/), and [estelle](https://github.com/estelle) for making things a bit more clear.

I have also found this [CheatSheet] (http://www.sketchingwithcss.com/samplechapter/cheatsheet.html#center) online.



## Documentation
flexbox docs can be found at [W3C](https://www.w3.org/TR/css-flexbox-1/)



