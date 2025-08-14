# Week 2
## Applied 2 - Tue 05/08/2025
### What we did:
- Setting up Unity on personal device. Downloading the hub and installing the editor.
- Learned how to create 3D shapes and set it to a material (like a skin to the 3D shapes)
- Learned how to install an existing assit pack into the program and use it.
- Learned C# Coding for Unity in order to add properties onto the 3D object.
### Specific Activities:
1. Rotating an Object using this code on VScode:
```csharp
using UnityEngine;

public class Rotator : MonoBehaviour
{
    public float rotationSpeed = 45f;

    void Update()
    {
        transform.Rotate(Vector3.up * rotationSpeed * Time.deltaTime);
    }
}
```
- Then attach the object to the code by adding component and attaching the code file 'Rotator'.

2. Moving an object from different points.
- Using Translate:
```
using UnityEngine;

public class Mover : MonoBehaviour
{
    public float moveSpeed = 5f;
    public Vector3 moveDirection = Vector3.forward;

    void Update()
    {
        transform.Translate(moveDirection * moveSpeed * Time.deltaTime, Space.World);
    }
}
```

## Studio 2 - Thur 07/08/2025
### What we did:
- Made sketches of what the app would look like.
- Create a concept for the application.
- Start creating a prototype.

### Reflection:
- I came in late and did not come to the previous studio so I had to quickly catch up with the others.\
  Started off with sketching out my app idea and its interfaces.\
  Thought about how it's going to function, what gestures, etc.\
  My three main gestures:
  - Drag and drop item
  - To throw away, quickly drag it out of sight.
  - To undo and redo, make circle with hand anticlockwise (undo) and clockwise (redo).\
  The prototype was simply just a couch, performed a test with 2 participants, told them to do the gestures\
  While I make the motion with the couch.
