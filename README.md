# Research record - undergraduate research student

## 1. Piano Project - Yeongmin Ko
- 07/19/2023: <a href="https://github.com/PSLeon24/Research_AI/blob/main/Hand%20Landmark%20Detection/docs/2023_07_19_Hand-Landmark-Detection-Experiments.pdf">Hand Landmark Detection Experiment 1</a>: The accuracy comparison for the middle finger of both hands and left hand.
- 08/03/2023: <b><a href="https://github.com/PSLeon24/Research_AI/blob/main/Hand%20Landmark%20Detection/Piano-Keyboard-Detection(0803)/Piano_keyboard_detection_project/C3Pap_openpose/Object_Detection_with_YOLO_v5_keyboard.ipynb">Piano Keyboard Detection using YOLOv5</a></b>
  - <a href="https://github.com/PSLeon24/Research_AI/blob/main/Hand%20Landmark%20Detection/Piano-Keyboard-Detection(0803)/Piano-Keyboard-Detection(0803).pdf">read more</a>
- 08/04/2023: <a href="https://github.com/PSLeon24/Research_AI/blob/main/Hand%20Landmark%20Detection/docs/2023_08_04_Hand-Landmark-Detection.pdf">Hand Landmark Detection Experiment 2</a>: The accuracy comparison for the middle finger of both hands and left hand.
  - The dataset has been reinforced than the experiment conducted on July 19th.
- 08/09/2023: <b><a href="https://github.com/PSLeon24/Research_AI/blob/main/Hand%20Landmark%20Detection/Hand-Landmark-Detection%20-%20SSD(0809).pdf">Piano Keyboard Detection for SSD</a></b>
  - <a href="https://github.com/PSLeon24/Research_AI/blob/main/Hand%20Landmark%20Detection/Keyboard_Object_Detection_Model_for_SSD.ipynb">Colab Link</a>
- 08/16/2023 ~ 08/18/2023: <a href="https://github.com/PSLeon24/Research_AI/blob/main/Hand%20Landmark%20Detection/comparison_result_2023-08-16/Piano-Keyboard-Detection_YOLOv5_SSD_Comparison.pdf">Evaluation Metric Comparison(YOLOv5, SSD MobileNet)</a>
- 08/18/2023: <a href="https://github.com/PSLeon24/Research_AI/blob/main/Hand%20Landmark%20Detection/Draw%20PR%20Curves/Draw%20PR%20curves(SSD%2C%20YOLOv5).ipynb">Draw PR curves to compare for YOLOv5 and SSD model respectively</a> (IoU threshold: 0.50 ~ 0.95 in increments of 0.05)<br>I got precision score and recall score about test data using https://github.com/Cartucho/mAP .
- 08/21/2023: Drawing PR curves was modified to compare to the same training steps.
  
  - This image below is pr curves I said.
 
  |YOLOv5 PR curves|SSD MobileNet PR curves|
  |---|---|
  |![yolov5g](https://github.com/dalabdgw/Experimental_Results/assets/135303032/8786162e-52ce-47a8-b5bf-912801c2565a)|![image](https://github.com/PSLeon24/Research_AI/assets/59058869/48994d7b-4c28-4b44-8ac3-6ffc1ca3c0e5)|

- 08/21/2023 ~ 08/22/2023: I have found some gloves tracking hand to extract skeleton data. - <b><a href="https://github.com/PSLeon24/Research_AI/blob/main/Hand%20Landmark%20Detection/docs/The%20finger%20tracking%20device.pdf">summary</a></b>
- 08/28/2023: <b><a href="https://github.com/PSLeon24/Research_AI/blob/main/Hand%20Landmark%20Detection/docs/Data%20Capturing%20Environment.pdf">How to capture hand pose data</a></b>
- 08/31/2023: <a href="https://github.com/PSLeon24/Research_AI/blob/main/Hand%20Landmark%20Detection/docs/2023_08_31_3D%20hand%20pose%20estimation%20using%20ResNet.pdf">3D hand pose estimation using ResNet</a>
- 09/11/2023: <a href="https://github.com/PSLeon24/Research_AI/blob/main/Hand%20Landmark%20Detection/docs/2023_09_11_3D%20hand%20pose%20estimation.pdf">The summary how to implement 3D hand pose estimation</a>
- 09/06/2023 ~ 09/14/2023: <a href="https://github.com/PSLeon24/Research_AI/blob/main/Hand%20Landmark%20Detection/Hand%20Pose%20Estimation%20based%20ResNet-50%20with%20PyTorch/ResNet-50%20Based%20Hand%20Pose%20Estimation.ipynb">3d Hand Pose Estimation based ResNet-50 with PyTorch</a>
  - <a href="https://github.com/PSLeon24/Research_AI/blob/main/Hand%20Landmark%20Detection/Hand%20Pose%20Estimation%20based%20ResNet-50%20with%20PyTorch/docs/ResNet-50%20Based%20Hand%20Pose%20Estimation%20Implementation.pdf">read more</a>
- 09/20/2023: <a href="https://github.com/PSLeon24/Research_AI/blob/main/Hand%20Landmark%20Detection/docs/Algorithms%20extracting%203d%20hand%20skeleton(0920).pdf">Finding out Algorithms extracting 3d hand skeleton</a>
- 09/26/2023: <a href="https://github.com/dalabdgw">decorate Github page</a>
-------

## 2. Person Identification Project - Yeongmin Ko
- 08/23/2023: I have found some paper regarding person identification about face recognition or face verification, etc through Google Scholar and I summarized that. - <b><a href="https://github.com/PSLeon24/Research_AI/blob/main/Person%20Identification/summary%20on%20Person%20Identification.pdf">summary</a></b>
- 08/24/2023: I have found open sources regarding face recognition. - <b><a href="https://github.com/PSLeon24/Research_AI/blob/main/Person%20Identification/finding%20out%20open%20sources%20about%20Person%20Identification.pdf">summary</a></b>
- 08/25/2023: I selected a open source named deep face for our research. And then, I made some test to check doing recognition correctly.
  - <b><a href="https://github.com/PSLeon24/Research_AI/blob/main/Person%20Identification/result_test%20face%20recognition%20-%201.pdf">the result of test 1</a></b>
  - <b><a href="https://github.com/PSLeon24/Research_AI/blob/main/Person%20Identification/result_test%20face%20recognition%20-%202.pdf">the result of test 2</a></b>
  - <b><a href="https://github.com/PSLeon24/Research_AI/blob/main/Person%20Identification/Recognition%20Test.ipynb">test code</a></b>
  
  ![image](https://github.com/dalabdgw/Experimental_Results/assets/135303032/dda2c609-46ed-4dae-9fc4-db354ca1ada8)

-------

## 3. Build a dataset of hands playing the piano
- 10/04/2023: I have found annotation tools. <a href="https://github.com/PSLeon24/Research_AI/blob/main/Build%20a%20dataset%20of%20hands%20playing%20the%20piano/docs/2023_10_04_Build%20a%20dataset%20of%20hands%20playing%20the%20piano.pdf">read more</a>
- 10/05/2023: I have found the way build experiment environment. <a href="https://github.com/PSLeon24/Research_AI/blob/main/Build%20a%20dataset%20of%20hands%20playing%20the%20piano/docs/2023_10_04_Build%20a%20dataset%20of%20hands%20playing%20the%20piano.pdf">read more</a>
- 10/11/2023: I have found related papers. <a href="https://github.com/PSLeon24/Research_AI/blob/main/Build%20a%20dataset%20of%20hands%20playing%20the%20piano/docs/2023_10_12_Hand%20landmarks%20dataset.pdf">read more</a>
- 10/16/2023: I proposed data collection environment and data preprocessing method. <a href="https://github.com/PSLeon24/Research_AI/blob/main/Build%20a%20dataset%20of%20hands%20playing%20the%20piano/docs/2023_10_16_Piano%20Performance%20Database.pdf">read more</a>
