# Compositing Live Video and Stop Motion

DragonFrame can record Live video from the camera, but the video does not have the same dimensions as the still images captured from the camera:

- Camera images = 5184 X 3456
- Video = 1280 x 720

**Note:** The Live Video can be imported as a reference layer in DragonFrame to make sure that the timing matches up.

They must be composited in a separate program like [Davinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve)...

## Basic Method:

- Export the completed stop motion animation from DragonFrame at the same dimensions as the video:

  - cropped to 16:9
  - 1280 x 720 pixels

- Copy the live video from inside the Dragonframe project folder:
  `project folder > project.dgn > Tests > Test_000x.mov`

- Import both of them into Davinci Resolve and do the masking and compositing there.
