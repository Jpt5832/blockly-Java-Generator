# Blockly Java Programming Generator 

A modified version of Blockly configured for introductory Java programming courses. This tool is a great way to visually learn how Java programming works.

## Purpose
This version adds Java functionality to Blockly. Simple way to learn Java basics and generate java code.

## Tools Needed

- git
- python3
- Terminal/PowerShell

## Setup Terminal Commands (MacOS / Windows)
** Run these in order **
1. git clone https://github.com/jpt5832/blockly-java-generator.git
2. cd blockly-java-generator
3. python3 -m http.server 8000

4. Open (after server has been started):
http://localhost:8000/demos/java_class/

## Features
- Buttons-only block adding
- Generate java program based off blocks added/connected in the environment
- Trimmed Java output
- Wrapped in public static void main(String[] args) (Main method)
- Download Main.java
- Buttons to center, zoom in, zoom out of environment


## Author
PSU student - Jayson Troxel

## Credits
https://github.com/toebes-extreme/blockly
