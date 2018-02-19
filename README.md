# In-house Demo for Unity Cinemachine

## What this project demonstrates
This project demos the implementation of a basic follow and look at target camera using Unity Cinemachine. It uses the vehicle asset from Unity Standard Assets and setups a camera to follow the vehicle using cinemachine.

## Implementation Details

### Import the Cinemachine package from asset store
- Download the Cinemachine as plugin from the asset store. Linked [here](http://u3d.as/GJQ).
- Import the Cinemachine into your project.

### Import vehicle package from Standard Assets (Optional)
- If you want to try the feature on some standard assets, then import the vehicle package.
- But preferably, you should have your own project in which you want to use the Cinemachine. In that case, skip this step.

### Setup the test scene
- Add any character you want the Cinemachine cameras to follow or look at.
If using the vehicles from Standard Asset:
- Add a plane to the scene, scale it up and set some random material to it.
- Add the car prefab to the scene and try it out.

### Add the Cinemachine Virtual Camera
- Simply go to the Cinemachine tab in the menu and add virtual camera. This will add a Cinemachine brain to your camera and create a virtual camera object in the scne.
- Add your object to the follow and look at transforms attributes and set the offset values to your liking.
- Adjust all the values you need to set the proper setting for the camera.
- Remember to increase the Yaw damping to some value and notice the affect.

## Useful Resources

* [Using Cinemachine: Getting Started](https://unity3d.com/learn/tutorials/topics/animation/using-cinemachine-getting-started?playlist=17099)
* [Cinemachine Home](http://www.cinemachineimagery.com/)

## Requirements
### Running the sample

* This demo was build using Unity 2017.3.0f3, so it is recommended you try it on this version or later.
