# Industrial-Safety-Gears-detection-using-YOLOV8

![image](https://github.com/user-attachments/assets/c8901e42-928c-4cdc-918c-63a61457c3da)

This project implements an industrial safety gears detection system using the YOLOv8 object detection model. The system identifies various safety gear items, such as helmets, gloves, goggles, and vests, to ensure compliance with safety regulations in industrial environments.

Installation and Setup
1. Create a Conda Environment
Create a new Conda environment to manage dependencies:

```bash

conda create -n safety_gear_detection python=3.9
conda activate safety_gear_detection
```

2. Install PyTorch and YOLOv8
Install the required versions of PyTorch. Use the following command for CPU support:

```bash

pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu113
pip install ultralytics
```

3. Clone the YOLOv8 Repository (if applicable)
If you're using a specific implementation of YOLOv8, you might want to clone its repository:

```bash

git clone https://github.com/ultralytics/yolov8
cd yolov8

```

4. Install Requirements (if applicable)
If there are specific requirements for the YOLOv8 implementation, install them:

```bash

pip install -r requirements.txt
```

### Running the Model
###Load the YOLOv8 model: 
Use a pre-trained YOLOv8 model or your custom-trained model for safety gear detection.

###Test with images/videos: 
Detect safety gear from images, videos, or live camera feeds.

## Features

Real-time detection of safety gear via webcam  
Detects various safety gear items such as helmets, gloves, goggles, and vests from images and video files

## Contact

For any questions or collaborations, feel free to reach out!
