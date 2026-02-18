# Blockly Java Programming Generator 

A modified version of Blockly configured for introductory Java programming courses. This tool is a great way to visually learn how Java programming works.

## Purpose
This version adds Java functionality within Blockly. It also adds categorized Add buttons for reliability on student laptops.

## Setup Commands (MacOS / Windows)

git clone https://github.com/yourusername/blockly-java-generator.git
cd blockly-java-generator
python3 -m http.server 8000

Open (after server has been started):
http://localhost:8000/demos/java_class/

## Features
- Buttons-only block adding
- Generate java program based off blocks added/connected in the environment
- Trimmed Java output
- Wrapped in public static void main(String[] args) (Main method)
- Download Main.java
- Buttons to center, zoom in, zoom out of environment

## Credits
https://github.com/toebes-extreme/blockly
