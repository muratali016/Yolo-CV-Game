# Webcam Game with Computer Vision
### Ready-to-use colab notebook: https://colab.research.google.com/drive/17gQ17vGR3-1ogTyYsqy__7QaCzxP2nwI?usp=sharing


https://user-images.githubusercontent.com/77502485/188268419-4a6eb8ea-9257-48d0-936f-7faaf3d32a9d.mp4

# Webcam Game with Computer Vision
* **This open-source game was created by using Yolov7 and OpenCV. As you see in the video. **
* **If you are too close to the bomb, the screen will explode!**
* **You can try it also on your webcam**
* **Code can run on Both (CPU & GPU)**

 
## Only 2 Steps to run Code
You have to downloan this file and add to ypur directory to apply code right:
https://drive.google.com/file/d/1Zc_DCPG8-BPMxCeZvjziWiH2iF-_u9aZ/view?usp=sharing


Install requesting files
```
!git clone https://github.com/muratali016/Yolo-CV-Game.git
!git clone https://github.com/WongKinYiu/yolov7.git
!pip install cvzone
from google.colab import drive
drive.mount('/content/drive')
```
Apply!
```
%cd /content/yolov7
!python /content/Yolo-CV-Game/detect_video_game.py --weights /content/drive/MyDrive/face.pt --source /content/Yolo-CV-Game/video.mp4
```
On your webcam
```
%cd /content/yolov7
!python /content/Yolo-CV-Game/detect_video_game.py --weights /content/drive/MyDrive/face.pt --source 0
```
### Upgrade pip with the mentioned command below.
``` pip install --upgrade pip ```

### Install requirements with the mentioned command below.
 ``` pip install -r requirements.txt ```

### Using counter
 * ```%cd /content/Yolov7-cigarette-censor-and-smokers-face-recorder```
* ```%!python detect.py --weights best_cigarette.pt --conf 0.1 --source /content/Yolov7-cigarette-censor-and-smokers-face-recorder/example_img.jpg --cigarette_blurrate 50 --shape_detector /content/Yolov7-cigarette-censor-and-smokers-face-recorder/shape_predictor_68_face_landmarks.dat```
 
 
### Results!
![exp](https://user-images.githubusercontent.com/77502485/187298601-c4fb2b68-5eef-4210-81a0-ea95b9cfeae1.jpg)
![exp2](https://user-images.githubusercontent.com/77502485/187298605-0975d484-8640-4525-a3bd-37af32a5ff0e.jpg)


### Inference on a video:
https://www.youtube.com/watch?v=ld9nP8-ZsQw

### References
* https://github.com/WongKinYiu/yolov7

