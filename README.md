# Unity VR Experiments

:sparkles: This is me, learning to do VR using Unity :sparkles:

## Project

For as long as is feasible, this repo will contain just one Unity project, with the different experiments being implemented as different scenes. This will hopefully encourage me to re-use code between scenes, and to eventually end up with a body of common code that can be used to seed other projects.

At time of writing Unity 2020.3.24f1 is being used.

Relevant XR package versions are:

 * XR Interaction Toolkit 2.0.1
 * XR Plugin Management 4.2.1

## Scenes

### Teleporter Scene

Demonstrates basic teleportation. Both controllers can be used to to teleport. The teleport destination is chosen using a ray that is only activated when the analog stick is pointing north (see [Assets/Scripts/RayToggle.cs](Assets/Scripts/RayToggle.cs)).

### Grab Scene

Similar to Teleporter Scene, but now there is an object that can be grabbed.

### Magnesis Scene (work in progress)

Similar to Grab Scene, but now XR Ray Interactors are used for both teleportation and interacting with objects. Which XR Ray Interactor is active is determined by whether an action button is pressed on the controller.

Once captured, objects can be moved around using the analog stick (similar to the magnesis effect in Breath of the Wild). Objects simply fall to the ground when released.

This scene incorporates haptic feedback, while objects are held.

## License

This code should be considered to be in the public domain.
