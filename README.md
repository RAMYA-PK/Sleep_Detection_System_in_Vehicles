# Sleep_Detection_System_in_Vehicles
The Sleep Drowsiness Detection System is a project designed to monitor and detect drowsiness in individuals, especially drivers, to prevent accidents caused by falling asleep at the wheel. The system uses Python along with computer vision and image processing techniques to track the user's eye movements and facial expressions in real-time.

Key Components:

Camera Integration: A camera (webcam or any external camera) is used to capture real-time video of the individual. This video serves as input for the detection algorithm.

Face and Eye Detection: Using computer vision libraries such as OpenCV and Dlib, the system detects the face and eyes of the individual. The eyes are tracked to identify whether they are open or closed.

Eye Aspect Ratio (EAR): The project calculates the Eye Aspect Ratio, which is a measure of the proportion of the eye’s width to its height. If the EAR falls below a certain threshold for a continuous period, the system concludes that the eyes are closed, indicating drowsiness.

Alert System: When drowsiness is detected, the system triggers an alert, such as a sound or vibration, to wake the individual and prevent any further risk.



Technologies and Libraries Used:

Python: The primary programming language for developing the project.

OpenCV: For image processing and real-time video analysis.

Dlib: For facial landmark detection, which helps in accurately tracking facial and eye movements.

Numpy: For numerical computations needed during the EAR calculation.


This project is highly beneficial in the field of road safety, providing a practical application of Python and computer vision techniques to save lives.
