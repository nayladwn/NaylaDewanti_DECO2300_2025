# NaylaDewanti_DECO2300_2025

## Week 1
### Applied 1 - Tue 29/07/2025
Wasn't here for the class, I was away. Caught up on the lecture instead.
### Studio 1 - Thu 31/07/2025
Wasn't here for the class, I was away. Caught up on the applied class instead.

## Week 2
### Applied 2 - Tue 05/08/2025
#### What we did:
- Setting up Unity on personal device. Downloading the hub and installing the editor.
- Learned how to create 3D shapes and set it to a material (like a skin to the 3D shapes)
- Learned how to install an existing assit pack into the program and use it.
- Learned C# Coding for Unity in order to add properties onto the 3D object.
#### Specific Activities:
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
