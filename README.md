목장 CCTV 영상에서 소를 식별하기 위한 이미지 데이터 만들기 
==============================================
팀명: MCMC
--------------------------------------

목적: yolact 기반으로 추적기 달고 배경 지워서
소 식별 데이터를 빠르게 만들기

왜 : 그런걸 만드느냐?
소 무늬를 통해 ai로 식별 가능하다는 논문은 많은데 
정작 산업에 적용하려고 보니 데이터가 없는 문제가 있습니다. 
논문에서는 Yolo를 통해 이미지를 한마리 한마리 모았는데
어느 세월에 그렇게 다 모으고 있나 싶어
추적기 달고 전처리를 위해 배경도 지우게 만들었습니다. 

왜2 : 소 식별해서 무었하나?
목장가서 1시간만 일하면 알게됩니다. 

+ 추적기 달기

![output_image](./output_image.png)

+ 배경 지우기

![cow_id_1_num_0](./cow_id_1_num_0.png)


--------------------------------------
- 정리 하는 일은 자소서 다쓰고 NCS 준비하는 중에 조금씩 업로드 합니다. 
- 이거 하다가 제 GPU에서 딱딱 소리가 나더니 고장났습니다. 
- 서류 마감이 9월 5일까지이고 공기업에서는 깃허브 안보는데 전 이걸 왜했을까요?
