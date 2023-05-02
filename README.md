Download Link: https://assignmentchef.com/product/solved-cosc-54735-program-8
<br>






Write the following phone app. The goal is learn to combine varying complex pieces together into a one program.

You app will do the following. It will have GPS (using fuse APIs) and maps. Inside the app, the user will be able to take a picture. That picture will be shown on the map (via the gps location for where it was taken). The user will be able to click on a landmark marker and the picture will be displayed again. The information does not have to survive the app closing (ie you don’t have to save the pictures to the filesystem), but can if you want to.

I would suggest, but it is not required:

The app displays the map as default screen with the GPS running. The user can then use something like FAB, a menu, BottomNavigationView, or even a Navigation drawer layout to start the picture taking process, which is likely a call to a “camera” fragment/activity. Once the picture has been returned the map (and location is determined), then a location marker is placed on the map at the current GPS location. When the user clicks on the location marker, it brings up the picture for the user see (which again, is likely a call to another activity or a dialog).

<strong>PROGRAM REQUIREMENTS:</strong>

You must use Google Maps API, Fuse API (not straight gps), and camera. Everything else is up to you to decide how to implement it, but it should be easy for the grader to use.

<strong>GRADUATE only section:</strong>

You <strong>can not</strong> use the camera intent, instead you must implement the camera picture taking in your app.

<strong>TURN IN and GRADING:</strong>

Hard copy:

<ol>

 <li>A copy page with Name, program #2, cosc 4735, a repo name (see github and below for your repo name).</li>

</ol>

Soft copy:

<ol>

 <li>Use this link to create your repo <a href="https://classroom.github.com/a/2Y639Pop">https://classroom.github.com/a/2Y639Pop</a></li>

 <li>Upload the project to your repo</li>

 <li>Upload your debug.keystore and default.keyset (found in c:users&lt;username&gt;.android) to the base directory of the repo. So the grader doesn’t have to create new API keys to grade the assignment.</li>

 <li>Create/Edit the <a href="http://readme.md">md</a> file, add the following:</li>

</ol>

o Course number 4010 or 5010

o Name

o how to run the program (this is likely very simple for program 1),

o which phone/emulator to run on including special information like android version (ie v4.4) and screen size.

<ul>

 <li>Or if you are using the borrowed, phone, Nexus 5X or Pixel</li>

</ul>




<ol start="5">

 <li>Lastly ensure everything has uploaded to the github website and not just the local repo. Code will be graded on correctness, comments, and coding style.</li>

</ol>