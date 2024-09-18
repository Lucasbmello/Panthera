## Introduction.

This section is dedicated to a brief presentation to the Unity workspace and some initial configurations that we will use in this project.

## 1. First steps - How to create the project.

As soon as you initialize the Unity Hub, you will be able to create the project. There are three rendering types available, but we will use Universal Render Pipeline (URP), so be sure that your project has been created using this type of rendering, otherwise next steps won't work. In the Universal Render Pipeline, Shader Graph and URP packages are already installed, wich will be used to optimize and change the aesthetics of the project.

## 2. Enabling serial communication.

In the opened project, right cick on "Editor", then on "Project Settings", "Player" and search for "Api Compability". Change to "NET.Framework", otherwise you will face errors when trying to initialize the serial port.