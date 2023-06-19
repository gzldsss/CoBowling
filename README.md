# CoBowling

This is a VR bowling game made by UE5. Players can throw the ball in their hands to hit the opposite glass bottle to get points. This is the first VR game I have made and I am really enjoying it.

video：https://youtu.be/5bjxXGnKFV0

![屏幕截图 2023-06-08 233440](https://github.com/gzldsss/CocacolaBall/assets/118484191/23246b46-6325-42d6-a929-5f19521e1cca)
# Scenes

This is an old street, a few glass bottles and a ball can keep children playing for a long time, it is the childhood that parents always say.

![屏幕截图 2023-06-05 183424](https://github.com/gzldsss/CoBowling/assets/118484191/f17a4796-2780-4f89-afa4-19d28900cd20)
![屏幕截图 2023-06-01 144618](https://github.com/gzldsss/CoBowling/assets/118484191/96420de3-6504-4bd8-82b1-0efac1f01820)
### post-rendering material blueprint
Manga style with purple tones. This blueprint uses the Stylized Texture Pack plugin, which I modified. And I used the good sky plugin for the sky.

![屏幕截图 2023-06-11 222946](https://github.com/gzldsss/CoBowling/assets/118484191/363e0814-c6d1-47cc-927c-d1480433c343)

# Models and Collisions

Added a model for the glass bottle and added box collision to the top half of the glass bottle. In this way, it can gain points when colliding.

![屏幕截图 2023-06-12 153500](https://github.com/gzldsss/CoBowling/assets/118484191/3a50ab1f-bfdd-4a10-aff0-3aede28c6e2c)
![屏幕截图 2023-06-12 153152](https://github.com/gzldsss/CoBowling/assets/118484191/f652f8b8-b65e-44e3-8477-47cd55e60953)

This is a black ball, because the ground is white, so the ball uses a simple black reflective material. This ball is used for players to pick up and throw it to hit the opposite bottle. etting the friction to -30 will allow the ball to roll smoothly to the opposite side，And add simulated physics to keep the ball from being bounced by the bottle.

![屏幕截图 2023-06-12 155118](https://github.com/gzldsss/CoBowling/assets/118484191/0192915a-e9f5-455d-bb4f-3b2f2fc4cdc3)

![屏幕截图 2023-06-12 155417](https://github.com/gzldsss/CoBowling/assets/118484191/a952dae9-9b49-457f-8468-9b2e4a09d0de)

# Score
Scores are obtained by colliding Coke bottles, and the score is the number of bottles hit. vent overlap means that when the glass bottle is hit, it will get points.


![屏幕截图 2023-06-11 222549](https://github.com/gzldsss/CoBowling/assets/118484191/9ae8e37d-33ad-4c11-a831-be7187d799c4)
![屏幕截图 2023-06-12 153340](https://github.com/gzldsss/CoBowling/assets/118484191/891e9f56-bbce-4591-afd0-80a3d5b596ac)
![屏幕截图 2023-06-11 222627](https://github.com/gzldsss/CoBowling/assets/118484191/222a28a0-c257-4812-8d04-0a370e122872)
Convert fractions to text, and as integer numbers.

![屏幕截图 2023-06-11 225021](https://github.com/gzldsss/CoBowling/assets/118484191/167fb91d-6b11-4adc-8bc8-9a9b87737ef2)

As shown in the picture, when the bottle is knocked down, the score obtained will be displayed.
# Sound

Make a sound and only trigger once per collision to make the collision sound more natural. So there's a sound when the ball rolls and when the bottle gets hit.

![屏幕截图 2023-06-11 222659](https://github.com/gzldsss/CoBowling/assets/118484191/061fa50a-8d15-42f6-bb47-c59034f6c2cf)

# Reference

https://www.youtube.com/watch?v=dL08XUunLKQ&list=LL&index=8&t=113s

https://www.youtube.com/watch?v=GrycMDKPRVs&list=LL&index=13

# Related to this work

It's a simple bowling game, although it wasn't easy for me to make. There were a series of problems in the production process, such as the resistance and gravity of the ball, the ball could not be thrown out, the bottle fell into the ground, the impact did not make a sound, and the score was not accurate, etc., but they were all overcome one by one. Arrived a lot, let me know more about the operation of Unreal Engine.
