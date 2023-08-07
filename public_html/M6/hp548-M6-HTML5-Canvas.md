<table><tr><td> <em>Assignment: </em> HW HTML5 Canvas Game</td></tr>
<tr><td> <em>Student: </em> Harsh Patel (hp548)</td></tr>
<tr><td> <em>Generated: </em> 7/1/2023 6:47:40 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT202-450-M23/hw-html5-canvas-game/grade/hp548" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Create a branch for this assignment called&nbsp;<em>M6-HTML5-Canvas</em></li><li>Pick a base HTML5 game from&nbsp;<a href="https://bencentra.com/2017-07-11-basic-html5-canvas-games.html">https://bencentra.com/2017-07-11-basic-html5-canvas-games.html</a></li><li>Create a folder inside public_html called&nbsp;<em>M6</em></li><li>Create an html5.html file in your M6 folder (do not put it in Project even if you're doing arcade)</li><li>Copy one of the base games (from the above link)</li><li>Add/Commit the baseline of the game you'll mod for this assignment&nbsp;<em>(Do this before you start any mods/changes)</em></li><li>Make two significant changes<ol><li>Static changes like hard-coded colors/values will not count at all (i.e., changing shapes/colors/values that are globally defined and set only once.</li><li>Direct copies of my class example changes will not be accepted (i.e., just having an AI player for pong, rotating canvas, or multi-ball unless you make a significant tweak to it)</li><li>Significant changes are things that change with game logic or modify how the game works. Static changes like hard-coded colors/values will not count at all (i.e., changing shapes/colors/values that are globally defined and set only once). You may however change such values through game logic during runtime. (i.e., when points are scored, boundaries are hit, some action occurs, etc)</li></ol></li><li>Evidence/Screenshots<ol><li>As best as you can, gather evidence for your first significant change and fill in the deliverable items below.</li><li>As best as you can, gather evidence for your significant change and fill in the deliverable items below.</li><li>Remember to include your ucid/date as comments in any screenshots that have code</li><li>Ensure your screenshots load and are visible from the md file in step 9</li></ol></li><li>In the M6 folder create a new file called m6_submission.md</li><li>Save your below responses, generate the markdown, and paste the output to this file</li><li>Add/commit/push all related files as necessary</li><li>Merge your pull request once you're satisfied with the .md file and the canvas game mods</li><li>Create a new pull request from dev to prod and merge it</li><li>Locally checkout dev and pull the merged changes from step 12</li></ol><p>Each missed or failed to follow instruction is eligible for -0.25 from the final grade</p></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Game Info </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> What game did you pick to edit/modify?</td></tr>
<tr><td> <em>Response:</em> <p>I have choose the Collect the Squares game for this assignment because it&#39;s<br>easy and fun to play. So, it caught my attention to further improve<br>this game.<br></p><br></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add the direct link to the html5.html file from Heroku Prod (i.e., https://mt85-prod.herokuapp.com/M6/html5.html)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://appp3-aa70a3e4e8f5.herokuapp.com"> https://hp548-appp3-f02b0e461144.herokuapp.com </a> </td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the pull request link for this assignment from M6-HTML5-Canvas to dev</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/hpatel544/Module6_Assignment/pull/1">https://github.com/hpatel544/Module6_Assignment/pull/1</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Significant Change #1 </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Describe your change/modification</td></tr>
<tr><td> <em>Response:</em> <div>Obstacles:&nbsp;</div><div><ul><li>I added obstacles represented by blue rectangles.&nbsp;</li><li>When the player's square collides with an<br>obstacle, the score decreases by 1, and the countdown timer decreases by 5<br>seconds.&nbsp;</li><li>The obstacle is also respawned at a random position on the canvas.</li></ul></div><br></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshot of the change while playing (try your best as some changes may be nearly impossible to capture)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fhp548%2F2023-07-01T13.39.112023-07-01%20(1).png.webp?alt=media&token=489cfc79-c171-4be2-ae38-49c4638ac280"/></td></tr>
<tr><td> <em>Caption:</em> <p>The initial startup of the game, the blue one is the obstacle and<br>the yellow one is the box to increase time up to 5 seconds<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fhp548%2F2023-07-01T13.39.412023-07-01%20(2).png.webp?alt=media&token=9118fc49-0c11-447a-9d59-e55c81041ddd"/></td></tr>
<tr><td> <em>Caption:</em> <p>I&#39;ve touched the obstacle and there is one minus from my whole score<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshot of the relevant lines of code that implement your change (make sure your ucid and the date are shown in comments) In the caption briefly describe/explain how the code snippet works.</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fhp548%2F2023-07-01T13.40.54image.png.webp?alt=media&token=be229812-5310-47e2-af9e-4b76f8e11939"/></td></tr>
<tr><td> <em>Caption:</em> <p>added the variables for obstacles<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fhp548%2F2023-07-01T13.41.36image.png.webp?alt=media&token=ac363e5f-d95e-4d11-bef3-6229a83ed9f1"/></td></tr>
<tr><td> <em>Caption:</em> <p>added move obstacle function. Also called them in the appropriate position (in the<br>start game function)<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fhp548%2F2023-07-01T13.42.09image.png.webp?alt=media&token=cb85afc6-82a2-49e5-a92d-593bc10a84dd"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added collide with obstacle<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fhp548%2F2023-07-01T13.42.48image.png.webp?alt=media&token=86e8cf82-824f-451f-802f-688a0342f4c5"/></td></tr>
<tr><td> <em>Caption:</em> <p>created for element obstacle<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Significant Change #2 </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Describe your change/modification</td></tr>
<tr><td> <em>Response:</em> <p>Yellow Boxes as Time Bonuses:<div><ul><li>&nbsp;I introduced a new time bonus represented by yellow<br>boxes.</li><li>When the player&#39;s square collides with the bonus, the score increases by 1,<br>and the countdown timer increases by 5 seconds.&nbsp;</li><li>The bonus is respawned at a<br>random position on the canvas.&nbsp;</li></ul></div><br></p><br></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshot of the change while playing (try your best as some changes may be nearly impossible to capture)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fhp548%2F2023-07-01T13.43.432023-07-01.png.webp?alt=media&token=e3cf33a2-553d-4087-bfab-769b2160ce23"/></td></tr>
<tr><td> <em>Caption:</em> <p>I have taken a few yellow boxes and you can see my time<br>has been significantly increased<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshot of the relevant lines of code that implement your change (make sure your ucid and the date are shown in comments) In the caption briefly describe/explain how the code snippet works.</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fhp548%2F2023-07-01T13.44.07image.png.webp?alt=media&token=8f092de2-4df8-46ec-984c-926400aa8015"/></td></tr>
<tr><td> <em>Caption:</em> <p>added the variables for bonus<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fhp548%2F2023-07-01T13.45.13image.png.webp?alt=media&token=85d57113-4a25-4d2e-98b0-72a4f5d1fa76"/></td></tr>
<tr><td> <em>Caption:</em> <p>added move bonus function. Also called them in the appropriate position (in the<br>start game function)<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fhp548%2F2023-07-01T13.45.44image.png.webp?alt=media&token=3b4cf7f9-91bb-4621-bb8e-0cd638a1d551"/></td></tr>
<tr><td> <em>Caption:</em> <p>Added collide with bonus<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fhp548%2F2023-07-01T13.46.29image.png.webp?alt=media&token=57c09879-de4b-4dcc-b244-c5f076a6617b"/></td></tr>
<tr><td> <em>Caption:</em> <p>created element for bonus <br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Discuss </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Talk about what you learned during this assignment and the related HTML5 Canvas readings (at least a few sentences for full credit)</td></tr>
<tr><td> <em>Response:</em> <div>I learnt how to organize and reuse code blocks by defining and using<br>functions. Functions enable modular design and enhance the readability, maintainability, and readability of<br>code. I found out how if statements may be used to modify the<br>execution's course depending on specific circumstances. It allows the game to react dynamically<br>to various user inputs and events.&nbsp;</div><div>I also learned, how to configure event listeners<br>to recognize and react to user inputs like keystrokes and mouse clicks. These<br>listeners make the game interactive and provide the user influence over the game's<br>aspects.</div><br></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT202-450-M23/hw-html5-canvas-game/grade/hp548" target="_blank">Grading</a></td></tr></table>
