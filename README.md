# ubiquitous-guide

A web app that detects your current emotion using your webcam.

If you have a negative expression on your face for at least 2 seconds, it shows a desktop notification with an emoji similar to your expression.

The goal is to allow you to quickly realize whenever you're in bad mood. You could let it run all day and hopefully become more aware of your emotional states throughout the day.

It uses [Affectiva](https://www.affectiva.com/) JS SDK CameraDetector to track different emotions.

## Demo page

https://andivis.github.io/ubiquitous-guide/

## Instructions

1. Allow camera and notification access when asked.
2. Make sure the lighting is good. Look at the camera. Wait until the dots appear on your face. The probabilities of the different emotions are written to the "Emotion Tracking Results" section.
3. Make a sad or angry face for at least 2 seconds. You'll get a desktop notification. You must wait at least 10 seconds before getting another notification.
4. Press the stop button to end the detector.