# 『밑바닥부터 시작하는 딥러닝』

코드 하나하나 numpy로 직접 구현해보고, 몰랐던 내용 기록. 아래 내용은 공식 GitHub 저장소의 README 내용들이다.

---

<img src="http://www.hanbit.co.kr/data/books/B8475831198_l.jpg" width="360">

:red_circle: **[공지]** 종종 실습용 손글씨 데이터셋 다운로드 사이트( http://yann.lecun.com/exdb/mnist/ )가 연결되지 않습니다.
그래서 예제 수행에 필요한 데이터셋 파일을 /dataset/ 디렉터리에 올려뒀습니다.
혹 사이트가 다운되어 데이터를 받을 수 없다면 아래 파일 4개를 각자의 <예제 소스 홈>/dataset/ 디렉터리 밑에 복사해두면 됩니다. ^__^

* [t10k-images-idx3-ubyte.gz](https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/t10k-images-idx3-ubyte.gz)
* [t10k-labels-idx1-ubyte.gz](https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/t10k-labels-idx1-ubyte.gz)
* [train-images-idx3-ubyte.gz](https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/train-images-idx3-ubyte.gz)
* [train-labels-idx1-ubyte.gz](https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/train-labels-idx1-ubyte.gz)

---

## 새소식
:white_check_mark: **2017.04.03** - 책 본문의 수식과 그림 파일들을 모아 공유합니다. 스터디 자료 등을 만드실 때 필요하면 활용하세요.

* [equations_and_figures.zip](https://github.com/WegraLee/deep-learning-from-scratch/blob/master/equations_and_figures.zip?raw=true)

:white_check_mark: **2017.02.26** - 각 챕터 디렉터리에 README.md 파일을 추가했습니다. 각 파일의 '용도', '관련 절', '등장 페이지'를 명기했고, 책에서 각 장의 '도입부', '목차', '이번 장에서 배운 내용'을 발췌해서 책이 없어도 큰 그림을 파악할 수 있도록 했습니다.

차차 파일 안의 소스 코드에도 친절한 설명을 덧붙이도록 하겠습니다.

:white_check_mark: **2017.02.20** - 3쇄가 출간되었습니다. 크고 작은 오류를 잡는 김에 책 전체를 한 번 더 교정했습니다. 그렇다고 다른 책이 된 게 아니니 1, 2쇄를 보신 분은 오탈자 정보만 확인하시면 충분합니다. 살아 있는 책으로 만들기 위해 이번처럼 기회가 올 때마다 지속해서 품질을 업그레이드할 것이니 궁금하거나 설명이 잘 이해되지 않으면 언제든 문의하세요~

## 파일 구성

|폴더 이름 |설명                         |
|:--        |:--                          |
|ch01       |1장에서 사용하는 소스 코드 |
|ch02       |2장에서 사용하는 소스 코드    |
|...        |...                          |
|ch08       |8장에서 사용하는 소스 코드    |
|common     |공통으로 사용하는 소스 코드  |
|dataset    |데이터셋용 소스 코드 |

## 라이선스

이 저장소의 소스 코드는 [MIT 라이선스](http://www.opensource.org/licenses/MIT)를 따릅니다.
비상용뿐 아니라 상용으로도 자유롭게 이용하실 수 있습니다.

## 책의 오류

이 책의 오탈자 등 오류 정보는 아래 페이지에서 확인하실 수 있습니다.

http://www.hanbit.co.kr/store/books/look.php?p_code=B8475831198


## 인공지능/딥러닝 관련 도서 로드맵

[개앞맵시] 스카이넷도 딥러닝부터 : https://www.mindmeister.com/812276967/

## 머신러닝/딥러닝 번역 용어표

이 책을 번역하며 정리한 [용어표](https://docs.google.com/spreadsheets/d/1ccwGiC01X-gs3PPcXPUz67W9rS6l994LD4AL18KF1_0)입니다.
