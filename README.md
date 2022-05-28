# Glove-for-paralysis-patients
## Introduction
Paralysis is a loss of strength in and control over a muscle or 
group of muscles in a part of the body. Most of the time, this is
not due to a problem with the muscles themselves. It is more
likely due to a problem somewhere along the chain of nerve
cells that runs from the body part to your brain and back again.
These nerve cells deliver the signals for your muscles to move.
Gesture recognition is the process by which gestures made by
the user are used to convey the information.

A set of physical gestures may compose
an entire language, as in sign languages. They can efficiently
convey a rich set of facts and feelings. This project makes the
modest suggestion that gesture-based input is such a beneficial
technique to convey information. This project is the solution to the
problem because the message is conveyed with the least effort

## Working
FLEX SENSOR is a variable resistor whose terminal resistance
increases when the sensor is bent. So this sensor
resistance increases depending on surface linearity. So it is
usually used to sense the changes in linearity
When it is bent 45º angle the FLEX SENSOR resistance
increases to twice as before. And when the bent is 90º
the resistance could go as high as four times the nominal
resistance. In this project the usual voltage divider is simulated
using a case structure , taking into consideration only 3 angles
(0,45,90).

## Requirements
### Labview
LabVIEW is a framework plan stage and development
environment for a visual programming language. Instead of
using a Voltage divider in the hardware, the software substitute
is summation. According to the Sensor Datasheet 45KOhms
and 90º is encoded to be 125KOhms. We initially simulate the five flex sensors for
all the fingers in LabVIEW. In this software, we have given
the input controls as angle values. 

We have done this project
currently for five gest little and thumb fingers are at 90 and
45. The second gesture is for “Medicines” when the ring and
thumb fingers are at 90 and 45. The third gesture is for the
“Restroom” when the middle and thumb fingers are at 90 and
45. The fourth gesture is for “To go out” when the index
and thumb fingers are at 90 and 45. The fifth gesture is for
“Emergency” when the thumb is at 90 while all other fingers
are at 0. The data is sent at the rate of 1 data point per second.
We have coded the LabVIEW block diagram and sent the data
to Thingspeak using the HTTP protocol.

### Thingspeak
IoT application platform that offers a wide variety of analysis,
monitoring and counter action capabilities is ‘ThingSpeak’.
ThingSpeak is a platform providing various services
exclusively targeted for building IoT applications. It offers the
capabilities of real time data. This can be used for the
further usage to train a Machine Learning Model.

### MIT App Invertor
MIT App Inventor is an intuitive, visual programming environment
that allows everyone to build fully functional apps for
smartphones and tablets The data is sent from the ThingSpeak
Channel to the MIT App Inventor. The IOT Dashboard is
displayed to the App using a WebView. The TextToSpeech
Module is used to give an Audio Output. This is implemented
into the project because it requires an immediate reaction. Text
messages may go unnoticed , but a Voice Message with high
pitch and repetition is hard to miss. Texting MIT App Inventor
is used to send Text messages to a given number.
