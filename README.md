✋ Touchless Interaction Demo – Hand Tracking with MediaPipe

This project demonstrates touchless interaction using real-time hand tracking technology.
Instead of using a mouse, keyboard, or touchscreen, your hand gestures control the interaction seamlessly.

The game “Catch the Mice” is used as an example to showcase this touch-free control.

👉 Interact with the system simply by pointing and moving your hand!

This project is a demo for hand-tracking and touchless interfaces — not just a game.

🎮 How It Works

The webcam activates and tracks your hand using MediaPipe’s Hand Landmarker model.

Your index fingertip is detected and visualized on the screen.

Animated mice (mouse.png) move randomly across the screen.

When your fingertip touches a mouse, it is considered caught, the mouse disappears, and a new one spawns at a random position.

Once all mice are caught, new ones appear automatically.

The demo runs for 60 seconds.

When time is up, your final score is displayed.

✨ Fully touch-free interaction — just move your hand in the air.

🧠 Technologies Used

Python

OpenCV — image processing, webcam input, overlay rendering

MediaPipe — real-time hand tracking using hand_landmarker.task

NumPy — vector math

Random / Time — spawning logic & timing

🛠️ Installation & Setup

After downloading the project, extract the ZIP file directly into your Documents folder.
Placing it in other directories may cause path-based issues that prevent the program from running correctly.

You can use Visual Studio Code as the recommended development environment.

This project requires Python 3.11.
The reason is that the libraries used here officially support versions up to Python 3.11, and using a newer version may lead to compatibility errors.

Once Python 3.11 is installed, be sure to install all required dependencies before running the program.
After installing the necessary libraries, you can launch the project normally.
