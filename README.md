# Blockly Java Programming Generator 

A modified version of Blockly configured for introductory Java programming courses. This tool is a great way to visually learn how Java programming works.

## Purpose
This version adds Java functionality to Blockly. Simple way to learn Java basics and generate java code.

## Tools Needed

- git
- python3
- Terminal/PowerShell
- Modern browser (Firefox, Edge, Chrome)

## Setup Terminal Commands (MacOS / Windows)
** Run these in order **
1. git clone https://github.com/jpt5832/blockly-java-generator.git
2. cd blockly-java-generator
3. python3 -m http.server 8000 (inside blockly-java-generator directory)
4. Open in browser (after server has been started):
http://localhost:8000/demos/java_class/

- ** Keep local HTTP server running until you are finished using the tool. Press Ctrl + C to stop server) **

## Features
- Buttons-only block adding into environment
- Generate java program based off blocks added/connected in the environment
- Trimmed Java output
- Wrapped in public static void main(String[] args) (Main method)
- Ability to download Main.java
- Buttons to center, zoom in/out of environment


## Author
PSU Cybersecurity student/intern - Jayson Troxel

## Credits
https://github.com/toebes-extreme/blockly
