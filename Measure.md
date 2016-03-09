# Introduction #

Measure is an Avisynth Script which generates greybars, and can measure such a testpattern by displaying luminence values on top of each bar.  The resulting video can be used for testing the video response of analog systems.


# Details #

The resulting video can be used for testing the video response of analog systems.
This can then be used to calibrate capture brightness/contrast.

It requires [avisynth](http://www.avisynth.org) to run.  Once Avisynth is installed, open the included .avs file in Mediaplayer.  A default testpattern should be displayed.  To use on your own videos, modify the .avs as a text file and follow the included instructions to use your own video.
![http://avisynthrestoration.googlecode.com/files/measure-test.png](http://avisynthrestoration.googlecode.com/files/measure-test.png)

Above is a measurement of the perfect testpattern which was recorded.

![http://avisynthrestoration.googlecode.com/files/measure-real.png](http://avisynthrestoration.googlecode.com/files/measure-real.png)

Above is a measurement of the testpattern after being recorded on a VHS VCR.  Notice the noise and brightness/contrast differences; contrast is too high and brightness is too low, cutting off the Y=32 bar.  This can theoretically be calibrated by a calculation; however it would also have to be re-digitized at the recommended capture settings.