<br/>Face recognition and landmark demonstration running on the STM32N6-DK development board.


<br/>This demonstration highlights the potential of executing a face recognition and landmark application on the STM32N6 platform. 
<br/>Further optimization and fine-tuning of the model will be necessary in future updates.
<br/>It currently runs at a low frame rate due to insufficient optimization.


## Requirements
- STM32N6570-DK(CR5) + B-CAMS-IMX (SONY IMX335)

## How to use
- Connect the STM32N6-DK to STM32CubeProgrammer. ( Development boot mode )
- Download all the hex files.
- Download the face_recog_fsbl.hex file.
- Download the face_recog_appli.hex file.
- Download the face_recog_network_data_1.hex file.
- Download the face_recog_network_data_2.hex file.


## Run
- Set the STM32N6-DK board to Flash boot mode and power it on.
- Press the USER button to register up to 10 faces.

## Run
- YoloV8n : https://www.ultralytics.com/yolo
- FaceNet : https://github.com/shubham0204/FaceRecognition_With_FaceNet_Android
- FaseMesh : https://github.com/google-ai-edge/mediapipe/blob/master/docs/solutions/face_mesh.md

<br/>Further details will be updated later.
