# Lesson 2

In this lesson, we will create a basis for a 2D platformer game.

The first task is very similar to lesson 1, but only in 2D.

## Task:
* Create a square shaped player
* Create a ground for the player to walk(?) on
* Make the camera follow the player
* Allow player to move left/right using either arrow keys or WASD
* Allow player to jump using space bar
* If you want, try creating platforms for the player to jump onto

### Some info
+ You can use a sprite for the ground, just like what you did in lesson 1
+ Jumping will feel very awkward for now. We will change that in the next lesson

## Useful links
### Player movement + jump
* [Simple Jump in Unity 2D (Unity Tutorial for Beginners)](https://www.youtube.com/watch?v=ptvK4Fp5vRY)
  + Creating player and platform sprite: 1:14
  + Player jump: 3:30
    - Uses **BoxCast()** and **layers**: 5:35
  + Solution for possible platform bug where character gets stuck in wall: 16:06
  
* [2D DOUBLE / TRIPLE JUMP PLATFORMER CONTROLLER - EASY UNITY TUTORIAL](https://www.youtube.com/watch?v=QGDeafTx5ug)
  + Left/right movement: 0:39
  + Character **flip**: 3:48
  + Character **jump** using **OverlapCircle()** and **layers** : 5:56
  + Double/Triple jump (optional) : 8:20
  
### Fundamental knowledge of execution (recommend reading when you see them in the tutorials above)
* [Start() and Awake()](https://unity3d.com/kr/learn/tutorials/topics/scripting/awake-and-start)
* [Update() and FixedUpdate()](https://unity3d.com/kr/learn/tutorials/topics/scripting/update-and-fixedupdate)
* [Execution Order/이벤트 함수 실행 순서](https://docs.unity3d.com/kr/530/Manual/ExecutionOrder.html)
  

## Upon Completion
If you have completed the task above, **CONGRATULATIONS!**

Assuming you have read and followed the tutorials above, you now know (at least have an idea of) concepts of:
* RigidBody2D, BoxCollider2D
* Input.GetAxis()
* Vector2()
* LineCast(), BoxCast()
* Layers
* etc (TODO)

And maybe know:
* Difference between Start() and Awake()
* Difference between Update() and FixedUpdate()



