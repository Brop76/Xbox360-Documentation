Configuring NUI Device
Skeletal Tracking Setup
1.5 m far away from the screen

Kinect placed 0.8 m high, bellow the screen

Skeletal Tracking Setup

<img width="317" height="276" alt="SkeletalTrackingSetup" src="https://github.com/user-attachments/assets/d799efa9-7645-4fce-8b1a-4b2e6751647e" />

Skeletal Tracking - Physical Interaction Zone
Curved-shape zone, natural hand movement

Auto-adaptable size - The size of the Physical Interaction Zone doesn’t depend on the user's size, so there is no need for any additional settings for its size.

Physical Interaction Zone

<img width="504" height="292" alt="PhysicalInteractionZone" src="https://github.com/user-attachments/assets/e60ffbe2-5b7d-41c6-9e41-9a22b4998fbd" />

Virtual Multi-touch Setup
Kinect set up below or above a display in approximately 1 meter (~40”) distance

Distance depends on the target screen size

Virtual Multi-touch Setup

<img width="340" height="282" alt="MultiSetup" src="https://github.com/user-attachments/assets/5740fb95-c66e-4a0e-8e69-8f9031cc4f7b" />

Virtual Multi-touch Calibration
Detection of Accidental Movement of the Kinect Device – When the user accidentally kicks the device, a message saying “Please recalibrate the Virtual Multi-touch” is shown and the interaction is stopped. From a technical aspect, the detection is based upon the accelerometer read out, so when the acceleration on one of the three axis is not zero, the accidental movement is detected and the virtual multi-touch must be recalibrated according to the new position of the Kinect device.
