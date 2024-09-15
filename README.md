# object_detection
1.프로젝트 개요

-casccade classifier 라이브러리를 활용하여 고속도로 차량주행 영상에서 객체감지 프로젝트입니다.

-code1 은 tracker를 사용했고, code2 는 tracker 버전 호환성문제로 일부 수정한 코드입니다. 

-개인 프로젝트 입니다.

-객체감지, 영상 저장 코드작업을 했습니다.

2.활용한 기술

python

3.프로젝트 진행단계
1) 샘플 영상 수집
2) 객체 감지 코드 작성
3) 영상 읽기 및 저장 코드 작성

4.프로젝트 결과

지나가는 모든 차량을 인식하고 바운딩 박스로 표시가능합니다.

샘플 영상 : 

https://github.com/user-attachments/assets/03949103-bdaa-4206-a60a-e6f783327b4d

good :

![image](https://github.com/user-attachments/assets/6ebd4e69-fd7d-4e95-9e48-111dfcf5bf1c)

bad:

![image](https://github.com/user-attachments/assets/7efc025e-dd12-4500-a8db-f8bfdd16e520)


5.프로젝트 회고

1)잘한 점

간단한 코드로 객체인식 성능이 좋은 코드를 구현했습니다.

2)개선 방안

-차량 그림자가 차량과 같이 인식되는 문제가 있습니다.

-바운딩 박스 세부조건 변경 혹은 더 나은 객체탐지 라이브러리를 활용해서 코드를 발전시키면 좋을 것 같습니다.
