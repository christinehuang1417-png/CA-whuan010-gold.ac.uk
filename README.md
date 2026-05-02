
# Dialogue with Earth

## Introduction
The reflective exteriors of modern buildings act as "urban curtain walls," serving as a new form of screens. What was my role while capturing and collecting these images and their reflections? When I record images and store them in cloud storage, or share them on social media, am I merely an absent "self" in this network of image-based social interactions?

The continuous emergence of photography techniques and digital imaging technologies, developed to satisfy human desires for "interaction," also expands the content, semantics, and functionality of "screen displays." "The act of photography places the photographer in an unconventional state, and the people (or objects) in the photos are in another state," says Roland Barthes. The urban curtain walls (reflective exteriors of modern buildings) capture our visual attention, making us indifferent to the interior spaces. The interaction with these surfaces and the opportunity for self-admiration excite us. Different curtain walls evoke varying desires and curiosities: standing before a glass wall reflecting clouds and the blue sky, we may merge ourselves with this backdrop in a photo. Yet, taking a banal photo under the actual blue sky and white clouds might seem cliché and uncreative. However, the urban curtain walls provide a fresh sense of "creativity" that we tirelessly enjoy. Thus, these curtain walls also seem to take on the role of layer mergers.

From the perspective of topology and information density, digital maps, remote sensing, and social media do not simply “record” space; they rewrite the space. When power traverses space, it does not move through a pre-given spacetime, but constructs a spacetime field of its own. Here, the urban curtain wall becomes a crucial mediator: it flattens the world into an image surface that can be viewed and circulated, encouraging viewers to linger on the “shareable” layer while delegating the judgment of the “real” to devices and platforms. The curtain wall thus resembles both a screen and an algorithm-readable evidentiary plane: it produces novelty while simultaneously producing a form of visibility that can be evaluated, ranked, and scored.






## You need to supply the following hardware to show this project:

## 1. Display
The display can be a projector or any flat screen that supports HD (1920×1080) or higher resolution.

Recommended setup

· Orientation: Landscape (16:9)

· Mounting/placement: position the screen so the audience can comfortably read the grid and letters.


## 2. Camera (Built-in or USB)
The work uses a camera feed for hand-gesture recognition

· A laptop webcam works

· A USB webcam works


Placement：

· Try to keep the camera **roughly aligned with the screen’s central axis** (camera facing the audience, “looking through” the screen direction)

· Distance is flexible; adjust so hands are clearly visible and not cropped


## 3. Computer
A computer that can run a modern browser smoothly:

· macOS / Windows 

· Chrome is recommended for the most reliable camera permission handling and performance


Connection

· The computer must be connected to the screen/projector via HDMI / USB-C / DisplayPort (use any reliable HD cable/adapter)

## 4. Light
Gesture recognition works best when the audience’s hands are evenly lit

· Avoid strong backlight (e.g., bright window behind the audience)

· Use a soft, diffuse light if possible




## Installation
This project runs in a browser and should be hosted via a local server (recommended for camera permissions)

### Run locally 
1. Put the project folder on your computer
2. Start a local server, for example:
   · VS Code: install “P5 Projecte Creator” →  Open the folder with P5 Projecte Creator
4. Open the work in a browser:
   · `http://127.0.0.1:5500/`
5. When prompted, allow camera access





## Interaction
### Step 1 — Pinch to grab
The system tracks the thumb tip and index fingertip.

· When the two fingertips are close (pinched), you can grab letters that your pinch passes over.

· Keep pinching to carry the letter around the screen.


### Step 2 — Release to drop
· When the fingertips separate (release), the letter is released and **falls** from that position.

### Step 3 — Translation trigger
· When a falling letter reaches the bottom edge of the screen, it is captured and mapped into the background grid, where it becomes part of the Earth-language “translation” and can be read as an evolving conversation.

### Step 4 — Switch poems
· Click the “Change” button to switch poem/text sets.




## Calibration / Setup
· Framing: make sure hands appear fully in the camera view (avoid cropped fingertips).

· Lighting: increase ambient light if fingertips are not detected reliably.

· Distance: if the pinch is not recognised, move slightly closer/farther until the fingertips are stable.

· Stability: for exhibitions, a fixed camera mount/tripod is recommended.



## Requirements
· Browser: Chrome (recommended), Edge, Safari

· Libraries:
  · p5.js
 
  · ml5.js (handPose) 


· Permissions:
  · Camera access enabled for the local site



## Text (Wall Label)
Please place the following text next to the work:

Earth Conversation (2026) by Wenqian Huang

Interactive web artwork. The audience uses a pinch gesture (thumb and index finger) to pick up letters and release them into a grid of Earth-textures, where the letters are “translated” into an imagined language of the ground. Inspired by a NASA experience in which typed names are visualised through environmental imagery, the work explores translation as a poetic exchange—where calling, answering, and misrecognition become part of a shared conversation with the planet.




## Images
![38291769306552_ pic_hd](https://github.com/user-attachments/assets/1511525b-488b-4f7f-9cbf-36396b243d1

![38321769306556_ pic_hd](https://github.com/user-attachments/assets/e95b7354-9a61-4112-b027-316c18cce06c)
