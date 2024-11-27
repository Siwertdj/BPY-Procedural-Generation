# Procedural Terrain Generation

This project was made to generate a simple model of a landscape using several algorithm

## Description

We created a heightmap as a template, then erroded this to create a more realistic-looking mountain range. We populate this terrain with vegetation using Poisson disk sampling and use Quadtrees to make this process more efficient.

## Getting Started

### Dependencies

* This project can be ran as a script in Blender

### Installing and Executing the program

* Download Blender (blender.org, steam, etc.)
* Navigate to where your Blender Python-executable is located in the terminal window, and enter the following, to install the 'scipy' library using pip
```
'python.exe -m pip install scipy'
```
* Once installed, open the 'Scripting' tab in the Blender interface, then open the 'program.py' file.
* Click 'Run', and the program will start to build. This may take a while, depending on the scale of your terrain.


## Authors

Created by Siwert de Jong - [Itch.io](https://siwertdj.itch.io). [Github](https://github.com/Siwertdj/). [LinkedIn](https://www.linkedin.com/in/siwertdj/)

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

This project was developed as part of the Threedimensional Modelling course at Utrecht University, taught by Ron Vanderfeesten.
