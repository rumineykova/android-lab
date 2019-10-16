
# Let's learn about Android! 
These are must-reads:
* Refresh your Java skills here [here](https://www.cs.utexas.edu/users/witchel/371M/lectures/01-java-review.pdf)
* Java very minimal code convention that you should follow, read [here](https://web.stanford.edu/class/cs193a/styleguide.shtml)
* Very useful Android development course from Stanford [here] [visualisation tools](https://try.github.io/)
* Android fundamentals [here] (https://developer.android.com/guide/components/fundamentals)

## :warning:This week's deliverables 
Completing assignments *Part I* and *Part II* is compulsory. </br>
If you complete assignments *Part III* you gain the status of an Android ninja! </br>
Next week we will continue with Android development. Your compulsory submission deadline will be next week. </br>
However the skills you will gain this week will be essential if you want to succeed with next week's Android task. </br>

## Part I: Basic Android skills: Create your first Android app
Create an Android project with the name Dice Roller. Select Git as a version control system. 
Each level below should be a separate commit! </br>
Quick summary:  </br>
Level 1: Create an app for rolling a dice. The app shoudld contain a button that when clicked generates and displays a random number. </br>
Level 2:  Then add an input box where the user can enter a number from 1 to 6. Repeat the process above, if the generated dice number is the same as the number in the box, then display Congratulations. </br>
Level 3: Add a a text box that displays the user points, e.g the number of times that the user has guessed the number on the dice. </br>
Finally, push your repository to github </br>

Resources that can help you: </br>
Creating a new Android project is explained [here](https://developer.android.com/training/basics/firstapp/creating-project)

## Part II: Create a game of bulls and cows
* __Step 1:__ Accept the assignment invitation from this [link](https://classroom.github.com/a/38k1-dLf) </br>
   Accepting the invitation will create a copy of the repository for you. </br>
   The name of the assignement repository will be something like: git-lab-yourusername  </br>
   In the above yourUserName will be your actual github name </br>
   The link to your repository will be: https://github.com/BrunelCS/git-lab-yourUserName </br>
   Again, note that yours will have the same naming convention but instead of yourUserName, there will be your github username </br>
* __Step 2:__ Create the game. The rules of the game are [here] (https://en.wikipedia.org/wiki/Bulls_and_Cows)
In this exercise, you will modify an existing repository and will submit a pull request to correct a nasty bug in the repository. </br>

## Part III: :hash: Wokring with external APIs: Share your score on slack!
Now when we know the basics of Android, let's have some fun with it. </br>
Add a finish button on the main Activity screen, clicking the button sends you to a new screen </br>
On the new screen there must be one button called "Share your score on slack" </br>
When you click the button your current score should be posted on the slack channel #test-android</br>
Hints: </br>
Update gradle with slack-api repository </br>
Update the manifest file to allow user permissions on have network access and wifi (you need to enable three user-permissions) 

</br>
The full API can be founds here, use it for referene to find which method you should use (hint:postMessage)! </br>
To use the API, you should generate a slack token, read how [here] </br>

Still struggling? Wrap the slack-api call in a try-catch block, and observe the error </br>
You cannot start a long running tasks from the main UI thread, this is not only bad practice, but also a dangerous one. 
Check how to solve it [here](http://simpledeveloper.com/network-on-main-thread-error-solution/). You are allowed to implement the hacky solution this time. But only this time! From next week, you should try using the proper one! </br>

## Part III:n:hash: Become an Android ninja!
There are prizes (android stickers) for whoever manages to complete it! Good luck!</br>
You will also be listed on the lab page as and Android master of the week! </br>


## Part IV: Finally, it is time to test your Android knowledge
* Test your git knowledge [here](https://basicversity.com/study/android-programming)
* Make sure that you can: 
  * create a new android project
  * work with widgets and events 
  * switch between activities 

# :book: Further practice and reading
Congratulations!You have completed this lab session. </br>
You are oficially an android master <img src="https://www.google.com/url?sa=i&source=images&cd=&ved=2ahUKEwjo2aK9wp_lAhVIyxoKHRyrCkoQjRx6BAgBEAQ&url=https%3A%2F%2Fwww.cnet.com%2Fandroid-update%2F&psig=AOvVaw1m-RcIgNo30mKw9JxejmMC&ust=1571271999401439" width="48"> </br>

## Useful resources





