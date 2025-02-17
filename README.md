# Tennis Analysis

The **Tennis Analysis Project** is a comprehensive tool designed to analyze tennis match videos. This project leverages advanced computer vision techniques to detect and track players, monitor ball movements, and identify key events such as ball hits. The project utilizes the **YOLO** object detection model for player and ball detection, and a custom-trained model for court line detection.

## Key Features

- **Player Detection and Tracking**: Detects and tracks players throughout the video using the YOLO model, providing insights into player positions and movements.
- **Ball Tracking**: Monitors the ball's trajectory and identifies significant events such as ball hits, using a combination of YOLO detection and custom algorithms.
- **Court Line Detection**: Detects court lines and keypoints to provide a reference for player and ball positions, enhancing the analysis accuracy.
- **Mini Court Visualization**: Visualizes the court and player positions on a mini court, offering a clear and concise representation of the match dynamics.
- **Video Processing Utilities**: Includes utility functions for reading, processing, and saving video frames, making it easy to integrate and extend the project.

## Project Structure

The project is organized into several modules, each responsible for a specific aspect of the analysis:

- **Trackers**: Contains the player and ball tracking code.
- **Court Line Detector**: Includes the model and code for detecting court lines and keypoints.
- **Mini Court**: Provides the visualization of the court and player positions.
- **Utils**: Utility functions for video processing and other common tasks.
- **Models**: Directory for storing the pre-trained models used in the analysis.
- **Input Videos**: Directory for storing the input videos to be analyzed.
- **Output Videos**: Directory for storing the processed output videos.
