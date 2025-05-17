🎮 Gesture-Controlled Fruit Ninja Game
A real-time computer vision game built using OpenCV and MediaPipe, where you slice falling fruits with hand gestures captured through your webcam—no mouse or keyboard needed!

✨ Features
Real-Time Hand Tracking with MediaPipe

Swipe Gesture Detection to simulate slicing

Smooth Fruit Falling Animation

Visual feedback: “SLICED!” when fruit is hit

Object-oriented structure with a custom Fruit class

🧰 Tech Stack
Python 3

OpenCV – image processing and webcam handling

MediaPipe – hand landmark detection

Math, Time, Random – game mechanics and logic

🕹 How It Works
Index finger is tracked using MediaPipe (landmark 8).

A "swipe" is detected if the fingertip moves a significant distance between frames.

Fruits fall from the top every 1.5 seconds.

If a swipe intersects a fruit's position — it's sliced!

📦 Future Improvements
Add fruit images and cutting animations

Implement scoring system and lives

Add sound effects for slicing

Support for multiplayer mode using multiple hands
