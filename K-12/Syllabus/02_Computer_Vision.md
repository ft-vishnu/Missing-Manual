# Computer Vision with Python and Tello

Learn how computers interpret visual information using Python, OpenCV, and the Tello drone camera.

This course introduces computer vision through practical programming activities, progressing from basic image processing to real-time object detection and tracking. Learners will use camera data to build visual applications and explore how computer vision can support autonomous robotics.

## Course Objectives

By completing this course, learners will be able to:

- Understand the fundamentals of computer vision and digital images.
- Use OpenCV to read, display, modify, and process images.
- Understand pixels, colour spaces, thresholding, and contours.
- Capture, display, and record video from a Tello drone.
- Process camera frames in real time.
- Detect colours, shapes, and simple objects.
- Track an object's movement across successive video frames.
- Understand basic visual tracking algorithms and their limitations.
- Read supported Tello mission-pad information.
- Develop practical computer vision applications using Python.

## Course Syllabus

### 01. Introduction to Computer Vision

- What is computer vision?
- How computers interpret visual information
- Applications of computer vision in robotics and drones
- Computer vision vs. image processing
- Object detection vs. object tracking
- Introduction to OpenCV
- Setting up Python and OpenCV

### 02. Understanding Digital Images

- What is a digital image?
- Pixels, image dimensions, and resolution
- Colour channels and image representation
- RGB and BGR colour formats
- Grayscale images
- Reading image properties using OpenCV
- Displaying and saving images

**Practical activity:** Load an image, inspect its dimensions, and display its colour and grayscale versions.

### 03. Basic Image Processing

- Reading and displaying images
- Resizing and cropping
- Drawing lines, rectangles, and circles
- Adding text to images
- Image rotation and flipping
- Blurring and smoothing
- Basic image transformations
- Saving processed images

**Practical activity:** Create an image-processing program that modifies an image and annotates selected regions.

### 04. Colour Spaces and Thresholding

- Understanding colour values
- RGB/BGR and HSV colour spaces
- Why HSV is useful for colour detection
- Colour ranges and threshold values
- Binary thresholding
- Creating image masks
- Isolating objects by colour
- Handling changes in lighting

**Practical activity:** Build a program that detects a selected colour and highlights matching regions.

### 05. Contours and Shape Detection

- What are contours?
- Finding and drawing contours
- Contour area and perimeter
- Bounding rectangles
- Contour centres and centroids
- Detecting circles, triangles, and rectangles
- Filtering detections by size and shape
- Understanding false detections

**Practical activity:** Detect basic geometric shapes and display their locations on an image.

### 06. Accessing the Tello Camera

- Introduction to the Tello camera
- Understanding the Tello video stream
- Enabling the video stream using DJITelloPy
- Receiving camera frames in Python
- Displaying live video using OpenCV
- Understanding frame dimensions and frame rate
- Starting and stopping the video stream
- Handling stream interruptions

**Practical activity:** Build a live camera viewer that displays the Tello video feed.

### 07. Video Processing and Recording

- Understanding video as a sequence of frames
- Reading video files using OpenCV
- Processing frames continuously
- Displaying live video
- Recording and saving video
- Extracting individual frames
- Adding text and graphics to video
- Managing frame-processing performance
- Releasing video and camera resources correctly

**Practical activity:** Record a video, process its frames, and save selected images.

### 08. Real-Time Object Detection

- Understanding object detection
- Colour-based object detection
- Detecting objects using contours
- Filtering detections by size and shape
- Drawing bounding boxes around detected objects
- Calculating object centres
- Displaying object coordinates
- Detecting multiple candidate objects
- Handling false positives and missed detections

**Practical activity:** Detect a coloured object in a live camera feed and display its bounding box and centre.

### 09. Object Tracking with OpenCV

- Introduction to object tracking
- Detection vs. tracking
- Tracking an object across successive frames
- Colour-based tracking using HSV masks
- Contour-based tracking
- Selecting an object to track
- Calculating and displaying the target centre
- Drawing bounding boxes and tracking paths
- Understanding tracking algorithms
- Introduction to OpenCV trackers such as CSRT, where supported
- Tracking loss and target reacquisition
- Occlusion, lighting changes, and camera movement
- Comparing simple colour tracking with tracker-based approaches

**Practical activities:**

- Track a coloured ball or other selected object.
- Track an object in a recorded video.
- Track an object in the live Tello camera feed.
- Display the object's centre and movement path on screen.

### 10. Introduction to Visual Markers and Mission Pads

- What are visual markers?
- Applications of markers in robotics
- Introduction to Tello mission pads
- Reading mission-pad information using DJITelloPy
- Understanding supported mission-pad IDs
- Using marker information as a visual checkpoint
- Combining marker detection with simple mission logic
- Understanding the difference between marker recognition and general object detection

**Practical activity:** Detect a supported mission pad and display its ID when available.

*Hardware note: Tello mission-pad functionality requires a compatible model, such as the Tello EDU, and appropriate SDK settings. It is not available on every Tello model.*


## Learning Resources

- [OpenCV Official Tutorials](https://docs.opencv.org/4.x/d9/df8/tutorial_root.html)
- [OpenCV Python Tutorials](https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html)
- [OpenCV Tracking API](https://docs.opencv.org/4.x/d9/df8/group__tracking.html)
- [DJITelloPy GitHub Repository](https://github.com/damiafuentes/DJITelloPy)
- [DJITelloPy Documentation](https://djitellopy.readthedocs.io/en/latest/)
- [Take Picture Example](https://github.com/damiafuentes/DJITelloPy/blob/master/examples/take-picture.py)
- [Record Video Example](https://github.com/damiafuentes/DJITelloPy/blob/master/examples/record-video.py)
- [Mission-Pads Example](https://github.com/damiafuentes/DJITelloPy/blob/master/examples/mission-pads.py)

## Prerequisites

- Basic Python programming knowledge.
- A computer with Python and a code editor such as VS Code.
- OpenCV installed in the Python environment.
- A Tello drone for live-camera activities.

A physical drone is not required for the introductory modules. Learners can practise using sample images and recorded videos before moving to live camera experiments.

## Safety Guidelines

- Test computer vision programs using saved images and videos before connecting to a drone.
- Use an open, controlled area for flight activities.
- Keep the drone away from people, obstacles, and fragile objects.
- Do not assume that object detection or tracking guarantees safe navigation.
- Test any vision-based flight behaviour separately before combining it with autonomous flight.
- Keep a clear landing area and know how to stop the program and land the drone safely.

**Capture images. Detect objects. Track movement. Build visual intelligence for robotics.**