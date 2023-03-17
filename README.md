### Hi there 👋

<!--
**SrijanBhattacharyya/SrijanBhattacharyya** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

HandTracker or HandTrakingModule
================================

It is a simple module to detect hands and do simple projects with hand recognition and machine learning.

Hand Detector
-------------
Uses:
  1. To find and detect hand.
  2. To find 21 landmarks in each hand.
  3. To find the distance between any 2 landmarks.
  4. To find if a finger is up or not.
  5. Can create a rectangle for the best hand detection zone.

Functions and their least requirements:
  1. HandDetector.FindHands:
      `Requires` image (with atleast one hand);
      `Returns` an image with hand landmarks drawn on it
  2. HandDetector.FindLocation:
      `Requires` image (with atleast one hand);
      `Returns` location of hand landmarks lmloc (dict), location of hand handloc (dict)
  3. HandDetector.DrawLandmarks:
      `Requires` image (with atleast one hand), index int value more than -1 but less than 21;
      `Returns` None
  4. HandDetector.fingersUp:
      `Requires` image (with atleast one hand);
      `Returns` info dict [fingername: bool]
  5. HandDetector.fingersUp_PROTO:
      `Requires` None;
      `Returns` info dict [fingername: bool]
  6. HandDetector.findDistance:
      `Requires` image (with atleast one hand), id numbers of any two landmarks;
      `Returns` image with those landmarks drawn on it and a line connection those and the center point of that line, length the disance between 
  7. HandDetector.FindingZone:
      `Requires` image (with atleast one hand);
      `Returns` location of rectangle FindingZonedim for the best hand detection zone

Other Uses
----------
  1. It can provide all the finger names used in this module, which is stored in `Fingers`.
  2. It can provide all the hand landmarks, which is stored in `HandLandmark`.
  3. It can provide all the ways to flip an image by 'opencv-python', which is stored in `CVFlipCodes`.
  4. It can provide all the corner point names used in this module, which is stored in `CornerPoints`.
  5. It can put text at any given coordinate on the image screen with a background, with the help of `PutText` function.

Hand Landmarks
--------------
![Hand Landmarks](https://user-images.githubusercontent.com/78896721/151704786-dce200a9-30f0-4b12-ae59-a061e60a833a.jpg)

Acknowledgement
---------------
For further information about any module, please see for the docs provided in each of the modules.

Thank You 🙂
------------
-->

Hay There
=========


```python
Name = "Srijan Bhattacharyya"

Interests = ["Coding", "Cryptography", "Problem Solving", "Cubing", "Photography", "Exploring various OS"]
Languages = ["C", "C++", "Python", "Bash"]
OS = ["Arch Linux", "Ubuntu", "Kali Linux", "Parrot Sec. OS", "Windows", "Linux Mint", "Kde Neon", "Ubuntu Server", "Manjaro", "Arch Server", "DietPi", "Raspberry Pi OS"]
DE_or_WM = ["KDE", "Genome", "i3wm"]

CURRENT_OS = "Arch Linux"
CURRENT_DE_or_WM = "i3wm"
MEMBER_OF = "IIC TMSL Tech Wing" 
```

### Tech Stack:
<div align=center>  

<img src="https://img.icons8.com/color/48/000000/c-programming.png">
<img src="https://img.icons8.com/color/48/000000/c-plus-plus-logo.png">
<img src="https://img.icons8.com/color/48/000000/python--v1.png"/>
<img src="https://img.icons8.com/color/48/000000/git.png"/>
<img src="https://img.icons8.com/color/48/000000/linux--v1.png"/>
<img src="https://img.icons8.com/color/48/000000/github--v1.png"/>
<img src="https://img.icons8.com/fluency/48/000000/visual-studio-code-2019.png"/>


</div>


Thank You 🙂
------------
