# ubiquitous-guide

A web app that detects your current emotion using your webcam.

If you have a negative expression on your face for at least 2 seconds, it shows a desktop notification with an emoji similar to your expression.

The goal is to allow you to quickly realize whenever you're in bad mood. You could let it run all day and hopefully become more aware of your emotional states throughout the day.

It uses [Affectiva](https://www.affectiva.com/) JS SDK CameraDetector to track different emotions.

## Demo page

https://andivis.github.io/ubiquitous-guide/

##Instructions

1. Press the start button to start the detector.
2. Allow camera and notification access when asked.
3. Make sure the lighting is good. Look at the camera. Wait until the dots appear on your face. The probabilities of the different emotions are written to the "EMOTION TRACKING RESULTS" section.
4. Make a sad or angry face for at least 2 seconds. You'll get a desktop notification.
5. Press the stop button to end the detector.