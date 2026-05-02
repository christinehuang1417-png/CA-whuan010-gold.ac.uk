
# Urban Building

## Introduction
The reflective exteriors of modern buildings act as "urban curtain walls," serving as a new form of screens. What was my role while capturing and collecting these images and their reflections? When I record images and store them in cloud storage, or share them on social media, am I merely an absent "self" in this network of image-based social interactions?

The continuous emergence of photography techniques and digital imaging technologies, developed to satisfy human desires for "interaction," also expands the content, semantics, and functionality of "screen displays." "The act of photography places the photographer in an unconventional state, and the people (or objects) in the photos are in another state," says Roland Barthes. The urban curtain walls (reflective exteriors of modern buildings) capture our visual attention, making us indifferent to the interior spaces. The interaction with these surfaces and the opportunity for self-admiration excite us. Different curtain walls evoke varying desires and curiosities: standing before a glass wall reflecting clouds and the blue sky, we may merge ourselves with this backdrop in a photo. Yet, taking a banal photo under the actual blue sky and white clouds might seem cliché and uncreative. However, the urban curtain walls provide a fresh sense of "creativity" that we tirelessly enjoy. Thus, these curtain walls also seem to take on the role of layer mergers.

From the perspective of topology and information density, digital maps, remote sensing, and social media do not simply “record” space; they rewrite the space. When power traverses space, it does not move through a pre-given spacetime, but constructs a spacetime field of its own. Here, the urban curtain wall becomes a crucial mediator: it flattens the world into an image surface that can be viewed and circulated, encouraging viewers to linger on the “shareable” layer while delegating the judgment of the “real” to devices and platforms. The curtain wall thus resembles both a screen and an algorithm-readable evidentiary plane: it produces novelty while simultaneously producing a form of visibility that can be evaluated, ranked, and scored.


## Video Documentation

Video link: https://youtu.be/pzj1fBUz-h8

## Project Description

**Urban Building** is an interactive audiovisual environment that explores the reflective exteriors of modern buildings as “urban curtain walls” — surfaces that operate simultaneously as mirrors, screens, image machines, and algorithm-readable layers.

The project began from my repeated act of photographing reflective glass and mirror-like facades in London. These surfaces produced a strange double condition: they belonged to the physical city, yet they also created an alternate visual space where sky, buildings, streets, bodies, and cameras were flattened into a new image surface.

Instead of treating the screen as a bounded technological device, this project reconsiders the screen as a reflective urban surface. The building facade becomes a place where seeing, recording, sharing, and self-positioning are continuously reorganised.

Through 2D-to-3D reconstruction, point-cloud modelling, TouchDesigner navigation, controller-based interaction, and Max/MSP sound experiments, the work transforms captured facade reflections into a navigable “mirror world.” The audience/player moves through this reconstructed urban surface while triggering glass-like sounds that imagine what might be preserved, hidden, or trapped inside the reflective skin of the city.

## Concept

The project asks:

- What happens when the reflective facade of a building becomes a screen?
- When we photograph these reflections, are we recording the city, or are we participating in a system of image-based self-construction?
- Do digital maps, remote sensing, cloud storage, and social media simply record space, or do they rewrite it?
- Can sound intervene in the silent reflective surface of the urban curtain wall?
- Once an image is captured and stored, does the facade also acquire a temporal quality?

In this work, the urban facade is not only an architectural surface. It becomes a mediator between the physical city and its image-based double. It flattens the world into something viewable, shareable, editable, and navigable.

## You need to supply the following hardware to show this project:

## 1. Display

The work can be shown through a projector or a large flat screen.

Recommended setup:

- Resolution: HD 1920×1080 or higher
- Orientation: Landscape 16:9
- Placement: the screen should be large enough for the audience to perceive the point-cloud environment clearly
- For exhibition settings, projection works well in a darker space, as the work contains many high-contrast reflective and point-cloud visuals

## 2. Computer

A computer capable of running TouchDesigner and Max/MSP smoothly is required.

Recommended:

- macOS or Windows
- A dedicated GPU is recommended if the point-cloud file is heavy
- At least 8GB RAM, preferably 16GB or more
- Stable audio output for live sound playback

## 3. Controller

A game controller is used as the main interaction device.

The controller allows the audience/player to navigate the reconstructed mirror world and trigger sound events. It also works as a bridge between the visual environment in TouchDesigner and the sound system in Max/MSP.

Recommended:

- USB or Bluetooth game controller
- Test the controller before exhibition
- Keep the controller close to the screen or projection area so the interaction feels connected to the visual space

## 4. Audio Output

The work includes a sound component generated through Max/MSP.

Recommended:

- External speakers or gallery sound system
- Stereo output is recommended
- Speakers should be placed near the screen/projection area, so the sound feels spatially connected to the facade environment

## 5. Optional: Keyboard and Mouse

Keyboard and mouse can be used for testing, debugging, or backup navigation inside TouchDesigner.

They are also useful during setup if the controller connection is unstable.

## Software Requirements

This project uses:

- TouchDesigner
- Max/MSP
- Game controller input
- Point-cloud / PLY file
- Audio output device or speakers

Optional / experimental:

- VR plugin for TouchDesigner  
  This was explored as a possible future direction, but it is not required for the current version.

## Installation

1. Download or clone this repository.

2. Make sure the project folder contains the required assets, such as:

   - TouchDesigner project file
   - Max/MSP patch
   - Point-cloud / PLY model
   - Image or video texture assets
   - Any required controller or input plugin files

3. Install TouchDesigner.

4. Install Max/MSP.

5. Connect the game controller to the computer.

6. Connect the computer to the display or projector.

7. Connect the computer to speakers or an external sound system.

8. Open the TouchDesigner project file.

9. Check that the point-cloud / PLY file path is correctly linked.

10. Open the Max/MSP patch.

11. Turn on audio in Max/MSP.

12. Test the controller input.

13. Enter Perform Mode in TouchDesigner when ready to present.

## Running the Work

### Step 1 — Launch TouchDesigner

Open the TouchDesigner file and check whether the point-cloud model loads correctly.

The visual environment is built from 2D images of urban reflections that were transformed into a navigable 3D point-cloud space. This space functions as a reconstructed “mirror world” based on the reflective surfaces of urban buildings.

### Step 2 — Launch Max/MSP

Open the Max/MSP patch and turn on audio.

The sound component is inspired by the timbre of the glass harmonica. It imagines a kind of sound that does not naturally exist inside the glass facades of urban buildings, but could be poetically preserved or activated through interaction.

### Step 3 — Connect the Controller

Use the controller to navigate the visual world and trigger sound events.

The controller acts as a shared interface between the visual system and the sonic system. Instead of using the player’s camera position as a continuous signal, the current version uses controller-based interaction for greater stability.

### Step 4 — Present the Work

For exhibition:

- Show the TouchDesigner output in full screen or Perform Mode
- Keep Max/MSP running in the background
- Make sure the speakers are active
- Let the audience/player hold the controller and move through the mirror world

## Interaction

### Navigation

The audience/player can move through the reconstructed urban facade environment using the controller.

The experience is intended to feel game-like: the audience is not only looking at an image of the city, but moving inside a distorted space produced by reflection, photography, and reconstruction.

### Sound Trigger

Controller buttons send signals to Max/MSP and activate glass-like sound events.

The sound is not meant to represent the literal sound of buildings. Instead, it explores a speculative question: if the urban facade is a mirror-world, what kind of sound might be hidden, preserved, or imagined inside it?

### Visual Experience

The work uses point-cloud aesthetics to make the reconstructed city feel unstable, incomplete, and suspended.

The audience moves through a space that appears both architectural and image-based, both physical and virtual. The urban facade becomes a surface that can be entered, navigated, and sonified.

## Calibration / Setup

Before showing the work, check the following:

### TouchDesigner

- Make sure the PLY / point-cloud file is correctly loaded
- Check the frame rate
- Reduce point density if the project runs too slowly
- Make sure the output resolution matches the display or projector
- Test Perform Mode before the exhibition

### Max/MSP

- Turn audio on
- Check the correct audio output device
- Test the volume level
- Make sure the sound is not too harsh or too loud in the exhibition space
- Test whether controller inputs are correctly triggering sound events

### Controller

- Check that the controller is connected
- Test all mapped buttons
- If using Bluetooth, make sure the battery is charged
- Keep a USB cable nearby as backup

### Display

- Use landscape orientation
- Avoid excessive ambient light if using projection
- Make sure the audience can clearly see the point-cloud details

### Audio

- Test the speakers before presentation
- Adjust volume according to the size of the space
- Avoid placing speakers too far away from the screen, unless a spatial sound setup is intended

## Troubleshooting

### The point cloud does not appear

- Check whether the PLY file path is correct
- Make sure the asset folder has not been moved
- Reload the file in TouchDesigner
- Check whether the point-cloud component is active

### The project is running slowly

- Reduce the density or size of the point-cloud file
- Lower the output resolution
- Close other heavy applications
- Use a computer with a stronger GPU if possible

### The controller is not responding

- Reconnect the controller
- Check whether the controller is recognised by the operating system
- Try a wired connection
- Restart TouchDesigner after connecting the controller

### There is no sound

- Turn on audio in Max/MSP
- Check the audio output device
- Make sure speakers are connected
- Check whether controller signals are reaching the Max/MSP patch
- Increase the volume gradually to avoid sudden loud output

### The sound is too harsh

- Lower the output volume
- Adjust filtering or envelope settings in Max/MSP
- Reduce rapid triggering from the controller
- Use softer speaker placement if the space is small

## Suggested Repository Structure

```text
Urban-Building/
│
├── TouchDesigner/
│   └── UrbanBuilding.toe
│
├── MaxMSP/
│   └── UrbanBuilding.maxpat
│
├── Assets/
│   ├── pointcloud/
│   ├── images/
│   └── sound/
│
├── Documentation/
│   └── screenshots/
│
└── README.md
