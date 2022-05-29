### [The Development and Implementation of a Smartphone Based Archery Analysis System](https://github.com/bruce6005/APP_1210_last_version/blob/master/ICCE_2021.pdf)

##### 過程
1.專案的過程中YOLO V4負責找出箭靶的落點
| <img src=https://user-images.githubusercontent.com/52123003/170857813-892d5049-604d-4a80-9c89-52939810b6e6.jpg width="800"> |
|:-----:|

2.辨識分數的部分藉由截出紅色與黃色的區塊並得出兩者的橢圓方程式
|<img src=https://user-images.githubusercontent.com/52123003/170857860-de8b9ec5-a71b-49c7-96bb-c66e5cf5f179.png width="388">|<img src=https://user-images.githubusercontent.com/52123003/170857867-efe04d44-0f46-455d-8351-5699429bfffa.png width="388">|
|:-----:|:-----:|

3.若直接藉由顏色判定會因為箭靶外圍較容易凹折的關係 而導致橢圓方程式與影像實際情況有出入
|<img src=https://user-images.githubusercontent.com/52123003/170857943-ebb05f6b-ae8d-465c-821a-7c6cff7b98d6.png width="800"> |
|:-----:|


4.所以我們選擇使用較為準確的紅色與黃色區塊為基準，藉由數學公式推論出其他區塊的所屬範圍
|<img src=https://user-images.githubusercontent.com/52123003/170858038-d9ce5db1-f930-45a5-b3b6-1139e5e644d5.png width="800">|
|:-----:|


5.結果
|<img src=https://user-images.githubusercontent.com/52123003/170858116-76012102-9c8b-4233-bf1d-b83738b48375.png width="250">|<img src=https://user-images.githubusercontent.com/52123003/170858152-dbb5247d-4ea5-4d66-aee0-da6671853841.png width="250">|<img src=https://user-images.githubusercontent.com/52123003/170858269-34dd9b26-9444-448e-8e6f-02c01eecca5e.png width="250">|
|:-----:|:-----:|:-----:|




