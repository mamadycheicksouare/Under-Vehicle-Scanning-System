# Under-Vehicle-Scanning-System

During my final-year internship at the Machinery Production Group, I developed an under-vehicle scanning system designed to enhance security by automatically scanning the underside of entering vehicles and detecting potential unauthorized objects or threats.

In the Python script, the scene is captured using OpenCV, and a yellow box is used to indicate the area that will be scanned and saved.



![yellow](https://github.com/user-attachments/assets/37d8aa0e-ff1c-4915-bd3f-d2a046b27662)


Then, the designated area is captured and saved. Whenever there is a significant change in pixels, the yellow box turns red to indicate a visible change.


![red](https://github.com/user-attachments/assets/c084c2eb-c3a1-4cb7-9f97-aa42f80e6c0c)

After the different frames are saved, they can be merged into a single panorama image using stitching algorithms. This panorama is then passed through an object detection model trained on a custom dataset.

Note: Note: This is not an open-source project, so I do not have the rights to share the code or certain details. This repository serves as a simple description of the work I completed.
