
# LEDs:
## Original-guide.js
### Operation
This is code copied from Spark Fun. It turns three LEDs on and off by varying the intensity.

[original-guide.js](https://github.com/Introduction-to-Computer-Engineering/final-project-assignment-7-week-12-vincefeil/blob/master/original-guide.js)

[Video of operation](https://drive.google.com/open?id=18U0jX9cr7zGimJkgGed54jC9b5KrN0VZ)

## enable-matrix.js
### Operation
This code turns three external LEDs and the center LED on the display on and off. This demonstrates the matrix is not disabled.

[enable-matrix.js](https://github.com/Introduction-to-Computer-Engineering/final-project-assignment-7-week-12-vincefeil/blob/master/enable-matrix.js)

[Video of operation](https://drive.google.com/open?id=1HmVqkgxUaCp90OcurM-u02o10D0E45Xb)

## twenty-eight.js
### Operation
This code conbines the external LEDs and the screen saver Arrows. It turns the three external LEDs on and of as it does in enable-matrix but, when button A is pressed the Arrows screen saver runs for five seconds.

[twenty-eight.js](https://github.com/Introduction-to-Computer-Engineering/final-project-assignment-7-week-12-vincefeil/blob/master/twenty-eight.js)

[Video of operation](https://drive.google.com/open?id=1HtXMLXTSLrJjspd22ozVGFGiz_jb_CsI)

## digital-in.js
### Operation

This code uses an external button to turn external and onboard LEDs on and off. When the button is pressed the LEDs come on and stay on until the button is pressed again. Each time the button is pressed the LEDs turn on or off depending on the state they are in at the time.

[digital-in.js](https://github.com/Introduction-to-Computer-Engineering/final-project-assignment-7-week-12-vincefeil/blob/master/digital-in.js)

[Video of operation](https://drive.google.com/open?id=1HzORvYLlownpRTzrTwa8CK9bYY0j_fVv)

## manual-calibration.js
### Operation

This code uses a Spark Fun soil moisture sensor to read the dampness of a material and shows a bar graph similar to the signal bar graph on a cel phone. The reading from the sensor is remaped to give a range of zero to four and uses this range for the display output. It was calibrated manualy by observing the reading of dry and saturated through the serial port. I used my finger in the video to demonstrate the change in moisture that changes the display.

[manual-calibration.js](https://github.com/Introduction-to-Computer-Engineering/final-project-assignment-7-week-12-vincefeil/blob/master/manual-calibration.js)

[Video of operation](https://drive.google.com/open?id=1IkQuKYiiHK24hkXO45fYccVy-DYIqXZq)

## auto-calibration.js
### Operation

This program starts by asking the user to to take three low moisture readings(sensor dry) and three high moisture readings(sensor in water). At start the disply shows an arrow pointing down to signal the low readings. The sensor is left dry and the user pushes and holds the A button until the display changes to the number one. This tells the user he has taken the first low reading. This is repeated two more times until the display shows the number three. At this point the display will change to an up arrow. Now the sensor is placed in water and the same button display sequence is repeated. After the three high readings are completed the display will say "Calibration Done."

Now the program does the same operations on the input as manual-calibration.js. A wet paper towel can be used to show the working display which is modeled after a cel phone signal display.

At any time the calibration routine can be redone by pressing the A and B buttons together. This restarts the callibration with a down arrow.

[auto-calibration.js](https://github.com/Introduction-to-Computer-Engineering/final-project-assignment-7-week-12-vincefeil/blob/master/auto-calibration.js)

[Video of calibration](https://drive.google.com/open?id=1InqEcKrNeEk1uhNpWLiP-LfOTI1iTMP8)

[Video of operation](https://drive.google.com/open?id=1Iok55aKkqWNKpDEShttekptZ6vFDMn7F)
