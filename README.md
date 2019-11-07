
# Let's learn about Android!  <img src="https://cnet4.cbsistatic.com/img/QJcTT2ab-sYWwOGrxJc0MXSt3UI=/2011/10/27/a66dfbb7-fdc7-11e2-8c7c-d4ae52e62bcc/android-wallpaper5_2560x1600_1.jpg" width="48">
These are must-reads:
* Refresh your Java skills [here](https://www.cs.utexas.edu/users/witchel/371M/lectures/01-java-review.pdf)
* Java very minimal code convention that you should follow, read [here](https://web.stanford.edu/class/cs193a/styleguide.shtml)
* Very useful Android development course from Stanford [here](https://web.stanford.edu/class/cs193a/videos.shtml)
* Android fundamentals [here](https://developer.android.com/guide/components/fundamentals)
* Git ignore for Android Studio [here](https://gist.github.com/iainconnor/8605514)
* Install Android Studio from [here](https://developer.android.com/studio/install)

## :warning: Overall Android-lab deliverables 
Completing *Part I*, then extend it by completing Part IIIa and (bonus) PartIIIb. </br>
Your Deadline is __8th November__! </br>
Submit your code on github (using the invitation link for Part I) </br>
Submit on wiseflow a short video that demo your final application, less than 3 min! </br>

## First Android-lab deliverables (old, week 3)
Completing *Part I* is compulsory, completing  *Part IIa* and *Part IIb* will give you the status of an Android ninja. </br>

## Part I: Basic Android skills: Create your first Android app :game_die:
Create an Android project with the name Dice Roller. Select Git as a version control system. 
Each level below should be a separate commit! </br>
Quick summary:  </br>
Level 1: Create an app for rolling a dice. The app shoudld contain a button that when clicked generates and displays a random number. </br>
Level 2:  Then add an input box where the user can enter a number from 1 to 6. Repeat the process above, if the generated dice number is the same as the number in the box, then display Congratulations. </br>
Level 3: Add a text box that displays the user points, e.g the number of times that the user has guessed the number on the dice. </br>
Finally, push your repository to github:  </br>
* Accept the [invitation link](https://classroom.github.com/a/x3PNkMI1)
* Configure your origin remote to point to that link! </br>

Resources that can help you: </br>
Creating a new Android project is explained [here](https://developer.android.com/training/basics/firstapp/creating-project)

## Part IIa: Basic Android skills: Guess the bigger number

Create an Android project with the name Bigger number. Select Git as a version control system. 
Each level below should be a separate commit! </br>
Quick summary:  </br>
Level 1: Create an app with two buttons. Each button displays a random number. The user should click on the number that is bigger </br>
Level 2:  If the user guess is correct, a Congratulation message is displayed!</br>
Level 3: Add a text box that displays the user points, e.g the number of times that the user has guessed correctly whch number is bigger. </br>
Level 4: Add maximum number of lives. When the limit is exhausted, display a toast messgae 'Game over' </br>

## Part IIb: Create a game of bulls and cows :cow2: 
* __Step 1:__ Accept the assignment invitation from this [link](https://classroom.github.com/a/aHANZdgs) </br>
   Accepting the invitation will create a copy of the repository for you. </br>
   The name of the assignement repository will be something like: android-lab-yourusername  </br>
   In the above yourUserName will be your actual github name </br>
   The link to your repository will be: https://github.com/BrunelCS/git-lab-yourUserName </br>
   Again, note that yours will have the same naming convention but instead of yourUserName, there will be your github username </br>
* __Step 2:__ Create the game. The rules of the game are [here](https://en.wikipedia.org/wiki/Bulls_and_Cows) </br>
The game should have at least four commits (1) initial 2) building the UI 3) building the the logic for cows and 4) the logic for bulls)

## Part IIIa:  Let's play D-ICEBREAKERS! 
This exercise builds on Part I. Open the app you built in part I and extend it with: </br>

__Level 4__: Rename the 'Roll the dice button' to 'I am feeling lucky' and Add anotter button 'Let's play D-ICEBREAKERS' </br>
When you click on Roll the dice, the same behaviour as the one in Part I happens </br>
When you click on Let's play D-ICEBREAKERS', a random question from [this list](https://docs.google.com/document/d/1tGVnM7qQ1SEEr1p0EjHz-bTU1h60iVHeReTORE4uqsE/edit?usp=sharing) of questions appears on the screen </br>
__Important__: Separate the code for generating a new number in a new  </br>
method called ```roll_the_dice()```, use this method from the </br>
handlers for the click event for both buttons. </br>
__(bonus)Level 4.5__: Add another button 'Add a new D-icebreaker'. </br>
Clicking on the button takes you on another screen with a text box where you can input a new ice-breaker rule. </br>
There are two nuttons on the screen: cancel and save. Clicking either of them takes you back to the previous screen. </br>
Read here how to start a [new activity](https://developer.android.com/training/basics/firstapp/starting-activity)

## Part IIIb:  Working with external APIs: Share your score on slack! :hash:
__Level 5__: Add a finish button on the main Activity screen, clicking the button sends you to a new screen </br>
On the new screen there must be one button called "Share your score on slack" </br>
When you click the button your current score should be posted on the slack channel #test-android</br>
Hints: </br>
This is the [slack-api](https://github.com/pschroen/slack-api-android) that you should use, </br>
To add this API to your project, you should add it to gradle </br>
Update the manifest file to allow user permissions on have network access and wifi (you need to enable three user-permissions) 
</br>
The full API can be founds [here](https://github.com/allbegray/slack-api), use it for referene to find which method you should use (hint:postMessage)! </br>
To use the API, you should generate a slack token, read how [here](https://slack.com/intl/en-gb/help/articles/215770388-create-and-regenerate-api-tokens) </br>

Still struggling? Wrap the slack-api call in a try-catch block, and observe the error </br>
You cannot start long running tasks (such as network events) from the main UI thread, this is not only a bad practice, but also a dangerous one. 
Check how to solve it [here](http://simpledeveloper.com/network-on-main-thread-error-solution/). You are allowed to implement the hacky solution this time. But only this time! From next week, you should try using the proper one! </br>


## Part IV: Finally, it is time to test your Android knowledge
* Test your android knowledge [here](https://basicversity.com/study/android-programming)
* Make sure that you can: 
  * create a new android project
  * work with widgets and events 
  * switch between activities 

# :book: Further practice and reading
Congratulations!You have completed this lab session. </br>
You are officially an android master <img src="https://cnet4.cbsistatic.com/img/QJcTT2ab-sYWwOGrxJc0MXSt3UI=/2011/10/27/a66dfbb7-fdc7-11e2-8c7c-d4ae52e62bcc/android-wallpaper5_2560x1600_1.jpg" width="48"> </br>

## Useful resources
* [Android Developer Docs](https://developer.android.com/guide)
* [Android API Reference](https://developer.android.com/reference/packages.html)





