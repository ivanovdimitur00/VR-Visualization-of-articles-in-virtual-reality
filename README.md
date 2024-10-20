# Visualization of articles in virtual reality - diploma thesis
This is a project, related to my diploma thesis about visualization of articles in virtual reality. I use Unity, C# and Google VR SDK. The application is to be used on mobile phones.
<br/>
<br/>

## Table of contents
0. [Project status](#Project-status)
1. [Description](#Description)
2. [Project requirements](#Project-requirements)
3. [Key features and functionalities](#Key-features-and-functionalities)
4. [Structure](#Structure)
5. [Installation instructions](#Installation-instructions)
6. [Dependencies](#Dependencies)
7. [System requirements](#System-requirements)
8. [Usage examples](#Usage-examples)
9. [API references](#API-references)
10. [Bugs](#Bugs)
11. [Future improvements](#Futute-improvements)
12. [Used resources](#Used-resources)
<br/>

## Project status
Completed and working. Not expecting changes.
<br/>
<br/>

## Description
The purpose and goal of this project is to create an application to be able to visualize articles, such as furniture and interior in a virtual environment. </br>
The application is meant to be run on mobile phones, that have sensors that enable them to project virtual reality experiences. </br>
The technologies used to create this application are the Unity Engine, the C# programming language and google's VR SDK.
</br></br>
The intended audiences for this application are my scientific advisor, myself and theoretically, people that go shopping for furniture.
<br/>
<br/>

## Project rquirements
Requirements are listed on page 2 of [the diploma thesis](Diplomna_Rabota_Dimitar_Ivanov_2209013779.pdf). <br/>
In short, I was to explore the theoretical and technical aspects of creating a virtual reality experience. <br/>
Originally planned to use the Oculus VR SDK, but due to technical limitations, was swapped with Google's VR SDK. <br/>
The project is meant to be created with Unity Engine.
<br/>
<br/>

## Algorithm explanation
On the theoretical side you can look at [Stereoscopy](https://en.wikipedia.org/wiki/Stereoscopy).
On the technical side you can look at [simple Euclidean movement transform](https://en.wikipedia.org/wiki/Rigid_transformation).
<br/>
<br/>

## Key features and functionalities
* ### Key features
   * Users can move around in the environment using a controller;
   * Users can interact with certain objects.
* ### Functionalities
   * Interactable objects that produce light, display a picture or produce sound. All toggleable;
   * Auto-calibration of the joystick by the application.
<br/>
<br/>

## Structutre
The structure of the project is a standard Unity 3D project. The assets and builds are integrated inside of the file structure.
<br/>
<br/>

## Installation instructions
Download the final build of the project [here](https://drive.google.com/file/d/1KfO8Gui4aZdsnAFkeubUMBXNEgM4UdOc/view?usp=sharing) and run on your device.
<br/>
<br/>

## Dependencies
It is optional for your phone to have Google Cardboard installed to manage VR experiences. </br>
Your phone must have an accelerometer and gyroscope. </br>
To be able to move around in the environment, you must have [this controller](https://www.emag.bg/komplekt-vr-ochila-i-kontroler-shinecon-vr-c5-2/pd/DHP0THYBM/).
<br/>
<br/>

## System requirements
| System requirements            |
| ------------------------------ | 
| Android KitKat 4.4.X or higher |
| VR/AR services for mobile      |
 
<br/>
<br/>

## Usage examples
Assuming the user has a controller, he can:
* Walk around within a confined room of a house/apartment and collide with the walls and furniture.
* toggle a red cubic textile light, switch on and off the tv and turn the computer monitor on and off to listen to music.
<br/>

## API references
Nothing to mention here.
<br/>
<br/>

## Bugs
- [X] No bugs have been caught;
<br/>

## Future improvements
- [ ] Introduce sound effects for walking and interacting;
- [ ] Physics objects;
- [ ] Animated objects;
- [ ] Visible user avatar;
- [ ] Hand controllers;
- [ ] Context menus for texture swapping and placing/removing objects;
- [ ] Modular pieces for room creation.
<br/>

## Used resources
These can be viewed on the last page of [the diploma thesis](Diplomna_Rabota_Dimitar_Ivanov_2209013779.pdf). <br/>
