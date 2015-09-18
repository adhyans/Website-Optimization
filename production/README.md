<h1>How to view this website</h1>
<p>1. Download the zip folder for this project</p>
<p>2. Click on index.html in the main folder to view page.</p>
<h1>Optimizations I made in the pizza.html</h1>
<p>1.I optimized the updatePositions() function in views/js/main.js.
<ul>
	<li>Extracted the variables that kept on repeating</li>
	<li>The values in the leftPositionArray kept on repeating after the 8th cycle so I put them in a array so that browser don't have to calculate again and again.</li>
	<li>The scrollTop variable never changed so it was extracted out of the loop.</li>
</ul>
</p>
<p>2.I decreased the number of pizzas that would load on scroll to 24 from 200 beacuse there were no 200 pizzas on page at any time.</p>
<p>3.I used the will change css property for the mover class because the div kept on changing position after scrolling so I thought it would be better to tell the browser before animations so as to reduce painting.</p>