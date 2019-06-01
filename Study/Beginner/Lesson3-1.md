# Lesson 3 - 1
If you have completed the last lesson ([Lesson 2](https://github.com/mike0295/Unity-Game-Development/blob/master/Study/Beginner/Lesson2.md)), you now have a basis to create a simple 2D platformer.
Now, you can implement unlimited number of movements and interactions! (with help from your best friend Google...)

However, a real game will need a main menu, pause and a proper game concept!

## Task
Create a simple **stage/level** for a "Bouncy Ball" style game

<img src="https://github.com/mike0295/Unity-Game-Development/blob/master/Study/photos/1_bouncy_ball.jpg">


### Constraints:
* The ball is always bouncing as default (no button needed to be pressed for jump)
* Use either AD or arrow buttons to move sideways
* Have a 'spawn' location
* Have a 'goal' destination
  + The desination can be a specific platform, a specific area, etc
  + Once you reach the goal destination, print "Game Complete" in console
* If the ball drops out of frame/camera it must **DIE**
  + When the ball dies, print "Dead" in console
  + The ball must automatically spawn back in spawn location

## Useful Links
* [Transform.position](https://docs.unity3d.com/ScriptReference/Transform-position.html) ([Korean](https://docs.unity3d.com/kr/530/ScriptReference/Transform-position.html)): Changing position of object
* [OnTriggerEnter2D()](https://docs.unity3d.com/kr/530/ScriptReference/MonoBehaviour.OnTriggerEnter2D.html): If you use a specific area (over a platform) as destination
* [OnCollisionEnter2D()](https://docs.unity3d.com/ScriptReference/MonoBehaviour.OnCollisionEnter2D.html) ([Korean](https://docs.unity3d.com/kr/530/ScriptReference/MonoBehaviour.OnCollisionEnter2D.html)): If you use a specific platform as destination
