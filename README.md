# 2025 CS231n Subtitles

[영상 링크](https://www.youtube.com/watch?v=2fq9wYslV0A&list=PLoROMvodv4rOmsNzYBMe0gJY2XS8AQg16&index=1)

[강의 자료](https://cs231n.stanford.edu/2025/)


CS231n 2025 강의 영상에 사용할 수 있는 자막 파일 모음입니다.  
영어 자막은 `En/`, 한국어 자막은 `ko/` 디렉토리에 들어 있습니다.

## 자막 구성

- `En/`: 영어 원문 자막
- `ko/`: 한국어 번역 자막

현재 포함된 강의:

- Lecture 4 Neural Networks and Backpropagation
- Lecture 5 Image Classification with CNNs
- Lecture 6 CNN Architectures
- Lecture 7 Recurrent Neural Networks
- Lecture 8 Attention and Transformers
- Lecture 9 Object Detection, Image Segmentation, Visualizing and Understanding
- Lecture 10 Video Understanding

일부 강의는 영어 자막만 있거나 한국어 자막만 있을 수 있습니다.

## 영상과 함께 재생하는 방법

가장 편한 방법은 영상 파일과 자막 파일의 이름을 동일하게 맞춘 뒤 같은 폴더에 두는 것입니다.

예를 들어 Lecture 6 영상을 재생하려면 다음처럼 파일명을 맞춥니다.

```text
Lecture 6 CNN Architectures.mp4
Lecture 6 CNN Architectures.srt
```

그 다음 동영상 플레이어에서 `Lecture 6 CNN Architectures.mp4`를 열면, 대부분의 플레이어가 같은 이름의 `.srt` 자막을 자동으로 불러옵니다.

## VLC에서 사용하기

1. VLC에서 강의 영상을 엽니다.
2. 상단 메뉴에서 `Subtitle` > `Add Subtitle File...`을 선택합니다.
3. 사용할 `.srt` 파일을 선택합니다.

한국어 자막을 보려면 `ko/` 폴더의 자막을, 영어 자막을 보려면 `En/` 폴더의 자막을 선택하면 됩니다.

## mpv에서 사용하기

터미널에서 다음처럼 실행할 수 있습니다.

```bash
mpv "Lecture 6 CNN Architectures.mp4" --sub-file="ko/Lecture 6 CNN Architectures.srt"
```

영어 자막을 사용하려면 `ko/` 대신 `En/` 경로의 자막 파일을 지정하면 됩니다.

## 웹 플레이어 또는 강의 플랫폼에서 사용하기

일부 웹 플레이어는 외부 자막 업로드를 지원합니다. 영상 재생 화면에서 `CC`, `Subtitle`, `Caption`, `자막 업로드` 같은 메뉴를 찾은 뒤 `.srt` 파일을 선택하면 됩니다.

업로드할 때는 영상 강의 번호와 자막 파일명이 같은지 확인하는 것이 좋습니다.

## 자막 싱크가 맞지 않을 때

영상 출처나 편집본에 따라 자막 시간이 조금 어긋날 수 있습니다. 이 경우 다음 방법을 시도해 보세요.

- VLC: `G` / `H` 키로 자막 싱크를 앞뒤로 조정
- mpv: `z` / `x` 키로 자막 싱크 조정
- 자막 편집기: Subtitle Edit, Aegisub 등으로 `.srt` 시간 수정

## 권장 사용 방식

강의별로 영상과 자막을 같은 폴더에 두고, 원하는 언어의 자막 파일만 영상 파일명과 동일하게 맞춰 사용하는 방식을 추천합니다.

```text
videos/
  Lecture 8 Attention and Transformers.mp4
  Lecture 8 Attention and Transformers.srt
```

한국어와 영어 자막을 모두 보관하고 싶다면 다음처럼 언어 표시를 붙여 둘 수도 있습니다.

```text
Lecture 8 Attention and Transformers.mp4
Lecture 8 Attention and Transformers.ko.srt
Lecture 8 Attention and Transformers.en.srt
```

이 경우 자동 로드가 되지 않는 플레이어에서는 자막 파일을 직접 선택해서 불러오면 됩니다.
