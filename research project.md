For my research I looked up how to have a score box on screen update. First I had to make a UI canvas and score box. 
![score](https://cloud.githubusercontent.com/assets/16655980/14691172/c7b3594c-071d-11e6-8fa0-44c8bdceaf54.png)


This is the tutorial I used https://unity3d.com/learn/tutorials/projects/survival-shooter/scoring-points that showed me how to create UI texts and also explained how to impliment a scoreing script to update the score box.

![screen shot 2016-04-20 at 5 29 08 pm](https://cloud.githubusercontent.com/assets/16655980/14717223/6fd56232-07be-11e6-9d34-e0841753164f.jpg)

However I realized that that wasn't working because for their code they connected the score to when an enemy in their game dies. 

I realized I had to make a script so that  when the spheres leave from the mouse click (which is what Ned coded) and they collide with an image plane the plane gets "destroyed" or in terms of our game dampened by pee.

<img width="749" alt="screen shot 2016-04-20 at 5 17 50 pm" src="https://cloud.githubusercontent.com/assets/16655980/14690992/dcf89908-071c-11e6-940a-df51bee24d1b.png">

Then I realized I needed to add a istrigger function to the "bullets" or pee that Ned programmed to come out of the mouse click, so that when they collide with image plane and destory it (because of the code I put on the image planes) it triggers the score to go up. 

However I'm still not exactly sure how to do that and Wade and Sasha are going to help me finish this today. 

This I found and read helped me a bit just because it gave a different way of doing the scoring. 
This one shows you how to make pick-ups and then and utilize the GUI system (which was in the older versions of maya) 
to keep score of how many points you get from pick ups. It keeps track of the score and stores info the textfield via a 
UpdateScoreText() function.
(http://code.tutsplus.com/tutorials/getting-started-with-unity-gui-scoring-timers-particles--active-10057)


And this particular tutorial shows how to add a script on the player. Based on a character that envelopes objects. 
Not exactly useful for our game. 
(https://unity3d.com/learn/tutorials/projects/roll-a-ball/displaying-text)


