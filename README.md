AnimationGrabber
================

AnimationGrabber is a bare-to-bones program for previewing and iterating animations of any kind. It allows you to turn any drawing program into an animation suite. So if you're like me and hate drawing on Photoshop and really dislike the the vector style of Flash, this is for you.

I'm uploading the original Python source along with a Windows executable that may or may not work on your system. I'm not an experienced Python programmer so use at your own risk and discretion! (Or make a pull request to make this a little bit less hacky)

The core idea of AnimationGrabber is that if you can take a screenshot of it, you can animate it! Replacing a frame within the looping animation is only a matter of pressing the Print Screen key. Want to replace the frame three? Just press the number 3 on your keyboard and the animation is instantly updated. The whole program is run by keyboard presses, which makes it super fast to use, but quite daunting to start using!

When you first boot AnimationGrabber, you'll see a pure black window with weird numbers on top. There are a few steps you need to take before using it.

## Setting the grab area

Grab area is the area on your screen that is placed into the animation. A good grab area would be some window which gives you a good view on your entire drawing, for instance the Navigator panel in some software.

- Move your mouse cursor to the top left corner of the capture area and press Alt+Home
- Move your mouse cursor to the bottom right corner of the capture area and press Alt+End

The AnimationGrabber window will change size along with the grab area.

## Grabbing frames

The horizontally labeled numbers 1 through 9 act as slots for keyframes. The Numpad numbers 1 through 9 are frames 10 to 18

- Pressing a number key will grab the viewport and store the file to that frame.
- Subsequently pressing PrintScr will overwrite the last frame you've set, so you don't need to remember where you were at.

## Setting the timerange

AnimationGrabber is limited to only 18 frames. This is not a fully fledged animation suite but a tool for previewing short segmets of animation.

- After pressing a number key and setting that frame active, press the End key to set that keyframe as the last.
- Pressing the Home key will set the keyframe as first.

Or just press 5 and End, and you'll get a looping animation of the first five frames.

## Adjusting framerate

- Framerate is adjusted with PageUp and PageDown keys.
