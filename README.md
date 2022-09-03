# Webcam Game with Computer Vision
### Ready-to-use colab notebook: https://colab.research.google.com/drive/17gQ17vGR3-1ogTyYsqy__7QaCzxP2nwI?usp=sharing


https://user-images.githubusercontent.com/77502485/188268419-4a6eb8ea-9257-48d0-936f-7faaf3d32a9d.mp4

# Webcam Game with Computer Vision
* **This open-source game was created by using Yolov7 and OpenCV. As you see in the video. **
* **If you are too close to the bomb, the screen will explode!**
* **You can try it also on your webcam**
* **Code can run on Both (CPU & GPU)**

 
## Only 2 Steps to run Code
* You have to downloan this file and add to ypur directory to apply code right:
* https://drive.google.com/file/d/1Zc_DCPG8-BPMxCeZvjziWiH2iF-_u9aZ/view?usp=sharing


**Install requesting files**
```
!git clone https://github.com/muratali016/Yolo-CV-Game.git
!git clone https://github.com/WongKinYiu/yolov7.git
!pip install cvzone
from google.colab import drive
drive.mount('/content/drive')
```
**Apply!**
```
%cd /content/yolov7
!python /content/Yolo-CV-Game/detect_video_game.py --weights /content/drive/MyDrive/face.pt --source /content/Yolo-CV-Game/video.mp4
```
**On your webcam**
```
%cd /content/yolov7
!python /content/Yolo-CV-Game/detect_video_game.py --weights /content/drive/MyDrive/face.pt --source 0
```

### References
* https://github.com/WongKinYiu/yolov7

