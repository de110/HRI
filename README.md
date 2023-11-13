# HRI
'휴먼로봇인터페이스' 강의 과제 저장소
<br/><br/>


#### 프런트 패널 구성 : 7음계(도, 레, 미, 파, 솔, 라, 시)의 피아노 건반 UI

<img width="250" alt="image" src="https://github.com/de110/HRI/assets/67581448/266ff852-1f40-43a7-8975-6074ea18a4f3">
<br/><br/>

<img width="100" alt="image" src="https://github.com/de110/HRI/assets/67581448/f7e8496c-31cc-4676-a50a-dc4240786a5d">

- Classic Boolean의 Flat Square Button을 사용하여 각 건반을 구성
<br/><br/>

<img width="90" alt="image" src="https://github.com/de110/HRI/assets/67581448/a4e14881-e275-44d9-b738-7b9976b3d50b">

- Cluster를 사용하여 전체 건반을 묶음
<br/><br/>
#### 블록 다이어그램 구성 :  피아노 작동 기능 구현

<img width="279" alt="image" src="https://github.com/de110/HRI/assets/67581448/8d30fc60-5565-45ae-b3f0-3e63c570b010">
<br/><br/>

1. Cluster 형의 피아노 건반 Boolean 데이터를 가져온다.
2. While 문 내에 위치한 event case의 조건을 통과한다.
<br/>   2.1 각 피아노 건반이 눌려서 Boolean 값이 바뀌게 될 경우, event case 내에 있는 함수를 작동 시킨다.
3. Event case 조건과 일치할 시, 각 건반의 음계에 맞는
     주파수 음역을 0.5 s 시간 동안 반환한다.
4. 건반 소리가 출력된다.


