# Pothole Detection
### Objective:
The main objective of this was to Detect the Road Potholes. Since, while Driving our vehicles we face many potholes which leads to many severe accidents. So the same is also applied to the Self Driving Cars. Since we are in the era of Self-driving cars, we are trying to make it more advanced day-by-day but Road potholes may seems to be an issue in the process. So I tried to build a Pothole Detection Algorithm which will be helpful in detecting potholes which can also be implemented in Self-Driving Vehicles.


<img src="https://github.com/anon-cypher/PotholeDetection/blob/main/Animated%20GIF-downsized_large.gif?raw=true" />


### Data Description:
The Dataset consists of 665 images of 720x720 pixels.
#### Data:
Data can be downloaded from [here](https://public.roboflow.com/object-detection/pothole/1 "Pothole Dataset")

### Framework used:
* [yolov5](https://github.com/ultralytics/yolov5 "Yolov5")

### Libraries Used:
* Cython
* matplotlib>=3.2.2
* numpy>=1.18.5
* opencv-python>=4.1.2
* Pillow
* PyYAML>=5.3
* scipy>=1.4.1
* tensorboard>=2.2
* torch>=1.6.0
* torchvision>=0.7.0
* tqdm>=4.41.0

### Commands:
First Create a virtual conda environment and activate it using:

```
conda create -n <Environment Name> python=3.7
conda activate <Environment Name>
```

Now install are the required libraries using the command:

```
pip install -r requirements.txt
```

After successfully installing libraries, execute the following code to detect 'clip.mp4' which is our test data:

```
python detect.py --weights runs/train/yolov5s_results/weights/last.pt --img 416 --conf 0.5 --source clip.mp4
```

When the above code executed successfully we can see our detected video in 'runs/detect' directory.

### Troubleshoot
If facing any issue, contact:

<a href = 'https://www.linkedin.com/in/anon-cypher'> <img width = '40px' align= 'center' src="https://cdn4.iconfinder.com/data/icons/social-messaging-ui-color-shapes-2-free/128/social-linkedin-circle-512.png"/></a>
  </t></t>
<a href = 'https://www.instagram.com/anon.cypher'> <img width = '40px' align= 'center' src="https://cdn2.iconfinder.com/data/icons/social-media-2285/512/1_Instagram_colored_svg_1-512.png"/></a>
