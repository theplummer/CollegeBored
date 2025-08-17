# CollegeBored
A script to retrieve answers on AP Classroom assignments and skip videos.

Source code is obfuscated to make it more difficult for CollegeBoard to patch the hack. But you know what? Instead of trying to patch every method of cheating, just rebuild the education system from the ground up!


HOW TO RUN
----------
* To run, log in to AP Classroom, go to a class, and navigate to the assignments page. 

* Do Ctrl+Shift+J (or right-click and hit Inspect Element, and click Console on the top).

* Copy all the code in the <a href="https://github.com/theplummer/CollegeBored/blob/main/CollegeBored.js">CollegeBored.js</a> file.

* Then paste the code you copied in the console, then press enter. Voila! The hack has been activated!

Alternatively, you can install this as a script in Tampermonkey.


HOW TO USE
----------
When you navigate to an assignment, there should be a lightbulb icon on the right. When you click it, it should highlight the correct answer and/or show you in a popup box of any other correct answers (including those that aren't visible to the page). If for some reason it's not highlighting anything and not alerting you anything, please go into the console (mentioned before), and type "window.rawAnswers = true;", then press Enter. You should now get all your answers in a popup box, which is more reliable but may make some answers more difficult to read.
<br>


When you navigate to a video, next to the close button there should be a button with a "fast forward" icon. Click it, and it will skip the video.

