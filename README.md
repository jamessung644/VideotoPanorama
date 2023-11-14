# VideotoPanorama

## Video File을 Panorama Image로 변환하기

`VideotoPanorama`는 비디오 파일을 파노라마 이미지로 변환해주는 도구입니다. 이 프로젝트를 사용하여 동영상의 각 프레임을 이어 붙여 하나의 넓은 파노라마 이미지를 생성할 수 있습니다.

### 설치 방법

이 도구를 사용하기 위해서는 Python 환경에 OpenCV와 Numpy를 설치해야 합니다. 아래의 명령어로 필요한 라이브러리를 설치할 수 있습니다.

```bash
pip install opencv-python numpy
```

Homography Matrix
VideotoPanorama는 Homography Matrix의 개념을 사용하여 이미지 변환을 수행합니다. 
Homography Matrix는 한 이미지에서 다른 이미지로의 투영 변환을 나타내는 행렬입니다.
이를 통해 비디오의 각 프레임을 하나의 이미지로 결합하는 과정에서 정확한 위치 조정과 변환을 수행할 수 있습니다.

Homography Matrix 행렬 공식

<img width="500" alt="스크린샷 2023-11-14 오후 7 20 28" src="https://github.com/jamessung644/VideotoPanorama/assets/39661528/6c9cc77a-ae2a-475b-ab91-26caf8bad93b">



