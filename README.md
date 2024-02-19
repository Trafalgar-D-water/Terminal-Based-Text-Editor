# Viewer Application

Viewer is a simple text viewer/editor built in Java using the Java Native Access (JNA) library. It allows users to view and edit text files in a terminal-like interface. 

## Prerequisites
- Java Development Kit (JDK) installed on your machine.
- JNA library added to the project dependencies.

## Installation
1. Clone the repository: 
2. Navigate to the project directory:
## Compilation
Compile the Viewer application using the following command: javac -cp "path/to/jna.jar" Viewer.java
Replace "path/to/jna.jar" with the actual path to the JNA JAR file.

## Running the Application
Once compiled, you can run the Viewer application using the following command:java -cp .:"path/to/jna.jar" Viewer [filename]
## Usage
- Navigate through the text using arrow keys.
- Edit text using the keyboard.
- Save changes using Ctrl + S.
- Find text using Ctrl + F.

## Example
To open a file named "example.txt":
