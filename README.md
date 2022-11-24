# Sky

This is a music runner game, made as a part of my experience with Motion Capture/[Xsens](https://www.xsens.com/motion-capture), Unity 3D and [SuperCollider](https://supercollider.github.io). 
The player controls the game by moving the marker [(hier kann man es sehen: YouTube)](https://youtu.be/OYplfKiy_DQ). Motion data is captured by Motion capture in Unity. The player plays in real-time.

Here is how it’s done: data (marker positions) is sent to the SuperCollider from Unity. This data generates the pitch of a sounding note (Frequenz). 
And in SuperCollider the sound is synthesized by using a programming language.

Thus, the game is not only a runner, but a real-time musical instrument that can also sound like a Theremin.


![logo](https://github.com/MilaGrishkova/Sky/raw/main/Sky.jpg)
