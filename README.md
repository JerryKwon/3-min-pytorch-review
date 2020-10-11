# 3-min-pytorch-review
<a href="https://www.hanbit.co.kr/store/books/look.php?p_code=B7193109877">김건우, 염상준 - 『펭귄브로의 3분 딥러닝 파이토치 맛』 (한빛미디어, 2019.11)</a>를 공부하여 내용을 정리합니다.

author's github source repo: <a href="https://github.com/keon/3-min-pytorch">click here</a> 



## :dart: ​목적

1. pytorch library에 대한 이해 및 사용법 습득
2. 지난번에 참여한 Dacon의 EMNIST 이미지 분류 대회에서 사용한 pytorch 코드의 개선점 탐색
3.  Kakao Areana Melon Playlist Continuation의 Auto Encoder를 활용한 추천시스템 구현을 위한 이해 



## :clipboard: 목차

1. <a href="https://github.com/JerryKwon/3-min-pytorch-review/blob/master/1.%20%EB%94%A5%EB%9F%AC%EB%8B%9D%EA%B3%BC%20%ED%8C%8C%EC%9D%B4%ED%86%A0%EC%B9%98/1.%20%EB%94%A5%EB%9F%AC%EB%8B%9D%EA%B3%BC%20%ED%8C%8C%EC%9D%B4%ED%86%A0%EC%B9%98.ipynb">딥러닝과 파이토치</a> (9/16)
2. <a href="https://github.com/JerryKwon/3-min-pytorch-review/blob/master/2.%20%ED%8C%8C%EC%9D%B4%ED%86%A0%EC%B9%98%20%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0/2.%20%ED%8C%8C%EC%9D%B4%ED%86%A0%EC%B9%98%20%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0.ipynb">파이토치 시작하기</a> (9/20)
3. <a href="https://github.com/JerryKwon/3-min-pytorch-review/blob/master/3.%20%ED%8C%8C%EC%9D%B4%ED%86%A0%EC%B9%98%EB%A1%9C%20%EA%B5%AC%ED%98%84%ED%95%98%EB%8A%94%20ANN/3.%20%ED%8C%8C%EC%9D%B4%ED%86%A0%EC%B9%98%EB%A1%9C%20%EA%B5%AC%ED%98%84%ED%95%98%EB%8A%94%20ANN.ipynb">파이토치로 구현하는 ANN</a>(9/22)
4. <a href="https://github.com/JerryKwon/3-min-pytorch-review/blob/master/4.%20%ED%8C%A8%EC%85%98%20%EC%95%84%EC%9D%B4%ED%85%9C%EC%9D%84%20%EA%B5%AC%EB%B6%84%ED%95%98%EB%8A%94%20DNN/4.%20%ED%8C%A8%EC%85%98%20%EC%95%84%EC%9D%B4%ED%85%9C%EC%9D%84%20%EA%B5%AC%EB%B6%84%ED%95%98%EB%8A%94%20DNN.ipynb">패션 아이템을 구분하는 DNN</a>(9/23~10/11)
5. <a href="https://github.com/JerryKwon/3-min-pytorch-review/blob/master/5.%20%EC%9D%B4%EB%AF%B8%EC%A7%80%20%EC%B2%98%EB%A6%AC%20%EB%8A%A5%EB%A0%A5%EC%9D%B4%20%ED%83%81%EC%9B%94%ED%95%9C%20CNN/5.%20%EC%9D%B4%EB%AF%B8%EC%A7%80%20%EC%B2%98%EB%A6%AC%20%EB%8A%A5%EB%A0%A5%EC%9D%B4%20%ED%83%81%EC%9B%94%ED%95%9C%20CNN.ipynb">이미지 처리 능력이 탁월한 CNN</a>(10/11)
6. 사람의 지도 없이 학습하는 오토인코더
7. 순차적인 데이터를 처리하는 RNN
8. 딥러닝을 해킹하는 적대적 공격
9. 경쟁하며 학습하는 GAN
10. 주어진 환경과 상호작용하며 학습하는 DQN