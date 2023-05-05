# Alzip Project Portfolio

## Youtube
[프로젝트 아키텍쳐 및 허프만 알고리즘 소개 (약 7분)](https://www.youtube.com/watch?v=Jz10hZ6JuMo&)

[LZ77 알고리즘 소개 및 시간복잡도 분석 (약 9분)](https://www.youtube.com/watch?v=woR0gj9tdQc)

[압축 프로그램 시연 (약 4분)](https://www.youtube.com/watch?v=XePezKhsy8M)

## 개요

### 선정 동기

2학년 1학기때 배운 자료구조 및 알고리즘을 실습해볼수 있고 파일입출력을 잘 다뤄보고 싶어서 압축 프로젝트를 선정하게 되었습니다

### 프로젝트 기간

2021.09.20 ~ 2021.12.20 (약 3개월, 2학기 팀 프로젝트)

### 사용 기술 스택

Java, JavaGUI, Jave Build(Maven), Huffman Encoding, LZ77 Encoding


### 프로젝트 역할

저는 팀장을 맡아서 프로젝트를 진행하였습니다. 요구사항 작성, 일정 관리, 코드의 전체적인 설계, 빌드 및 배포 관리등을 맡았습니다

## 목표

### 문제 정의

#### 1. 압축의 생소함

자료구조 수업에서 허프만 압축에 대해 간단하게 다뤄주시긴 하지만 압축이라는 기능의 경우 일반적으로 프로젝트 주제로 잘 선택되는 주제는 아니다보니 팀원 모두가 압축 알고리즘을 어떻게 구현할지 생소함이 있었습니다

#### 2. GUI 프로그래밍의 어려움

저희는 GUI를 위한 언어로 Java 및 Swing을 선택했는데 요즘엔 웹이나 안드로이드쪽이 유행하고 상대적으로 GUI 프로젝트는 적다보니 GUI를 다루기위한 Api 자체도 팀원들이 많이 생소해 하였습니다

#### 3. 프로젝트 설계

1, 2번과 맞물려 압축이라는 기능 구현도 생소하고 GUI구현도 생소하기때문에 코드 구조를 어떻게 가져가야할지 팀원들이 많이 난감해 했었습니다 

턴제 게임이다 보니 상호작용은 UI 위주로 일어나기 때문에 **UI를 얼마나 효과적으로 빠르게 구현할 수 있는지**가 중점이였던것 같습니다 그 외에는 턴제 게임의 규칙을 만들기 위해 **상태머신을
잘 설계**하는것이 중요하였습니다 전반적인 작업 내용은 UI가 6~7할 상태머신 설계가 2할 나머지 1할정도의 작업이 되었습니다

### 문제점

C++은 C#의 이벤트나 Javascript의 이벤트 핸들러와 같은 기능들을 통해 이벤트 프로그래밍을 적극적으로 지원하는 언어는 아니였어서 UI를 동작시킬떄 어려움을 겪었습니다 처음엔 버튼 하나하나
마다 직접 클래스를 만들어서 작업을 처리하도록 작성했었는데 이렇게 만들다보니 사실상 이벤트 처리 빼고는 나머지는 다 중복되는 코드였기 때문에 코드의 크기가 쓸데없이 커진다는 문제점이
있었습니다



