# flexbox101
agcb trying to understand flexbox

##Deciding on Ideas.
A useful analogy for me has been a wooden box w/ a string tied across from one end
to the other. Beads on the string represent the children.They are the plants or shoes strung on a telephone wire.
We imagine the telephone wire as the Main Axis.... A vertical string would be called the Cross Axis.
The Parent Container and It's Children.
It's children that live on a wire.
This can be a way to categorize the flexboxLanguage. 

Starting on the next line i will lay out all possible declarations...
#First the Parent Containers.
<ol>
<li>display: flex; /* or inline-flex */</li>
<li>flex-direction: row | row-reverse | column | column-reverse;</li>
<li>flex-wrap: nowrap | wrap | wrap-reverse;</li>
<li>justify-content: flex-start | flex-end | center | space-between | space-around;</li>
<li>align-items: flex-start | flex-end | center | baseline | stretch;</li>
</ol>

#Now the Children.
<ol>
	<li>order: <integer>;</li>
	<li>flex-grow: <number>; /* default 0 */</li>
	<li>flex-shrink: <number>; /* default 1 */</li>
	<li>flex-basis: <length> | auto; /* default auto */</li>
	<li>flex: none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]</li>
	<li> align-self: auto | flex-start | flex-end | center | baseline | stretch;</li>
</ol>




### Contributions
Many thanks to [thomaspark](https://github.com/thomaspark/flexboxfroggy), [Chris](https://css-tricks.com/snippets/css/a-guide-to-flexbox/), and [estelle](https://github.com/estelle) for making things a bit more clear.



## License
flexbox101 is licensed under the [MIT license.](https://github.com/agcb/flexbox101/LICENSE.txt)

