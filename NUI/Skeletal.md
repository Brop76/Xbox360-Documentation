Skeletal
========

In NUI Skeletal Tracking mode, the user's hands operate as the cursors.

Cursors
**Hovering** - While the cursor is in-range and not engaged, the cursors will appear as open hands representing the current location the user is hovering.


![Hovering](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/images/GWX_Skeletal_Mode_Hovering.png)
 

**Over interactive object** - Hovering directly over a dynamic object.

 
![OverIO](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/images/OverInteractiveObject.png)


**Interacting** - Selecting, dragging, etc.

 
![Interacting](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/images/GWX_Skeletal_Mode_Interacting.png)


**Out-of-range** - If at any time the user's hands exit the physical interaction zone, dots will represent the cursors. Though the user cannot interact with the system when out of range, the dots will represent the location of the users hands on screen.

 
![OutOfRange](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/images/GWX_Skeletal_Mode_Out-of-Range.png)



Gestures
NUI Skeletal Tracking mode also makes use of Gestures.

 

**Waving Gesture**

![Waving](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/images/GWX_Skeletal_Mode_Out-of-Range.png)

 

Users can wave their hand to start interaction. They can use their hands or body to interact with 2d and 3D objects. Commands vary according to settings.

 

Some actions that can be performed:

<ul>
  <li>Rotating or orbiting</li>
  <li>Panning and moving forward</li>
  <li>Zooming</li>
</ul>

**Pick Actions Using Gestures**
Pick actions can be triggered using Gesture Commands (in Skeletal Tracking Only).

 

First, enable IcoNui use for the open display by setting **Preferences > GwxRuntimeOptions > EnableNuiFeature** to **True**.

 

Then, set IcoNui to **Skeletal Tracking** mode.

 

Next, select the pick action of an object (e.g.: a button). The pick action will then have an option under **Execution Trigger – Natural UI** named **VoiceCommand**.

 

All that is needed is to select the type of gesture to associate with the pick action. Gesture types include:

<ul>
  <li>RightHandSwipe - gesture is recognized when right hand moved from right to left.</li>
  <li>LeftHandSwipe - gesture is recognized when left hand moves from left to right.</li>
</ul>


Voice Commanding
**Pre-commands**
In Skeletal Mode, commands can also be issued using voice commands. The user can issue voice commands in one of two ways:

The user can say the pre-command word. By default, the pre-command word is set to "Computer", but can be changed in the Natural User Interface Settings of the NUI Ribbon in GraphWorX64. Stating the pre-command word will give the user a "Listening" notification on the bottom of the on-screen interaction assistant. Once the "Listening" notification is given, the user may issue voice commands.

The user can also issue voice commands by using a physical gesture. By putting a hand close to the mouth, the user should receive a "Listening" notification on the bottom of the on-screen interaction assistant. Once the "Listening" notification is given, the user may issue voice commands.

**Giving a Voice Pre-command**

![VCommands](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/images/GWX_Voice_Command_Listening.png)

**Pick Actions Using Voice Commands**
Pick actions can be triggered using voice commands (in Skeletal Tracking only).

 

First, enable IcoNui use for the open display by setting **Preferences > GwxRuntimeOptions > EnableNuiFeature** to **True.**

 

Then, set IcoNui to **Skeletal Tracking mode**.

 

Next, select the pick action of an object (e.g.: a button). The pick action will then have an option under **Execution Trigger – Natural UI** named **VoiceCommand**.

 

All that is needed is to type the voice command you want associated with the pick action in that field. Notice that this voice command can also be a language alias, in the same way as with the pre-command in the IcoNui Speech recognition settings. [NOTE: Voice command text can only contain alphabetical characters and spaces.]

**Voice Interactions On-Screen GUI**
**Speech Recognition Status:**
<ul>

<li>    Listening… - User can speak.</li>

![Listening](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/images/Listening.png)

<li>    Listening Cancelled – The recognizer has not heard any spoken word in 5 seconds timeout.</li>

![ListeningC](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/images/ListeningCancelled.png)

<li>    Command Recognized – Spoken word has been recognized as a command.</li>

 </ul>
 

**Speech Recognition Problem Message:**
<ul>

<li>Too Loud, Too Fast, Too Noisy, Too Slow, No Signal: Problem with speech pronunciation.</li>

![TL](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/images/TooLoud.png)

<li>Audio Input Has Stopped – Input device has been disconnected. After the device is connected again, the NUI must be restarted.</li>

 </ul>

**See Also**:

[Introduction to NUI](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/Introduction%20to%20NUI.md)

[Installing the NUI Component of GENESIS64](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/Installing%20NUI%20Component%20of%20GENESIS64.md)

[Configuring the NUI Device](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/Configuring%20NUI%20Device.md)

[Natural UI Section](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/Natural%20UI%20Section%20of%20the%20Ribbon.md)

[Interaction Modes](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/Interaction%20Modes.md)

[Natural User Interface Settings](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/Natural%20User%20Interface%20Settings.md)

[Calibrating the NUI Device](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/Calibrating%20the%20NUI%20Device.md)

[Interacting with the NUI Device in Runtime](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/Interacting%20with%20NUI%20Device%20in%20Runtime.md)

[Multi-Touch](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/Multi-Touch.md)

[NUI Support for Multiple Window Scenarios](https://github.com/Brop76/Xbox360-Documentation/blob/main/NUI/NUI%20Support%20for%20Multiple%20Window%20Scenarios.md)

 
