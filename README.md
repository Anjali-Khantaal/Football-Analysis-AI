# Football-Analysis-AI

This project demonstrates the use of machine learning, deep learning, and computer vision to build a comprehensive football analysis system. It includes object detection using YOLOv8, object tracking, team classification, and measurement of player movement, speed, and distance covered.

## Features
- **Object Detection:** Detect players, referees, and footballs using YOLOv8.
- **Custom Training:** Fine-tune and train your own YOLO model on a custom dataset.
- **Team Classification:** Use KMeans clustering for t-shirt color segmentation to assign players to teams.
- **Camera Motion:** Measure camera movement between frames using optical flow.
- **Perspective Transformation:** Apply perspective transformation to measure player movement in real-world units (meters).
- **Speed & Distance:** Calculate player speed and distance covered during the match.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/Football-Analysis-AI.git
    cd Football-Analysis-AI
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Object Detection:**
   - Detect players, referees, and footballs using YOLOv8 provided by Ultralytics.

2. **Custom Object Detector:**
   - Train and fine-tune your own YOLO model on custom data to improve detection accuracy.

3. **Team Assignment:**
   - Use KMeans to cluster pixel values and identify team colors based on t-shirts.

4. **Camera and Player Movement:**
   - Use optical flow for camera movement detection and perspective transformation to measure player movement in meters.

5. **Player Speed Calculation:**
   - Track players across frames and calculate speed and distance covered.

## Libraries Used
- [Ultralytics YOLOv8](https://github.com/ultralytics/yolov8)
- [OpenCV](https://opencv.org/)
- [KMeans Clustering](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)
- [Optical Flow](https://docs.opencv.org/3.4/d4/dee/tutorial_optical_flow.html)
- [Perspective Transformation](https://docs.opencv.org/3.4/da/d54/group__imgproc__transform.html)

## Contributing

Contributions are welcome! Feel free to submit pull requests to improve the project or add new features.

## License

This project is licensed under the MIT License.
