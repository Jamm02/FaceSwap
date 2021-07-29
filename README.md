# FaceSwap
Swapping face of one image to another.

## About the project
### Tech Stack
The Technologies used for this project are
* Python
* OpenCV
### Implimentation
1. The algorithm first detects detects the face from the source image.
2. This face is then restructured according to the orientation of the target face using _delaunay triangulation_.
3. The newly constructed image is then applied on the destination image using a mask.
4. Final step is to apply seamless cloning to match the tone of the destination face with the newly constructed face.

## License
The [License](https://github.com/Jamm02/AirDraw/blob/master/LICENSE) Used for this Project.
