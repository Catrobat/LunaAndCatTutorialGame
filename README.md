![GitHub img copy](https://user-images.githubusercontent.com/48293545/63705269-713a9f80-c835-11e9-8a4f-ee33b9bb21ea.png)
<h1 align="center"> The Magic Word </h1>

## A LunaAndCatTutorialGame ##

The Luna&Cat Tutorial Game is being developed using the [Luna&Cat](https://catrob.at/luna) app in the [Catrobat](https://www.catrobat.org/) language. 

This project was started in 2019 as a [Google summer of Code](https://summerofcode.withgoogle.com/) project.

This repository host the .catrobat files for the game and all the used sprites and songs.

The latest release can also be found on the Catrobat community and code repository site via TODO.

# Getting Started # 

### Installation ###

Download Luna&Cat from the App Store and make a Catrobat account. When you have the account, you search
for the user TODO on the Catrobat website. The Magic Word is listed on the user’s page.

<h4 align="center">or</h4>

Download  the latest version from [GitHub](https://github.com/Catrobat/LunaAndCatTutorialGame/tree/master/code) and copy it onto your Android  phone.
In catrobat you can select "import file" from a drop down menu in the right corner of the 
app.

### Add / Modify Features ###

If you want to send us improvements, e.g., translations, bug reports, or new features send us an email [lunaandcat@catrobat.org](mailto:lunaandcat@catrobat.org). 

* You can simply remix the project by uploading your improved version via [Luna&Cat](https://catrob.at/luna) to the Catrobat community and repository site.

### Translations

If you are interested in contributing as a translator, download the latest version of the app and:
* Translate all text included in the "language controller" scene.
* Translate the names of the scenes and objects of the game.

_The game needs to complete its text mechanism, a translation in its current form is not recommended_

# Work

## Done 

 _Every [commit](https://github.com/Catrobat/LunaAndCatTutorialGame/commits/master) is the individual's work, except stating otherwise in the title of the commit._

The [Storyline](https://github.com/Catrobat/LunaAndCatTutorialGame/tree/master/story/Storylines) was based on [Naomi Pfaff](https://github.com/npfaff)'s [research](https://github.com/Catrobat/LunaAndCatTutorialGame/tree/master/story/Research) on the desired audience, while [Stefania Mak](https://github.com/stefaniamak) was in charge of bringing that story to life graphically by [storyboards](https://github.com/Catrobat/LunaAndCatTutorialGame/tree/master/story/Storyboards) and [graphics](https://github.com/Catrobat/LunaAndCatTutorialGame/tree/master/graphics).

A sequence of images can now be flicked through by touching the screen.
The correct dialogue is assigned to the correct image. When a unit ends
the user is taken to an activity. These features were added to
every unit of the game. 

## To-Do 

* Adding the text for Units 0, 1, 2, 4 and 6 in the "language controller" scene. 
Based on this [Google Doc file](https://docs.google.com/document/d/1ItitaWzAqJSvqRZuS6hDe5AaZT5WWwsANt6Z1vvS5Ps/edit?usp=sharing).

* Make the "scene" and "block" images easily translatable.
    * Replace the img files within the project with erased text img files: [Scenes](https://github.com/Catrobat/LunaAndCatTutorialGame/tree/master/graphics/scenes/empty) / [ScenesV2](https://github.com/Catrobat/LunaAndCatTutorialGame/tree/master/graphics/scenes/empty%20%2B%20scrablle) / [Blocks](https://github.com/Catrobat/LunaAndCatTutorialGame/tree/master/graphics/bricks/Empty_) (needs to add a speech bubble on some).
    * Create the same mechanic with the storyline's text over the "language controller" scene.

* After the game is completed, the dialogue will be available in German, English and Greek. 
The option of choosing between these languages will be worked
into the game.

# Development

### Merging

Both [Naomi Pfaff](https://github.com/npfaff) and [Stefania Mak](https://github.com/stefaniamak) contributed on versions of the game. 
The latest version producing the features listed above was merged with code writte by [Stefania Mak](https://github.com/stefaniamak). 
[Stefania Mak](https://github.com/stefaniamak)'s code is responsible for the feature that ensures that users are only able to access a unit if they have successfully completed the previous unit. 
A revised version of the dialogue feature was added. It is the basis for the option of choosing different languages within the game. [Stefania Mak](https://github.com/stefaniamak) also coded the activities.

### Challenges and Learnings

Code had to be adapted to reduce the size of the game. Simultaneously 
considering the game size and its functionality increased the difficulty 
of the task. However it encouraged us to find the simplest possible way
to create a feature and therefore improved the quality of our work.

### Running the tests 

In Catrobat code can be tested by going into game mode. 
This is achieved by pressing play.

# Story

## Learning Mechanism 

The learning mechanism of this game is based on Cogntive Load Theory. The examples of code shown to the user by Cat are worked examples. Worked examples are completed examples of a problem. For example, a line by line solution of an algebra problem is a worked example.
The study of worked examples is a way of teaching problem solving. It is thought that the passive role of the learner in worked examples frees cognitive resources that would be recruited during active problem solving (van Gog, Paas, & van Merriënboer, 2006). The additional cognitive resources made available by the passive role of the learner in worked examples enable learners to gain more knowledge from worked examples than they would from working the examples themselves (Carroll, 1994; Sweller & Cooper, 1985; van Gog, Kester, & Paas, 2011; van Gog et al., 2006).  Problem solving imposes an especially high strain on novice learners. Novice learners profit from the cognitive resources freed by worked examples more than learners with more expertise (Sweller & Cooper, 1985). As Novice learners are the target audience of The Magic Word, worked examples were used to teach coding concepts in this game.

This is to say that there is considerable evidence suggesting that, at a beginner level, coding should be taught by showing students examples of code and then explaining their function. In the Magic Word students do not only receive explanations of the function of the code; they are see the code it in action. Each activity serves to solidify the knowledge attained in the preceding scene. The following text is a scene by scene description of the learning content of each scene and the plot that is used to carry it.

## Unit 0 : Narrative User Interface

The user is given an overview of the locations of projects on the device. The relationship between objects and their scripts is introduced. The categories of bricks are explained. The user is introduced to pocket paint and learns how to add looks to an object.

Cat steals a book containing magic spells and brings it to Lunas room. The user helps cat take the book. Luna finds the book and her pet dog Noodles falls into it. Cat reveals that the book is a portal to a magic word that Noodles is now trapped in. Luna goes on a quest to save him with the reluctant help of Cat. Cat wants Luna to  focus on learning magic from her as Luna comes from a family of magicians who have travelled between the magic world inside the book and Luna’s world for generations. The magic Luna learns is coding and the magic book of spells contains examples of code for the user.

## Unit 1 : the Motion Brick 

In this unit Users experiment with different types of motion bricks. At first, they insert the “move ten steps brick” in conjunction with a forever loop and observe its effect on the movement of the character. Next the “If on edge bounce” and “Set rotation style” bricks are added to this script in order to improve the pacing motion of the character. Finally, the user animates Luna by adding the “Next Look” brick in combination with a forever loop.

Luna has to use magic to move in the other world. The user helps Luna move through the use of motion bricks.

## Unit 2 : Broadcasts

Unit 2 A
Users learn that broadcasts determine the moment of an action and the objects that execute it. They add a broadcast brick and insert a motion that is to be executed when the object receives the broadcast.
Luna and Cat are trapped by rocks. The user has to make the rocks all levitate simultaneously so that Luna and Cat can pass under them.

Unit 2 B 
Users learn that Broadcasts can be used in conjunction with the “When (x) becomes true” brick in order to link the moment broadcasts are sent to an event within the game. 

Luna and Cat are thirsty. Cat knows a spell that will reveal water to them.

## Unit 4 : Sensors 

Unit 4 A 
Users are introduced to the concepts of sensors. The use an “inclination x” sensor to control the movement of an object.

Luna is sick of living off berries. Cat has seen an egg in a tree nearby but the egg might break on one of the branches below if it comes straight down. Inclination is used to give Luna more control over the eggs movement so that it does not break.

Unit 4 B 
Users combine a facial detection sensor with the “When (x) becomes true” brick that was previously used in unit 2B. 

There is an old mirror standing in a tower. It can tell Luna and Cat where Noodles is but it is sleeping. It only wakes up when it sees a magician. When the phone detects the face of the user the mirror sees Luna. It tells Luna and Cat that Noodles is in the Dartmoor. Cat implies that she has had a run in with some werewolves there and that they hold a grudge against her.

## Unit 6 : Variables 

Unit 6A
Users are introduced to the concept of variables. They then add a brick to their script that increases the value of a variable by 1 every time a game event takes place.

Luna and Cat enter the Dartmoore. The tracking spell they use to find Noodles always traces him to the last place he stopped for a rest. For it to work every stop must be counted otherwise the final stop – the stop where Noodles is right now – cannot be found. The users script counts the stops. Luna and Cat find werewolf tracks. We see red eyes watching them from the distance.

Unit 6B
Luna and Cat find Noodles in an abandoned campsite. As a pack of werewolves approaches from the darkness it becomes clear that the campsite was not abandoned. Their leader turns into a human and reveals that Noodles has lived with them as their friend and that they mean Luna and Cat no harm. He says goodbye to Noodles and the three of them teleport to Lunas bedroom.

## Bibliography 
Carroll, W. M. (1994). Using worked examples as an instructional support in the algebra classroom. Journal of educational psychology, 86(3), 360.

Sweller, J., & Cooper, G. A. (1985). The use of worked examples as a substitute for problem solving in learning algebra. Cognition and instruction, 2(1), 59-89

Van Gog, T., Paas, F., & Van Merriënboer, J. J. (2006). Effects of process-oriented worked examples on troubleshooting transfer performance. Learning and Instruction, 16(2), 154-164.

Van Gog, T., Kester, L., & Paas, F. (2011). Effects of worked examples, example-problem, and problem-example pairs on novices’ learning. Contemporary Educational Psychology, 36(3), 212-218.

# Licences #

* AGPL and CC-SA-BY in their latest versions. For details, see http://catrob.at/licensesofuploads
