# Blockly Java Programming Generator 

A modified version of Blockly configured for introductory Java programming courses. This tool is a great way to visually learn how Java programming works. Intended as an educational tool for all introductory level Java programmers!


## Purpose
This version adds Java functionality to Blockly. Simple way to learn Java basics and generate java code.

## Tools Needed

- git
- python3
- Terminal/PowerShell
- Modern browser (Firefox, Edge, Chrome)

## First Time Setup Terminal Commands (MacOS/Windows/Linux)

There are two main ways to "install" this tool

A) MUST do first time regardless from Command Line (clone command)
   - git clone https://github.com/jpt5832/blockly-java-generator.git
     

1) Run Strictly from Command Line:
   - cd ~/blockly-java-generator
   - python3 -m http.server 8000 (start http server inside blockly-java-generator directory)
   - Open in browser (after server has been started): http://localhost:8000/demos/java_class/
      - ** Keep local HTTP server running until you are finished using the tool. Press Ctrl + C inside the terminal to stop server **
    
2) Run from GUI
    - From the Command Line run: mv blockly-java-generator ~/Desktop (change ~/Desktop to whatever preferred location)
    - Open the newly added blockly-java-generator on your Desktop or whatever location you specified
    - Navigate to /demos/java_class directory
         - You should only see index.html file in the java_class folder
     - Double-click the index.html file in the java_class folder to load the tool!

## Using the Tool Again
There are multiple ways to run this Tool again!

A) Make sure to pull commits before starting (in case a new update was released)
   - Commands:
      - cd ~/blockly-java-generator
      - git pull origin main

1) Start Tool again from the Command Line
    - cd ~/blockly-java-generator
    - python3 -m http.server 8000 (start inside blockly-java-generator directory)
  
2) Start directly by opening html file
    - From command line: mv blockly-java-generator ~/Desktop (this copies the files to the desktop)
    - Open the newly added blockly-java-generator on your Desktop
    - Navigate to /demos/java_class
         - You should only see index.html file in the java_class folder
     - Double-click index.html to load the tool!

## Features
- Buttons-only block adding into environment
- Generate java program based off blocks added/connected in the environment
- Trimmed clean Java output
- Wrapped in public static void main(String[] args) (Main method)
- Ability to download Main.java
- Buttons to center, zoom in/out of environment


## Updates
v2.0 - Released 02/20/2026
  - Added support for lists
  - Added for-each (enhanced for) loop

v2.2 - Various bug fixes with syntax errors

v2.32 - Syntax bug fix, added variable adding 1 shortcut (i++)

v3.00 - Huge bug fix update! - Released 02/25/2026
  - Fixed a ton of syntax errors for all loops
  - ending curly braces print/format properly
  - Lists length / get list values implemented correctly
  - Variables initate as intended
  - All loops & if/if-else statements work in conjunction to each other
  - Fixed Java code output


## Author
PSU Cybersecurity student/intern - Jayson Troxel

## Credits
https://github.com/toebes-extreme/blockly
