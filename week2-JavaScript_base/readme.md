
<p class="p1"><span class="s1">By making a game, you will gain experience in JavaScript, including variables, arrays, loops and functions.</span></p></span></div><div class="rc-AssignmentInstructionSection" data-reactid="227"><div class="title-container bgcolor-primary-light" data-reactid="228"><span class="body-2-text" data-reactid="229">Instructions</span><span class="rc-MoreOrLess body-2-text color-hint-text" data-reactid="230"><button class="nostyle button-link" data-reactid="231"><!-- react-text: 232 -->less<!-- /react-text --><!-- react-text: 233 --> <!-- /react-text --><i class="cif-chevron-up toggle-arrow" data-reactid="234"></i></button></span></div><div class="instructions-content-container" data-reactid="235"><span data-reactid="236"><p class="p1"><span class="s1"><b>The Task&nbsp;</b></span></p>
<p class="p1"><span class="s1">This assessment task requires you to make a simple color guessing game. This game is similar to the example number guessing game we have discussed on the course, but there are some significant differences. Please see the video for an example walk-through.</span></p>
<p class="p1"><span class="s1">When the web page is loaded, the player sees a message like this.</span></p><img src="https://spark-public.s3.amazonaws.com/phoenixassets/html-css-javascript/Screen%20Shot%202015-08-30%20at%2011.58.42%20PM.png" title="Image: https://spark-public.s3.amazonaws.com/phoenixassets/html-css-javascript/Screen%20Shot%202015-08-30%20at%2011.58.42%20PM.png"><br>







<p class="p1"><span class="s1"></span><br></p>
<p class="p2"><span class="s1">As you can see, the objective of the game is for the player to guess the color which your program is thinking of. The player needs to enter their guess, such as <i>cyan</i>.</span></p><p class="p2"><span class="s1"><br></span></p><img src="https://spark-public.s3.amazonaws.com/phoenixassets/html-css-javascript/Screen%20Shot%202015-08-30%20at%2011.59.49%20PM.png" title="Image: https://spark-public.s3.amazonaws.com/phoenixassets/html-css-javascript/Screen%20Shot%202015-08-30%20at%2011.59.49%20PM.png"><br>







<p class="p1"><span class="s1"></span><br></p>
<p class="p2"><span class="s1">&nbsp;A response from the browser will then be shown.</span></p>
<p class="p2"><span class="s1">1.<span class="Apple-tab-span">	</span>If the color entered by the player is not in the array of colors used by the game, an appropriate message like this is shown:</span></p><p class="p2"><span class="s1"><br></span></p><img src="https://spark-public.s3.amazonaws.com/phoenixassets/html-css-javascript/Screen%20Shot%202015-08-31%20at%2012.01.06%20AM.png" title="Image: https://spark-public.s3.amazonaws.com/phoenixassets/html-css-javascript/Screen%20Shot%202015-08-31%20at%2012.01.06%20AM.png"><br>







<p class="p1"><span class="s1">2.<span class="Apple-tab-span">	</span>If the color entered by the player is in the list of colors used by the game but the color entered by the player is alphabetically higher than the answer, an appropriate message like this is shown:</span></p><p class="p1"><span class="s1"><br></span></p><img src="https://spark-public.s3.amazonaws.com/phoenixassets/html-css-javascript/Screen%20Shot%202015-08-31%20at%2012.02.19%20AM.png" title="Image: https://spark-public.s3.amazonaws.com/phoenixassets/html-css-javascript/Screen%20Shot%202015-08-31%20at%2012.02.19%20AM.png"><br>







<p class="p1"><span class="s1">3.<span class="Apple-tab-span">	</span>If the color entered by the player is in the list of colors used by the game but the color entered by the player is alphabetically lower than the answer, an appropriate message like this is shown:</span></p><p class="p1"><span class="s1"><br></span></p><img src="https://spark-public.s3.amazonaws.com/phoenixassets/html-css-javascript/Screen%20Shot%202015-08-31%20at%2012.03.37%20AM.png" title="Image: https://spark-public.s3.amazonaws.com/phoenixassets/html-css-javascript/Screen%20Shot%202015-08-31%20at%2012.03.37%20AM.png"><br>







<p class="p1"><span class="s1">4.<span class="Apple-tab-span">	</span>If the color entered by the player is correct the web page background is changed to that color and an appropriate message is shown:</span></p><p class="p1"><span class="s1"><br></span></p><img src="https://spark-public.s3.amazonaws.com/phoenixassets/html-css-javascript/Screen%20Shot%202015-08-31%20at%2012.04.51%20AM.png" title="Image: https://spark-public.s3.amazonaws.com/phoenixassets/html-css-javascript/Screen%20Shot%202015-08-31%20at%2012.04.51%20AM.png"><br>







<p class="p1"><span class="s1"></span><br></p>
<p class="p2"><span class="s1">This is what a web page looks like when the message is shown on top of a web page where the background has been changed to orange.</span></p><p class="p2"><span class="s1"><br></span></p><img src="https://spark-public.s3.amazonaws.com/phoenixassets/html-css-javascript/Screen%20Shot%202015-08-31%20at%2012.06.12%20AM.png" title="Image: https://spark-public.s3.amazonaws.com/phoenixassets/html-css-javascript/Screen%20Shot%202015-08-31%20at%2012.06.12%20AM.png"><br><br>







<p class="p1"><span class="s1"><b>A Flowchart</b></span></p>
<p class="p2">Here is a flowchart for the game, showing the basic behavior.<br></p><p class="p2"><br></p><img src="https://spark-public.s3.amazonaws.com/phoenixassets/html-css-javascript/Screen%20Shot%202015-08-31%20at%2012.07.48%20AM.png" title="Image: https://spark-public.s3.amazonaws.com/phoenixassets/html-css-javascript/Screen%20Shot%202015-08-31%20at%2012.07.48%20AM.png"><br>







<p class="p1"><span class="s1"><b>A Note on Alphabetic Order</b></span></p>
<p class="p1"><span class="s1">In the game we use alphabetical order to provide hints to the player. Here are some examples of two strings where the first string is alphabetically higher than the second string. <br>
</span></p>
<p class="p1"></p><ul><li>sat &gt; sad<br></li><li>bags &gt; bag<br></li><li>thin &gt; fat&nbsp;<br></li><li>good &gt; bad<br></li></ul><p></p>



<p class="p2"><span class="s1"></span><br></p>
<p class="p1"><span class="s1">Here are some examples of two strings where the first string is alphabetically lower than the second string. <br>
</span></p>
<p class="p1"></p><ul><li>rag &lt; rat<br></li><li>bit &lt; bite&nbsp;<br></li><li>food &lt; water<br></li><li>potato &lt; potatoes &nbsp;<br></li></ul><p></p>



<p class="p2"><span class="s1"></span><br></p>
<p class="p1"><span class="s1">In JavaScript you can easily determine whether one string is alphabetically higher or lower than another string e.g.</span></p>
<p class="p3"><span class="s1">&nbsp; &nbsp; var string1="hat";</span></p>
<p class="p3"><span class="s1">&nbsp; &nbsp; var string2="hit";</span></p>
<p class="p3"><span class="s1">&nbsp; &nbsp; if (string1 &gt; string2)&nbsp;</span></p>
<p class="p3"><span class="s1">&nbsp; &nbsp; &nbsp; &nbsp; alert("string1 is alphabetically higher");</span></p>
<p class="p3"><span class="s1">&nbsp; &nbsp; else&nbsp;</span></p>
<p class="p3"><span class="s1">&nbsp; &nbsp; if (string1 &lt; string2)&nbsp;</span></p>
<p class="p3"><span class="s1">&nbsp; &nbsp; &nbsp; &nbsp; alert("string1 is alphabetically lower");</span></p>
<p class="p4"><span class="s1"></span><br></p>
<p class="p1"><span class="s1">Wikipedia has a good discussion of alphabetical order at <i><a href="https://en.wikipedia.org/wiki/Alphabetical_order#Basic_order_and_example" title="Link: https://en.wikipedia.org/wiki/Alphabetical_order#Basic_order_and_example">https://en.wikipedia.org/wiki/Alphabetical_order#Basic_order_and_example</a>&nbsp;</i></span></p><p class="p1"><span class="s1"><i></i></span><br></p><p class="p2"><span class="s1"><b>Technical Overview</b></span></p><p class="p2"><span class="s1">This task is similar to the example number guessing game we have discussed on the course. However, that game involved the generation of one single random number, and no arrays were used in that game. This assessment task requires an array of colors e.g. <br>
<br>
</span><span class="s2">&nbsp; &nbsp; colors=["aqua", "black", "cyan", </span><span class="s3">. . .</span><span class="s2"> ];</span></p><p class="p3">The target color which the player has to guess is a randomly selected color from that array.<br><span class="s1"></span></p><p class="p1">The names must be HTML color names. This is so that when the player successfully guesses the color it can be used for the web page background color, to show what the color actually looks like.</p><p class="p2"><span class="s1">You can find a list of HTML color names at <a href="http://www.w3schools.com/html/html_colornames.asp"><span class="s4">http://www.w3schools.com/html/html_colornames.asp</span></a><br>
and other places on the web. Some of them are regular English names such as “red”, “black”, and so on, but there are also more unusual color names you can use such as “DarkSeaGreen” and “RebeccaPurple”.</span></p><p class="p2"><span class="s1">In your array the colors do not have to be listed in alphabetical order. However, in terms of playing the game, when the list of colors is shown to the player it would be more helpful if they are in alphabetical order. If you wish, you can easily use JavaScript to sort them, as we have discussed on the course.</span></p><p class="p2"><span class="s1">One way to set the background color of a web page is&nbsp;</span></p><p class="p3">myBody=document.getElementsByTagName("body")[0];<br><span class="s1"></span></p><p class="p1"><span class="s1">























</span></p><p class="p4"><span class="s1">myBody.style.background=<i>name_of_color</i>;</span></p><p class="p1"><span class="s1"><b><br></b></span></p><p class="p1"><span class="s1"><b>JavaScript Content</b></span></p><p class="p1"><span class="s1">Your file is likely to have JavaScript content which is similar to the number guessing game we have discussed before. However, one difference is that for this task you are required to put your JavaScript and HTML in <b>one single file</b>, unlike the number guessing game which used a separate file for HTML and JavaScript for better management. The only reason for the need to use one file in this task is to make marking your work and the work of others much easier.</span></p><p class="p1"><span class="s1">Here is the likely JavaScript content of your game.</span></p><p class="p1"><span class="s1">1. Declaration of global variables and array e.g. </span><span class="s2">color[]</span><span class="s1">.<br>
&nbsp; &nbsp; Setting the initial values.</span></p><p class="p1"><span class="s1">2. The main game function - </span><span class="s2">do_game()</span></p><p class="p1"><span class="s1">&nbsp; &nbsp; 2.1. Generate a random number in the range <br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; [0, length of array-1]</span></p><p class="p1"><span class="s1">&nbsp; &nbsp; 2.2. Assign </span><span class="s2">target</span><span class="s1"> to the random color in the array</span></p><p class="p1"><span class="s1">&nbsp; &nbsp; 2.3. A while loop, which repeats until <i>finished</i> is true:<br>
&nbsp; &nbsp; &nbsp; &nbsp; - ask the player for their guess using </span><span class="s2">prompt()</span></p><p class="p1"><span class="s1">&nbsp; &nbsp; &nbsp; &nbsp; - increase a variable </span><span class="s2">count</span><span class="s1"> by 1</span></p><p class="p1"><span class="s1">&nbsp; &nbsp; &nbsp; &nbsp; - check the player’s guess using </span><span class="s2">check_guess()</span></p><p class="p3"><span class="s1">&nbsp;&nbsp;</span><span class="s1">3. Check the input - </span><span class="s2">check_guess()</span></p><p class="p1"><span class="s1">&nbsp; &nbsp; Check whether the player's guess is:&nbsp;</span></p><p class="p1"><span class="s1">&nbsp; &nbsp; 3.1. not a color in the array:<br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; show an appropriate message and return <i>false</i></span></p><p class="p1"><span class="s1">&nbsp; &nbsp; 3.2. alphabetically higher than the target:<br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; show an appropriate message and return <i>false</i></span></p><p class="p1"><span class="s1">&nbsp; &nbsp; 3.3. alphabetically lower than the target:<br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; show an appropriate message and return <i>false</i></span></p><p class="p1"><span class="s1">&nbsp; &nbsp; 3.4. correct:<br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; change the background color to the target,&nbsp;</span></p><p class="p1"><span class="s1">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; show an appropriate message <br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; which includes the total number of guesses&nbsp;</span></p><p class="p1"><span class="s1">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; stored in variable </span><span class="s2">count</span><span class="s1">,</span></p><p class="p4"><span class="s1">






























</span></p><p class="p1"><span class="s1">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;return <i>true</i></span></p><p class="p2"><span class="s1">The numbers shown above (such as 2.3) are simply to give you an idea of an appropriate order for the code. You don’t have to use those numbers in any particular way and you don’t have to follow exactly the order shown, although it may help you to do so.</span></p><p class="p1">See the flowchart image above for more guidance.<br><span class="s1"></span></p><p class="p1">No HTML content is needed for this game, except for a <i>body</i> element which is used to show the color when the player has successfully guessed it.</p><p class="p1"><span class="s1">















</span></p><p class="p2"><span class="s1">To start the game one way is to use a body <i>onload</i> event, in the way that we have discussed on the course. This can be used to trigger the execution of </span><span class="s2">do_game()</span><span class="s3">.</span></p><p class="p2"><span class="s3"><br></span></p><p class="p1"><strong>Which Browser to Use</strong></p><p class="p1">The game was originally developed using the Chrome browser. We have checked that it works in all modern browsers. However, Internet Explorer only allows a small amount of text to be shown in a <i>prompt()</i> message, which means Internet Explorer is not suitable for this project.</p><p class="p2"><b>Discussion Video</b><br></p><p class="p2">Please watch the accompanying video, which shows and discusses the completed task.</p><p class="p1"><b>What to Submit</b></p><p class="p2">This assessment task is closely related to the number guessing game discussed on the course. The code for that game has also been released in the system. You are encouraged to watch the video and look at the code, in order to learn from it.<br><b></b></p><p class="p2">There are 2 parts of this assessment. You need to submit 1 file for part 1 and 1 file for part 2.<br></p><p class="p2">For both part 1 and part 2 you can only submit one single HTML file, which includes the JavaScript code within it. That means there are no links to external JavaScript files or any other files in this assessment task.</p><p class="p2">Part 1 is a simple version of the game. When the file is loaded a color is randomly selected from an array of colors and a loop begins which repeatedly asks the player what the color is. However, no feedback is given to the player depending on what he/she enters. The loop simply finishes when the player enters the correct color. Make sure you save a copy of this as, for example, <i>part1.html</i>, before you move on to the next part.</p><p class="p1">For Part 2, take your part 1 file and extend it by completing the entire game. Make sure you save a copy as, for example, <i>part2.html.</i></p><p class="p2">Please note that this assignment does not require any style rules or HTML content (apart from a <i>body)</i>, but you are welcome to add them if you wish.<br><i></i></p><p class="p2">Here are the more specific requirements and further information for both parts.<br></p><p class="p2"><strong>Part 1 Requirements.</strong><br></p><p class="p2">







</p><ul class="ul1">
<li class="li1">Your part 1 work should be a simple ‘game’ which uses a loop. In the loop, the player is shown the list of colors and is asked for their guess. However, no feedback is given to the player based upon their input. In other words, the function <span class="s1">check_guess()</span> is not required in part 1. The loop finishes when the player enters the correct color.</li>
<li class="li1">A summary:</li>
<ul class="ul1">
<li class="li1">Include a list of colors in an array</li>
<li class="li1">In function <span class="s1">do_game()</span>:</li>
<ul class="ul1">
<li class="li1">Randomly select one of those colors in the array as the <span class="s1">target</span></li>
<li class="li1">Display the <span class="s1">target</span> (to help with debugging and marking) e.g. <span class="s1">alert(target);</span></li>
<li class="li1">Go into a loop which</li>
<ul class="ul1">
<li class="li1">Shows the array of colors and asks the player for their guess</li>
<li class="li1">Stops if the player’s guess is the same as the target</li>
</ul>
</ul>
</ul>
</ul><p class="p2">







</p><p class="p1"><strong>Part 2 Requirements.</strong></p><p class="p1">







</p><ul class="ul1">
<li class="li1">Part 2 is the completed game, as described in the instructions and demonstrated in the accompanying video.</li>
<li class="li1">Here is a summary:</li>
<ul class="ul1">
<li class="li1">Include a list of colors in an array</li>
<li class="li1">In function <span class="s1">do_game()</span>:</li>
<ul class="ul1">
<li class="li1">Randomly select one of those colors in the array as the <span class="s1">target</span></li>
<li class="li1">Optionally: display the <span class="s1">target</span> (to help with debugging and marking) e.g. <span class="s1">alert(target);</span></li>
<li class="li1">Go into a loop which</li>
<ul class="ul1">
<li class="li1">Shows the array of colors and asks the player for their guess</li>
<li class="li1">Using the function <span class="s1">check_guess()</span>:</li>
<li class="li1">Displays a message such as ‘I don’t recognize that color!’ If the text entered by the player is not in the array of colors, OR:</li>
<li class="li1">Displays a message such as ‘Your input is alphabetically higher than mine!’ if that is true, OR:</li>
<li class="li1">Displays a message such as ‘Your input is alphabetically lower than mine!’ if that is true, OR:</li>
<li class="li1">If the player’s input is the same as the target: changes the web page background color to the target color and displays a message which includes the total number of guesses such as ‘You are right! You took 8 guesses!’&nbsp;</li>
<li class="li1">Stops if the player’s input is the same as the target</li>
