Download Link: https://assignmentchef.com/product/solved-cs2261-homework2-pong
<br>
<strong>Purpose:</strong>​ To build a simple game in Mode 3 to further your understanding of: inputs to the GBA, collision detection and reaction, C basics, and drawing in Mode 3. <strong> </strong>

<strong>Instructions: </strong>

For this homework, you will recreate the game “<strong>Pong</strong>​     ” in Mode 3.  Review the ​      <em>Requirements</em>​ section on the succeeding page for an explicit list of what we expect as the base requirements. The basic idea is as follows:

There are two different paddles on opposite sides of the screen that can be controlled through user input. A ball moves around the screen and bounces off of the paddles. If a player misses the ball, the opposing player gets a point. The game ends when a player reaches 3 points, and that player wins!

To get an idea of what the gameplay should look like, watch this video: <a href="https://www.youtube.com/watch?v=fiShX2pTz9A&amp;ab_channel=andys-arcade">https://www.youtube.com/watch?v=fiShX2pTz9A&amp;ab_channel=andys-arcad</a>

<a href="https://www.youtube.com/watch?v=fiShX2pTz9A&amp;ab_channel=andys-arcade">e</a><a href="https://www.youtube.com/watch?v=fiShX2pTz9A&amp;ab_channel=andys-arcade">.</a><u>​</u> Of course your game is not expected to look exactly like the original pong (it can if you’d like), but the basic gameplay should still be recreated.




<strong>Requirements:  </strong>

Your ​<em>game</em>​ must have the following:

<ul>

 <li>Two paddles that can collide with the ball and move meaningfully through <em>intuitive </em>​user input controls (e.g. up/down &amp; A/B)

  <ul>

   <li>If the ball collides with a paddle OR the top or bottom of the screen, it must “bounce off” and change direction. ​<strong>Note</strong>​: If you decide to change the orientation of the paddles to be at the top and bottom of the screen, then the ball should bounce off of the left and right sides of the screen</li>

  </ul></li>

 <li>If the ball is missed by a paddle and hits the edge of the screen, the opposing player gets a point</li>

 <li>An end state

  <ul>

   <li>The game should end once any of the two players reaches 3 points</li>

  </ul></li>

</ul>

○ You do not have to have anything happen once you reach the end state, as long as it can be understood that you have reached an end to the game

<ul>

 <li>A ​<strong>txt</strong>​ file

  <ul>

   <li>An instruction manual (of sorts) that tells a player how to play your game</li>

  </ul></li>

</ul>

○ Include which buttons are used for controlling the paddles

<ul>

 <li>Only a​ ​<strong>minimal </strong>​<strong>amount of flicker </strong></li>

</ul>

Your ​<em>code</em>​ must have the following:

<ul>

 <li><strong>Multiple .c </strong>​files</li>

 <li>At least​<strong> one .h</strong>​ file</li>

 <li>Good organization (see tips below)</li>

 <li>Meaningful comments</li>

</ul>

<em>Flair</em>​ ​<strong>(optional)</strong>​:

<ul>

 <li>Add “flair” to your game in order to receive​<strong> up to an additional 5 points </strong>○ Some ideas:</li>

</ul>

■ Add a tally to the screen to indicate how many points each player currently has

■ Draw the ball as something other than a rectangle/square

■ Change the end state so that it indicates which player won







<strong>Tips:</strong>

<ul>

 <li><strong>Start early</strong>​. Never underestimate how long it takes to make a game.</li>

 <li>For collision code, draw pictures. Graph paper is your friend!</li>

 <li>When splitting code between multiple files, put code that will be useful in multiple games in myLib.c, and code specific to this game in main.c or other files.</li>

</ul>

Those other files should be specific to a concept (collision, etc.).

<ul>

 <li>Organize your code into functions specific to what that code does. ​<strong>Your main method should not be very long</strong>​. Use helper functions!</li>

 <li>Having ​update() ​and ​draw() ​functions that you call in ​main() ​is helpful.</li>

 <li>Make sure the order in which you call your functions takes into account waiting for vBlank at the correct​ ​ This will help you to minimize flicker.</li>

 <li>Build upon the myLib.c and myLib.h files we’ve provided in labs.</li>

</ul>