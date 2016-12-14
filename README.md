# Chris's Puzzler Project
For the VR Developer Nanodegree at Udacity, I designed, tested, and iterated on a mobile VR app called Puzzler. In this app the user enters a dungeon and plays a game of <em>Simon Says</em> in order to solve the puzzle and exit the dungeon.

### Unique Considerations
There were many design considerations taken into account for this project, including scale, thematic lighting and sound, and user comfort during sequences involving motion.

## Puzzler
This project was successful thanks to an iterative approach that was used to make improvements to the game. My test users and I have enjoyed playing it and I hope many others will too.

<a href="https://youtu.be/RhPmb2DC6qI" alt="Puzzler Walkthrough Video" target="_blank"><img src="https://github.com/caasted/puzzler/blob/master/images/Screenshot_20161213-140337.png" alt="Puzzler Walkthrough Video" width="560">
<br>Click to watch Puzzler Walkthrough Video</a>

## Design process
**Statement of Purpose:** Puzzler is a mobile VR application for new VR users that challenges them to solve a familiar type of puzzle in a new way.

### Persona
For this project I created a user persona called Tim:
<table><tr><td width=150>
<img src="https://github.com/caasted/puzzler/blob/master/images/persona.png" alt="Perona Sketch" width="150" height="150">
</td><td>
Tim, 28 – Sales Representative
<br>“I like playing quick games between tasks at work.”
<br>Tim knows his way around a smart phone and is familiar with mobile gaming, but is relatively new to virtual reality apps. He prefers his entertainment to be fast, fun, and rewarding.
<br><strong>VR Experience:</strong> Beginner
</td></tr></table>
### Sketches
Here are some of the conceptual sketches that I created to lay the groundwork for designing this project:

<img src="https://github.com/caasted/puzzler/blob/master/images/sketch1.jpg" alt="Overall Design Sketch" width="300">

<img src="https://github.com/caasted/puzzler/blob/master/images/sketch2.jpg" alt="Panel Design Sketch" width="300">

## User testing outcomes and iteration
Testing the scene and atmosphere
I conducted a user test with one user who had minimal prior experience with VR to determine if the scale for the environment was accurate, if the mood was appropriate, and if the view areas were comfortable. They did feel like they were smaller than I had intended, but the experience was otherwise positive. The scale of the environment was changed as a result of this feedback.

I conducted a second user test with the same user to assess the design of the start and restart panels. They felt that the panels were positioned too close to the user, but had no issues understanding their function or clicking on the buttons. As a result, the viewing distance of the panels was increased by one meter.

In the third round of user tests we evaluated whether the application was likely to cause simulator sickness or other types of discomfort. The user did find that the movement speed was slow, which resulted in some discomfort. The movement speed was increased following this round of feedback.

In the final round of user testing, the subjects were asked to run the application from start to finish and provide feedback on the entire experience. Multiple users reported that the buzzer sound for failing the puzzle was too loud relative to the rest of the experience. One user questioned the lack of a "win" sound. Two users did not like that the restart function moves you backwards through the dungeon and were concerned this could be disorienting. The first two concerns have been addressed, but the return path has not been changed.

## Breakdown of the final application
The final implementation of the game can be seen in the following set of screenshots. The user enters the experience facing the start panel in the first figure. After clicking on start they move into the dungeon and see the orbs visible in the second figure. The orbs then illuminate and make a sound in a random pattern with a length of five. If the user clicks on the orbs in the correct pattern, they exit the dungeon and are presented with the panel in the third figure. The user may restart the experience from this panel if they wish to keep playing.
<img src="https://github.com/caasted/puzzler/blob/master/images/Screenshot_20161213-140321.png" alt="Puzzler App Screenshot" width="560">
<img src="https://github.com/caasted/puzzler/blob/master/images/Screenshot_20161213-140359.png" alt="Puzzler App Screenshot" width="560">
<img src="https://github.com/caasted/puzzler/blob/master/images/Screenshot_20161213-140414.png" alt="Puzzler App Screenshot" width="560">

## Conclusion
Overall the application runs well and provides the user with a short duration virtual reality experience that shouldn't be difficult to master. The application does a good job of demonstrating how lighting and sound can be used in a 3D environment as well as for visual queues to get the user's attention or indicate the function of the reticle on an object.

## Next steps
Additional user feedback may lead to further iterations on the design of the puzzler app, but for the time being the only task left is considering alternative methods of transporting the user back to the starting point.

## Link to additional work
For more VR experiences, please visit my [GitHub](https://github.com/caasted) and [Udacity](https://profiles.udacity.com/u/chrisaasted) profile pages.
