# transitions-implementation

<h2>About</h2>
<p>
    This is an implementation of an algorithm described in a paper written by <a href="https://web.mit.edu/wongb/www/origami/">Brandon Wong</a> and <a href="https://erikdemaine.org/">Erik Demaine</a>, titled <i>Algorithmic Transitions between Parallel Pleats</i>, published in 8OSME (the 8th International Meeting on Origami in Science, Mathematics and Education). This implementation was built by Brandon Wong. The source code for this program can be found <a href="https://github.com/theplantpsychologist/transitions-implementation">here</a>.
    <br><br>
    This algorithm constructs a flat foldable transition between two sets of parallel creases across a common ridge crease, which is equivalent to a ridge level shifter but with aribitrary crease positions. In order for a flat foldable transition to exist, the alternating sums of the x-intercepts of creases must be equal for the two sets. For example, if set A has creases located at [1,2,3,4] and set B has creases located at [2,3,4,5], then the alternating sums are 1-2+3-4 = 2-3+4-5 and a flat foldable transition exists.
</p>
<h2>Instructions</h2>
<p>
    First, enter the positions of the creases in the top and bottom sets. Alternatively, you can select a preset test case to see a variety of cases the algorithm can handle. Then, enter the &theta; angle that the parallel creases make with the common ridge, as well as the &beta;<sub>1</sub> angle that initializes the vertex placements. Check the box if you would like to generate a gif of the construction process. Finally, click "Build transition" to generate the crease pattern. The crease pattern will be displayed on the canvas.

    You can save the transition crease pattern by right clicking on the canvas and selecting "Save Image As..." which will save the canvas as a .png file. You can do the same to save the gif, if generated. You can also download the crease pattern as a .CP or .FOLD file by selecting the respective buttons at the bottom of the page.
</p>
<h2>External libraries</h2>
<ul>
    <li><a href="http://paperjs.org/">Paper.js</a> - For vector graphics on top of the HTML5 Canvas</li>
    <li><a href="https://jnordberg.github.io/gif.js/">GIF.js</a> - For gif generation</li>
    
</ul>