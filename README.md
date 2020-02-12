# CSP-Deconstructions3

## DATA
### Assets
Sound files (.mp3, .wav)
3D object files (.obj)
Images (.jpg, .png)
### Script
#### Sky
- Color
- Image
#### Plane
- Position
- Rotation
- Dimensions
- Color
#### Trees
- Dimensions
- Color
#### Pyramids
- Dimensions
- Color
- Texture
- Sound
- Animation
#### Spheres
- Dimensions
- Color
- Texture
- Sound
- Animation
#### Boxes
- Dimensions
- Color
- Texture
- Sound
- Animation
#### Lighting
- Direction
- Intensity
- Width

## RENDER
### Scene
- Sky rendered
- Plane rendered
- Trees rendered
- Objects rendered

## SIMULATION
### Animations
- Objects transform/move according to animation data
- User's image changes depending on camera location in scene

## EVENTS
### Object hit
#### if controller enters the edge of object 
- referenced sound of object is triggered
- animation is run
#### if arrow keys are pressed
- camera angle changes depending on the direction
