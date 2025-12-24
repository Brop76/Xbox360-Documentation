Natural User Interface Settings
================================

The Natural User Interface Settings contains four tabs:

<ul>

  <li>Kinect</li>
  <li>Overlay</li>
  <li>Skeletal Tracking</li>
  <li>Navigation</li>
  <li>Virtual Multitouch</li>
  <li>Speech</li>
  
</ul>


Kinect Tab
==========
The Kinect Tab allows users to select the type of interaction mode to use with the input device (e.g., Kinect). It also allows users to set the tilt angle of the device to be adjusted, as well as the detection range of the sensor, which determines how far or close the device can see.

 

**Kinect Tab of Natural User Interface Settings**

![KT](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/images/NuiSettings_GeneralTab_SekeltalTracking2.png)

 

**NUI Mode** - Allows the user to toggle between **Skeletal Tracking** mode and **Virtual Multi-touch**. The NUI mode can also be set through the Mode Tab on the [Natural UI Section](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/Natural%20UI%20Section%20of%20the%20Ribbon.md) of the GraphWorX64 View Ribbon.

**Sensor Tilt** - Allows the user to adjust the degree of tilt of the sensor. The sensor has a default tilt of 0° and a range of +27° to -27°. A positive angle will create a sensor tilt upwards (with respect to a horizontal axis) while a negative angle will create a sensor tilt downwards (with respect to a horizontal axis).

 

Overlay Tab
===========

**Overlay Tab of the Natural User Interface Settings Window**

![Overlay](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/images/OverlayTab.png)



 

**Show Assistant Window** - Click this checkbox to enable the Natural User Interface assistant window. The **Assistant** is used for guiding users towards the best experience. For instance, when a user stands partially out of the sensor’s field of view, the assistant window will let him know that he should move so that the sensor can see him better. Also, the assistant notifies the user about speech events, such as the voice commanding is listening for a voice command or that the voice command has been recognized or rejected.

 


Skeletal Tracking Tab
=====================
The Skeletal Tracking Tab provides settings for defining the physical space for user. It provides the user with an adjustable, visual display of minimum and maximum interaction space and the corporal and facial interaction space. The physical space is presented as the field of view of the sensor (which is constant and is shown as a blue triangle in the interaction overview picture) and the minimum and maximum distance of the user from the sensor (Near and Far settings, shown as a gray rectangle in the interaction overview picture). The user’s intent for interaction can be set by facial angle, which determines within which angle the user must face the sensor. Similarly, the body angle determines within which angle the user’s body can be turned relative to the sensor.

 

**Body Interaction Subtab within the Skeletal Tracking Tab of the Natural User Interface Settings**


![BI](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/images/SkeletalTrackingTab2.png)
 

**Space**:

Near [m] - The closest distance the users can be in front of the sensor.

Far [m] - The furthermost distance the users can stand in front of the sensor.

**Corporal interaction**:

Enable Body Tracking - Enables detection of the user's intention for interaction using the angle of the user's body.

Angle [°] - Allows the user to adjust the angle boundary within which the user body must stay to remain detected

**Facial Interaction**:

Enable Face Tracking - Allows the user to enable or disable face tracking.

Angle [°] - Allows the user to adjust the angle boundary within which the user's face must stay to remain detected.

 

**Sensor**:

Auto Tilt Adjustment - Enables the sensor to automatically adjust its tilt angle in order to adapt the sensor field of view when user moves.

 

**Legend**:

**Gray area**- Physical interaction space given by the Near and Far distance.

**Green triangle** - The field of view of the sensor. The sensor is only able to see things located inside this triangle.

**Blue triangle** - When the user's body angle is inside this triangle, the interaction intention is detected.

**Red triangle** - When user's face angle is inside this triangle, the interaction intention is detected.

Navigation Tab
==============
The Navigation tab allows users to specify how to control movement within the display, i.e., Zoom, Walk, Orbit, Look Around, Panning.

 

**Navigation Tab in the Natural User Interface Settings**

![NT](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/images/NavigationTab2.png)

 

**Navigation Presets:

  **Custom** – Allows users to define their own navigation settings

**TwoHandedControl** – Navigation using both hands. Primary hand for zoom, orbit, look around. Secondary hand for panning and walk

**OneHandedBodyControl** – Navigation using primary hand for zoom, orbit, look around. Using body motion for walk and panning.

**TwoHandedBodyControl** – Navigation using both hands and body motion. Primary hand for zoom, orbit, look around. Secondary hand for panning and body motion (forward or backward) for walk.

 

**Control Mode**:

**Position Control** – Analogous to mouse control. By moving your hand, you change only an increment of the position, so the navigation changes only when you move your hand.

**Rate Control** – Analogous to joystick control. By moving your hand, you change the speed of the navigation.

**Body Control** – By moving body position – like stepping forward/backward/left/right, you change the navigation.

 

**Hand**:

**Primary Hand** - Specifies the user's primary hand to trigger navigation.

**Secondary Hand** - Specifies the user's secondary hand to trigger navigation.

Skeletal Tracking Navigation Modes include the following:

Orbit3D

Fly3D

Walk3D

**Skeletal Tracking - Navigation Modes**

![ST](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/images/SkeletalTrackingNavigationModes.png)

**Navigation Descriptions**


**Zoom** [in 2D and Orbit3D]

<li>Position Control – By grabbing the display and moving your hand closer or further from the sensor, the zoom level is changed. When your hand is closer to the sensor than it was at the moment of the grip, the zoom level is decreased (zoom out). Otherwise, the level is increased (zoom in).</li>

<li>Rate Control – By grabbing the display and moving your hand closer or further from the sensor, the speed of zooming is changed. When your hand is closer to the sensor than it was at the moment of the grip, the zoom out speed increases. Otherwise, the zoom in speed increases. </li>

<li>Body Control – Not applicable.</li>



**Walk** [in Fly3D and Walk3D]

<li>**Position Control** – Not applicable.</li>

<li>**Rate Control** – By grabbing the display and moving your hand closer or further from the sensor, the speed of walk movement (movement forward or backward) is changed. When your hand is closer to the sensor than it was at the moment of the grip, the speed of movement forward increases. Otherwise, the speed of movement decreases and becomes backward movement.</li>

<li>**Body Control** – By grabbing the display and moving your body closer or further from the sensor, the speed of walk movement is changed. When your body is closer to the sensor than it was at the moment of the grip, the speed of movement forward increases. Otherwise, the speed of movement decreases and becomes backward movement. The walk navigation is analogous to real walking. When you step forward, you actually move forward in the 3D scene.</li>

*Orbit* (rotation around model) [in Orbit3D]

<li>**Position Control** – Not applicable.</li>

<li> **Rate Control** – By grabbing the 3D scene and moving your hand left, right, up, or down, you can change the orbiting speed of the camera around the 3D model.</li>

<li> **Body Control** – Not applicable </li>

**Look Around** (rotation) [in Fly3D and Walk3D]

<li>**Position Control** – By grabbing the 3D scene and moving your hand left, right, up, or down, you can change the angle of the camera’s view.</li>

<li>**Rate Control** - By grabbing the 3D scene and moving your hand left, right, up, or down, you can change the speed of the angle increase of the camera’s view.</li>

**Body Control** – Not applicable.

**Panning** [in 2D and 3D]

<li>**Position Control** – Not applicable.</li>

<li>**Rate Control** - By grabbing the 3D display and moving your hand left, right, up, or down, you can change the speed of the scene movement.</li>

<li>**Body Control** - By grabbing the 3D display and moving your body left, right, up, or down, you can change the speed of the scene movement.</li>

Virtual Multitouch Tab
======================

The Virtual Multitouch tab allows you to set a screen size, align the sensor and run a calibration utility.

 

**Virtual Multitouch Tab of Natural User Interface Settings**

![VMT](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/images/VirtualMultitouchTab2.png)

<li>Screen Size - Allows the user to toggle between screens 80'' and less and screens over 80''.</li>  

<li>Sensor Alignment - Allows the user to select whether the sensor is facing towards the screen or away from the screen.</li>

<li>Run multi-touch calibration - Initializes the calibration process for the Multi-touch mode.</li>


Speech Tab
==========
The Speech Tab allows users to select the speech input, accuracy, microphone settings and echo cancellation.

 

Speech Tab of Natural User Interface Settings

![ST](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/images/NuiSettings_SpeechTab2.png)

 

**Speech Recognizer**

  **Enable Speech Input** - Click this checkbox to allow voice interaction with the device.

  **Language** - Allows the user to set the voice recognizer language (default: English-US)

  **Pre-command** -A word to initiate the speech commanding. This can a word in the current language or a language alias. The former gets automatically     translated to the language selected in GraphWorX64 in Runtime.

  **[...]** - The ellipsis [...] button lets you browse for an existing alias.

  **Test** - The Test button opens the Speech Test window, which provides an Audio Level Indicator, a Recognizer Status Message, an Audio Problem Message and additional info on what the user should do for testing pre-commands. The Recognizer Status Message says whether the command has been recognized (as illustrated in the picture below) or if the recognition has been rejected or cancelled. The Audio Problem Message says which difficulties the speech recognizer is having with the audio input. The problems are mostly related with the user’s pronunciation or audio signal.

 **Use start/stop listening** - You can provide commands to have the speech recognizer either 'Start listening' or 'Stop listening'. These are set to their assumed defaults but can be changed to any word/phrase.

 

  **Speech Test Window**


![STW](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/images/SpeechTestWindow.png)
 

**Microphone Settings**:

Audio Input - By default, the input device that is set as the default recording device in the OS is used as the input for speech recognition. Setting this to Kinect will set the Kinect device as the input for speech recognition.

 

**Feedback:**

Enable Audio Feedback - Enables or disables the audio feedback provided for more interactive control. There are three options for the audio feedback:

<li>      None – No audio feedback is provided.</li>

<li>      Sound – When a speech event occurs, a sound is played.</li>

<li>      Voice – When a speech event occurs, an event message is spoken by a synthesized voice.</li>

Enable Tooltips - Shows tooltips for objects with voice command ability associated with its pick-action.

 

**Recognition Accuracy:**

Provides the user with a scale of pronunciation accuracy. More strict accuracy will yield more accurate word recognition but requires more precise pronunciation. More relaxed accuracy will allow more leniency on word pronunciation, but will increase the chances of a misinterpreting the word.

 

**Kinect Microphone Configuration:**

Helps improve the input audio signal and thus the quality of the speech recognition. The settings is applied only on the Kinect device.

 

Echo Cancellation Mode - Cancels or cancels/suppresses echo from the audio input.

Automatically gain control - Dynamically adjusts the gain to an appropriate level for a range of microphone input signal levels.

Noise suppression – Removes noise from microphone input signal.

 



 

 

**See Also**:

[Introduction to NUI](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/Introduction%20to%20NUI.md)

[Installing the NUI Component of GENESIS64](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/Installing%20NUI%20Component%20of%20GENESIS64.md)

[Configuring the NUI Device](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/Configuring%20NUI%20Device.md)

[Natural UI Section](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/Natural%20UI%20Section%20of%20the%20Ribbon.md)

[Interaction Modes](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/Interaction%20Modes.md)

Calibrating the NUI Device

Interacting with the NUI Device in Runtime

[Skeletal](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/Skeletal.md)

[Multi-Touch](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/Multi-Touch.md)

NUI Support for Multiple Window Scenarios

 
