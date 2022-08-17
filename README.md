`최근 업데이트 : '22. 08. 17.`  
</br>
![image](https://user-images.githubusercontent.com/86638578/184792479-0f54fc56-0463-4ba0-b43d-3e6184a3d8c8.png)  
</br>

## 개요
#### ✔ 더 나은 사용자 경험을 위해, 안드로이드 어플리케이션의 성능을 개선해 나갑니다.
#### ✔ Clean Architecture, JetPack 라이브러리를 학습하고 있으며, 지속적으로 업데이트 될 예정입니다.
#### ✔ 오류 및 보완해야할 내용은 Contribution을 통해 기여부탁드리겠습니다🙇‍♂️
</br>

## 목차
### Jetpack
#### 1. Architecture
#### 2. UI
#### 3. Foundation
#### 4. Behavior

### Android Clean Architecture

### Q&A
#### Android Support Library?
#### Jetpack vs AndroidX?
</br>

## Jetpack
![image](https://user-images.githubusercontent.com/86638578/184792585-a238e4e4-d1a0-44d7-8272-39896310c2c2.png)
#### Jetpack은 5월 8일 Google I/O 2018에서 처음 발표되었습니다.
#### 이를 통해, 안드로이드는 어플리케이션의 품질을 높일 수 있는 지침, 권장 라이브러리, 도구 모음을 제공합니다.
- AndroidX 라이브러리가 포함되거나 포함되지 않을 수 있습니다.(현재는 AndroidX로 구성되어 있음)
- 일부 기능의 지침이 변경되거나 발전되었을 경우, Jetpack 권장 사항에 포함되지 않을 수 있습니다.
- AAC - Room [`repo`](https://github.com/woongcheol/Android-Clean-Architecture-Room)
- AAC - DataBinding [`repo`](https://github.com/woongcheol/Android-Clean-Architecture-DataBinding)
- AAC - LiveData [`repo`](https://github.com/woongcheol/Android-Clean-Architecture-LiveData)
- Architecture Pattern - MVVM [`repo`](https://github.com/woongcheol/Android-Clean-Architecture-MVVM)
- Design Pattern
  </br>

## Android Clean Architecture
![image](https://user-images.githubusercontent.com/86638578/184793261-dca999cd-08ad-4b32-babf-dd412c3b0698.png)
[이미지 출처](https://github.com/falsy/react-with-clean-architecture)
- 작성 예정  
  </br>

## Q&A
#### 기존의 Android Support Library는 왜 안쓰나요?
- Android Support Library는 Android Framework에서 제공하지 않는 기능들을 제공하는 라이브러리입니다.
- 구글에서 별도로 제공하며 개발자는 버전의 하위 호환성, 다양한 사용자 인터페이스, 유용한 유틸리티를 위해 사용합니다.
- 하지만 `모호한 버전 규칙`, `스마트폰 스펙 상향`, `단일 라이브러리 제공`, `바이너리의 호환성 제약`의 문제점이 있었고 이를 개선한 AndroidX가 등장했습니다.

#### Jetpack에도 AndroidX, AndroidX에도 Jetpack. 둘 차이는 무엇인가요?
- Jetpack은 라이브러리, 도구 등 권장되는 사항들의 모음집이고, AndroidX는 Jetpack이 추구하는 가이드라인을 실체화한 라이브러리입니다.
- AndroidX는 Jetpack에 구성되는 라이브러리를 개발, 테스트, 패키지화, 버전 및 릴리즈하기 위해 사용합니다.
- AndroidX는 Android Support Library(com.android.support.*)를 개선하여 통합한 것입니다.
- Android Support Library는 현재에도 제공되지만, 신규 라이브러리는 AndroidX에서 개발되고 있습니다.  
  </br>

+) AndroidX의 Release stage
![image](https://user-images.githubusercontent.com/86638578/185006356-68cb712c-5372-4aa2-8028-52d8312a46d2.png)
</br>

+) 버그 발견 시 [이슈 트래커](https://issuetracker.google.com/issues)에 등록