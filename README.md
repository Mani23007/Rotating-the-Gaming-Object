# Rotating-the-Gaming-Object

## Aim:
To develop a 3D application for rotating the gaming objects in unity.
## Algorithm:
### Step1:
Start
### Step2:
Click File -> Scene -> Select the scene -> Save as-> New folder(Scenes)-> File name (Expno1)
### Step3:
Click Hierarchy -> 3DObject -> Cylinder
Hierarchy -> 3DObject -> Capsule
Hierarchy -> 3DObject -> Text
Hierarchy -> Effects -> Particle system
### Step4:
Create a folder in project and name as Materials
Material folder -> Create -> Material (Name: Cylinder)
Inspector ->Surface Inputs ->BaseMAp (Choose the color)
Drag the Cylinder to the plane and release the mouse

Create a folder in project and name as Materials
Material folder -> Create -> Material (Name: Capsule)
Inspector ->Surface Inputs ->BaseMAp (Choose the color)
Drag the Capsule to the plane and release the mouse

### Step5:
Click Hierarchy -> DirectionalLight
Inspector -> Change the color to white (255,255,255)

### Step6:
Create a folder name Coding and create a C# file to add the coding in it.

### Step7:
To add our C# Script file to our selected object, click on the C# Script file and drag it to our selected objects in the Hierarchy window nad run the application.

### Step8:
Stop

## Program:
Object :1
```
using UnityEngine;

public class rotate1 : MonoBehaviour
{
    // Start is called once before the first execution of Update after the MonoBehaviour is created
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        transform.RotateAround(Vector3.right,Vector3.left,30*Time.deltaTime);
    }
}
```
Object : 2
```
using UnityEngine;

public class rotate2 : MonoBehaviour
{
    // Start is called once before the first execution of Update after the MonoBehaviour is created
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        transform.RotateAround(Vector3.up,Vector3.down,30*Time.deltaTime);
    }
}
```

## Output:
![Exp1 AR,VR](https://github.com/user-attachments/assets/ab206068-b37c-4038-87da-7d20a81ac19a)

## Result:
The development of two 3D application for rotating the gaming objects in unity is performed Successfully.
