# single feature multiple task

![image](https://user-images.githubusercontent.com/103256030/169685835-c2edafc1-e671-477b-b542-4c64f3470077.png)

한가지 feature로 detection과 segmentation을 모두를 수행하기 위한 방법을 찾기 위한 코드로



feature_switch_test.ipynb에서 detection과 segmentation의 feature을 추출한 이후, 
feature을 서로 바꿔 성능을 측정합니다. 측정 결과는 파일 안에 나와 있습니다.

-----------------------


사용 모델

# detection

~~~
COCO-Detection/faster_rcnn_R_50_FPN_3x.yaml
~~~

# segmentation


~~~
COCO-InstanceSegmentation/mask_rcnn_R_50 _FPN_3x.yaml
~~~

-----------------------

# 결과

![image](https://user-images.githubusercontent.com/103256030/174029747-aa81c852-53af-4120-9670-8438c7a65a4a.png)
-----------------------
