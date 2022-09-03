# Webcam Game with Computer Vision
### Ready-to-use colab notebook: https://colab.research.google.com/drive/17gQ17vGR3-1ogTyYsqy__7QaCzxP2nwI?usp=sharing


https://user-images.githubusercontent.com/77502485/188268419-4a6eb8ea-9257-48d0-936f-7faaf3d32a9d.mp4

# Webcam Game with Computer Vision
* **Censoring and counting all cigarettes on the screen and saving smoker's faces in the folder or any database**
* **Useful for public non-smoking areas**
* **Code can run on Both (CPU & GPU)**
* **Video/WebCam/External Camera/IP Stream Supported**


https://user-images.githubusercontent.com/77502485/188095525-84964058-0945-463a-9924-1b606007204a.mp4


## It is super easy to run
* **We are going to copy my repo and just download "traced_model.pt" which is already given by me in the code,
and we are good to go!**
 
## Steps to run Code
* clone the repository:
* ```git clone https://github.com/muratali016/Yolov7-cigarette-censor-and-smokers-face-recorder.git```
* Download traced_model.pt by link:https://drive.google.com/file/d/1ovsR0biNCnOZ9174bSkNS-5IMtYGa52b/view?usp=sharing and move this model to your directory 

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

