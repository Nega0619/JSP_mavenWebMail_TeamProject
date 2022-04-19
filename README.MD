###### 레포지토리 구조

- 1_REPORT
  - 프로젝트 계획서
  - 발표 PPT
  - 프로젝트 결과 보고서
  - 발표 동영상 URL 링크
- 2_MEETING
  - 1주차-8주차까지의 회의록
- 3_PROJECT
  - 실제 프로젝트의 소스코드
  - 소나큐브 분석을 위한 Property파일
- 4_TOOLS
  - 계획 단계에서 분석한 기존 프로젝트 오류 리스트
  - 요구사항 목록, 유스케이스, 시스템 테스트케이스 작성파일

-----

###### 목차

1. 프로젝트 개요
3. 담당 역할
4. 추후 개선할 점
5. 프로젝트 결과
5. 레포지토리 구조

---
<br>

# 프로젝트 개요

JSP를 이용하여 제공된 웹 메일 시스템 프로젝트에 대해 유지보수를 진행하였습니다.

- 오류를 수정하는 **교정 유지 보수**
- 다양한 환경에 적응하여 작동하는 **적응유지보수**
- 새로운 기능 추가 및 변경을 위한 **완전화유지보수** 
- 프로젝트의 높은 품질, 버그의 방지를 위한 방법을 찾는 **예방유지보수**

위 유지보수를 통하여 사용자에게 이전보다 개선된 품질의 시스템 을 제공하는 것을 목표로 하였습니다.



<br>

### Tools & languages

https://velog.io/@cha-suyeon/github-%EA%B9%83%ED%97%88%EB%B8%8C-%EB%A6%AC%EB%93%9C%EB%AF%B8%EC%97%90%EC%84%9C-%EB%B1%83%EC%A7%80-%EB%A7%8C%EB%93%A4%EA%B8%B0

- Apache NetBeans IDE

- Apache Tomcat

- STMP

- POP

- MySQL

- JSP

- HTML

- CSS






<br>

# 기존 프로젝트



## 전체 유스케이스


![image](https://user-images.githubusercontent.com/80737049/163927818-9928c6a1-bfbb-4f24-aa6e-751db360f0d4.png)



## 요구사항 목록

![](https://user-images.githubusercontent.com/80737049/163902703-b620899d-a23a-48e1-bfb7-b99eb1b13a3d.png)

<br>

# 본 프로젝트



### 유지보수 계획

1. Sonar Qube를 이용하여 Bug와 Code Smell들을 처리해 주었다.

2. 요구사항을 아래와 같이 새롭게 수정하였다.

![image](https://user-images.githubusercontent.com/80737049/163927776-09bbef8c-4c13-463f-a43f-317ad6e90ce5.png)
![image](https://user-images.githubusercontent.com/80737049/163927758-60d93c37-4cb7-4bf4-a65c-32a82134c33f.png)
![image](https://user-images.githubusercontent.com/80737049/163927748-16edb11f-c144-4982-957e-d10e72b8adf8.png)
![image](https://user-images.githubusercontent.com/80737049/163927726-92bd3bf3-9e32-43c7-b46a-966e9a21b2bd.png)



## 유지 보수 프로세스

스크럼 개발 프로세스를 적용하여 유지보수를 진행하였습니다.

제품 기능 목록 작성 –> 스프린트 계획 회의 –> 스프린트 수행 -> 완료로 진행되며, 스프린트 완료 후 스프린트 검토 회의, 회고, 다음 스프린트 계획 회의를 진행하였습니다.

![image](https://user-images.githubusercontent.com/80737049/163927799-3cc56421-bc3b-445a-bd60-bcb4d4d5fd3e.png)



# 담당역할



### 팀장



### 메일 북마크 기능
북마크 메일 추가, 삭제, 취소, 불러오기 별로 유스케이스를 작성하였습니다.
본문분석, 시스템 순차 다이어그램, 도메인 모델을 작성 한 후, 시스템 오퍼레이션을 정의하고 통신다이어그램을 그린 후, 설계 클래스 다이어그램을 작성하였습니다.

구현 완료 후에는 각각의 기능별로 테스트 시나리오를 작성한 후, 테스팅 결과 테이블을 작성하였습니다.

README에는 일부만 가져 왔으며, 1_REPORT 폴더의 결과보고서에서 자세한 사항을 확인하실 수 있습니다.

## 추가

### 유스케이스
![image](https://user-images.githubusercontent.com/80737049/163948632-638a6203-35ab-48aa-b777-c0b2683aaa93.png)


### 시스템 순차 다이어그램
![image](https://user-images.githubusercontent.com/80737049/163946057-2ae87d6c-7edb-4573-82f4-16f239a8336a.png)

### 통신 다이어그램
![image](https://user-images.githubusercontent.com/80737049/163946122-ce17f1d4-98c5-4f52-91a2-65bad86d90c3.png)


### 스팸 메일 기능



스팸 메일 추가, 삭제, 취소 별로 유스케이스를 작성하였습니다.
본문분석, 시스템 순차 다이어그램, 도메인 모델을 작성 한 후, 시스템 오퍼레이션을 정의하고 통신다이어그램을 그린 후, 설계 클래스 다이어그램을 작성하였습니다.

구현 완료 후에는 각각의 기능별로 테스트 시나리오를 작성한 후, 테스팅 결과 테이블을 작성하였습니다.

README에는 일부만 가져 왔으며, 1_REPORT 폴더의 결과보고서에서 자세한 사항을 확인하실 수 있습니다.


# 프로젝트 결과

### 프로젝트 관리
![image](https://user-images.githubusercontent.com/80737049/163942911-1b992607-85a9-412a-8cf1-2ab25364607b.png)





# 발표 동영상
12분의 발표시간이 있어 (신휘정, Nega0619) 빠르게 말합니다. 양해부탁드립니다.
[![발표동영상](https://youtu.be/Mq76OWryDzc)






