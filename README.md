# MachineVision

### 1. CameraCalibration_SimpleAR

- 실제 물체와 여러 각도의 사진들을 이용해서 Camera Calibration을 계산함
- 계산한 Camera Calibration을 이용해서 간단한 AR 구현 


_예시)_
<div display="column">
<img height="200" alt="스크린샷 2022-03-19 오후 1 38 58" src="https://user-images.githubusercontent.com/50614113/159107057-386fb373-27d5-432f-8734-3dc2f3187c4b.png">

<img height="200" alt="스크린샷 2022-03-19 오후 1 34 01" src="https://user-images.githubusercontent.com/50614113/159106902-4ac140a7-b31e-4f82-a51b-0b7bda79a9a3.png">
</div>




### 2. ImageFiltering

- Average Filtering
- Image Sharpening
- Gaussian Filtering
- Median Filtering (salt and pepper noise 추가)

_예시)_
<div display="column">
<img height="200" alt="스크린샷 2022-03-19 오후 1 38 58" src="https://user-images.githubusercontent.com/50614113/161310357-e76fa957-94ca-41a1-b7bd-15110cdca986.png">
<img height="200" alt="스크린샷 2022-03-19 오후 1 38 58" src="https://user-images.githubusercontent.com/50614113/217177519-65272395-117c-459b-b021-80e34bc340bc.png">
</div>



### 3. RANSAC_Linefitting
- Line and Curve Fitting

_예시) 차선 검출_
<div display="column">
<img height="200" alt="스크린샷 2022-03-19 오후 1 38 58" src="https://user-images.githubusercontent.com/50614113/217181820-3ae2117f-f02c-41b1-a9ae-53bb3dd4ef31.png">
<img height="200" alt="스크린샷 2022-03-19 오후 1 38 58" src="https://user-images.githubusercontent.com/50614113/217181878-27e80321-0986-4cb6-8349-294f670a0635.png">
<img height="200" alt="스크린샷 2022-03-19 오후 1 38 58" src="https://user-images.githubusercontent.com/50614113/217181910-969affd6-0151-4304-b859-6974a704711b.png">
</div>


### 4. ImageStitching
- Corners and Blobs Detection
- 찾은 local image data 로 match

_예시)_
<div display="column">
<img height="200" alt="스크린샷 2022-03-19 오후 1 38 58" src="https://user-images.githubusercontent.com/50614113/217183889-91edc27d-4923-4e48-95ac-cbf5de70559c.png">
<img height="200" alt="스크린샷 2022-03-19 오후 1 38 58" src="https://user-images.githubusercontent.com/50614113/217183980-0add646c-ff92-4e70-8618-3d3f6b9596ac.png">
<img height="200" alt="스크린샷 2022-03-19 오후 1 38 58" src="https://user-images.githubusercontent.com/50614113/217184301-f79dd5b2-67df-49fe-beec-66c91a8de0c8.png">
</div>
<img height="200" alt="스크린샷 2022-03-19 오후 1 38 58" src="https://user-images.githubusercontent.com/50614113/217185125-7f1776eb-ddde-49e0-adb7-9fb6c4bfe5b7.png">


### 5. Homography
- Homography로 파노라마 구현


_예시)_
<div display="column">
<img height="200" alt="스크린샷 2022-03-19 오후 1 38 58" src="https://user-images.githubusercontent.com/50614113/217186277-179f7d14-f623-4b73-9016-be9f6b6b408a.png">
<img height="200" alt="스크린샷 2022-03-19 오후 1 38 58" src="https://user-images.githubusercontent.com/50614113/217186387-a4f4ff3e-d858-4f25-8755-da72ca50e25c.png">
</div>

<img height="200" alt="스크린샷 2022-03-19 오후 1 38 58" src="https://user-images.githubusercontent.com/50614113/217186687-f1957fbc-7ba3-4e16-a3c0-fa421523cb75.png">

### 6. Image_Classification
- 이미지 분류

### 7. Object_detection
- 이미지 검출
