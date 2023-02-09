# the-loud-bouncer
Exercise 11 of the "C# Class Development" course of the "C# Programming for Unity Game Development" Specialization by the University of Colorado via Coursera

## Description
Problem 1 - Getting started

Note: This exercise is Exercise 10 with a sound effect added. Download the solution to that exercise and use it as your starting point for this exercise.

Note: When you open the provided Unity project, it will probably start in an Untitled scene. Double-click Scene0 in the Scenes folder in the Project window to open the correct scene.

Problem 2 - Adding an audio clip and source

Add an audio folder to the Project window and copy an audio file (I used a short wav file) into the audio folder.

Select the Bouncer game object in the Hierarchy window and add an Audio Source component to it. Drag your audio clip from the Project window onto the AudioClip for the new Audio Source component. Uncheck the Play On Awake check box so the sound doesn't play when the Bouncer is added to the scene.

Problem 3 - Playing the sound

Add a field to the Bouncer class to store a reference to the AudioSource component and initialize the field in the Start method.

Add code to the Bouncer OnCollisionEnter2D method to play the sound effect.

When you run your game, you should hear your sound effect every time the Bouncer hits an edge of the screen.

## Getting Started

n/a

### Dependencies

+ Windows 10
+ .NET
+ Microsoft Visual Studio
+ Unity

### Installing

* Download link: [Github Repository](https://github.com/lyndonpanton/the-loud-bouncer)

### Executing program

1. Open the project's directory
2. Traverse: Exercise11 -> Build -> Windows -> x86
3. Run _Exercise11_ application

## Help

n/a

## Authors

Lyndon Mykal Panton
[lyndonpanton](https://github.com/lyndonpanton/)

## Version History

* 0.1
    * Initial Release

## Preview
n/a

## License

n/a

## Acknowledgments

n/a
