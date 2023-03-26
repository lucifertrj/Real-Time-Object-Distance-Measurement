<div align="center">
<h1>Real-Time Object Detection and Distance Measurement</h1>
<img src="https://i.ytimg.com/vi/ftsUg5VlzIE/maxresdefault.jpg" width=80%>
</div>

### AccelATHON 3.0
Team Name: Cipher

### Problem Statement

Real World Distance measurement by detecting and identifying the Object using WebCam. A prototype that can help blind people navigate smoothly. 

Algorithm used: YoloV4:Yolo i.e., You only look once.
Dataset uses: COCO i.e., Common Objects in Context

Future Goal: Implementing the project on Hardware kit, i.e., ESP32 CAM. 

### Requirements

```py
pip install -r requirements.txt

```

## Code Flow

- Import OpenCV Module and create a function to detect objects.  
- Create two more functions to calculate Distance and Focal length
- Create an instance of DetectionModel and pass reference images to the detected object.
- Using cv2, capture the real-time Video using WebCam and measure distance in inches. 
## Screenshots

![outcome](https://user-images.githubusercontent.com/66197713/188265636-a2e529ba-800f-4a49-9643-fc3e4460ccd8.png)


## Presentation

[Canva Presentation- Team Cipher](https://www.canva.com/design/DAFLKeN0WFE/0tIHlfOiTvCe71TXL7bPWw/view?utm_content=DAFLKeN0WFE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## Future Aspects- Applications

- Self Driving Cars
- Vision to Blind
- Argumented Reality

## Conclusion

- In the given problem statement, Objects were detected successfully. 
- To detect the Objects successfully YOLO dataset came in handy.
- Implemented a Prototype for the problem statement i.e., to find the distance.
- In future this problem statement code will be dumped on Raspberry PI or ESP-32
## Authors

- [@TRJ_0751](https://www.twitter.com/TRJ_0751)
