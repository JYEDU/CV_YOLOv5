# 2021 Computer Vision Term Project
4개 분야 선정하여 베이스라인 찍기
## My Repository
1. [2D Objection Detection](https://github.com/JYEDU/CV_YOLOv5)
2. [Scene Text Recognition](https://github.com/JYEDU/CV_Scene_Text_Recognition)
3. [Super Resolution](https://github.com/JYEDU/CV_Super_Resolution)
4. [Image to Image(Ther2RGB)](https://github.com/JYEDU/CV_Image-To-Image)

<br/><br/>
## 2D Objection Detection (YOLOv5)

1. Challenge Leaderboard

    - [LINK](http://203.250.148.129:3088/web/challenges/challenge-page/24/overview)
    
    
    
    
2. Object Detection 챌린지 개요

    - 비디오나 사진과 같은 디지털 영상에서 사람, 동물, 차와 같은 특정 클래스의 물체의 인스턴스를 탐지하는 중요한 컴퓨터 비전 작업 중 하나
    - 컴퓨터 비전 응용에 필요한 기본적인 정보를 제공하기 위한 계산 모델을 개발하는 것을 목표로 함

<br/>

![image](https://user-images.githubusercontent.com/87462769/143814263-9b1eca09-b181-4097-8901-208e637d558e.png)

<br/>

3. 방법론 (YOLOv5 - YOLOv5x)

    - YOLO (You Only Look Once) : 이미지 내의 bounding box와 class probability를 single regression 문제로 간주하여, 이미지를 한 번 보는 것으로 object의 종류와 위치를 추측함
    - 간단한 처리 과정으로 속도가 매우 빠르며, 이미지 전체를 한 번에 바라보는 방식으로 CLASS에 대한 맥락적 이해도가 높다는 장점이 있음
특히 작은 Object에 대해 상대적으로 낮은 정확도를 갖는다는 단점이 있음

<br/>

![image](https://user-images.githubusercontent.com/87462769/143814369-17b867c2-b198-4bc7-93c2-4369b7ccfc8a.png)

<br/>

4. 데이터 셋

    - MS COCO Dataset
    - Object Detection, Segmentation, Keypoint Detection 등을 위한 데이터 셋
    - train2017 : 훈련 및 검증용으로 사용
    - val2017 : 테스트용으로 사용


5. 참고자료

    - [[Paper](https://pjreddie.com/media/files/papers/yolo_1.pdf)] You look only once : Unified, Real-Time Object Detection
    - [[Youtube](https://www.youtube.com/watch?v=NM6lrxy0bxs)] You look only once : Unified, Real-Time Object Detection youtube
    - [[Github](https://github.com/ultralytics/yolov5)] Yolov5 Repository
    - [[Github](https://github.com/trancis31444/2D-Object-Detection-leaderboard)] 2D-Object-Detection-leaderboard Repository
    - [[Youtube](https://www.youtube.com/watch?v=V1lnjEATIlU)] 2D Object Detection 챌린지 및 베이스라인 설명

<br/><br/><br/><br/>
 
## 원복 과정에 대한 챌린지 제출 파일
### ① eval.ai 리더보드상의 기록 캡쳐본
![image](https://user-images.githubusercontent.com/87462769/143817735-5dba44ae-8c0a-49cb-9fe9-db4b98dfe8de.png)
### ② 베이스라인을 찍기 위한 나의 repository
[[Github](https://github.com/JYEDU/CV_YOLOv5)]
### ③ 제출 과정에 대한 동영상 링크(베이스라인 알고리즘 설명 및 베이스라인을 찍기 위한 과정을 설명)
[[Youtube](https://youtu.be/o_K5NsPXwTU)]
