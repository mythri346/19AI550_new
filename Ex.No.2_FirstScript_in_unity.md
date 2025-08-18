# Ex.No: 2  Welcome Script in Unity
### DATE:  18/08/2025                                                                          
### REGISTER NUMBER : 212223240034
### AIM: 
 To learn the basic scripting in Unity and print welcome message in Console window. 
### Procedure:
1. Start the program
2. Open the Unity hub and Create a new 3D project
3. In Assets window, create the new folder and name it as Scripts
4. Create a new script with file name as FirstScript
5. Open the Script and print message "Welcome to Unity" inside the start function
6. Save the script
7. Create a new 3D game object in Hierarchy window and name it as 3DObject.
8. Add the component Firstscript in inspector window of 3Dobject.
9. Run the program
10. Stop the program.
### Program 
```
using UnityEngine;

public class simple : MonoBehaviour
{
    // Start is called once before the first execution of Update after the MonoBehaviour is created
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
       print("welcome to unity"); 
      // transform.Translate(0,0.2f,0);

    }
}
```
### Output:
<img width="1920" height="1080" alt="Screenshot (100)" src="https://github.com/user-attachments/assets/0b8d672d-5c5c-4cf3-a64e-000c81afbba1" />



### Result:
Thus the welcome script was printed on Console Window  sucessfully.

