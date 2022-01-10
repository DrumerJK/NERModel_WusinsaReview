# 우신사 리뷰 댓글 개체명 인식 모델
# NER Model For WusinsaReview

이 프로젝트는 K-Digital 빅데이터 과정 수강생 7명이 공동으로 작업한 프로젝트입니다.

프로젝트 수행과정에 대한 더욱 세부적인 사항은 .ipynb 파일에서 확인하실 수 있습니다.

### 팀원 소개 

>김준기 <star956733@gmail.com>
> 
>엄성현 <tjdgus510@gmail.com>
> 
>이경진 <kungjin0119@naver.com>
> 
>이상화 <templas332@naver.com>
> 
>임혜림 <eim0801@naver.com>
>
>조민지 <study.minji.study@gmail.com>
> 
>하은겸 <foreverek4th@naver.com>

![슬라이드0001](https://user-images.githubusercontent.com/92901381/148316178-6bf15c96-7308-485e-ae07-86edd53e53f1.jpg)
![슬라이드0004](https://user-images.githubusercontent.com/92901381/148358155-92e43691-de03-4343-9d75-0b05f6d5a334.jpg)
![슬라이드0005](https://user-images.githubusercontent.com/92901381/148316261-acbd6eb7-9e38-488c-8474-541d420dc92d.jpg)
![슬라이드0012](https://user-images.githubusercontent.com/92901381/148316604-f1373eb3-ab0d-4624-9d3c-33249533ce00.jpg)
![슬라이드0016](https://user-images.githubusercontent.com/92901381/148316762-485a2fa0-23f9-4b35-b54c-8c7261d941fb.jpg)
![슬라이드0018](https://user-images.githubusercontent.com/92901381/148316779-575cf49b-2972-4597-92e2-e567b63aec3e.jpg)
![슬라이드0020](https://user-images.githubusercontent.com/92901381/148316805-9366d507-e427-441f-b61a-28fa6b5534e9.jpg)
![슬라이드0023](https://user-images.githubusercontent.com/92901381/148316841-ae786fea-793b-4e78-86b8-022b71fafa6a.jpg)
![슬라이드0028](https://user-images.githubusercontent.com/92901381/148316863-97a3b063-67f1-4b02-8f91-9f86913bdb50.jpg)
![슬라이드0029](https://user-images.githubusercontent.com/92901381/148317326-79172320-c03b-469d-95d5-4ebd6f872777.jpg)
![슬라이드0032](https://user-images.githubusercontent.com/92901381/148316962-9061e40a-0870-43a0-85c3-d924cf24b933.jpg)
![슬라이드0035](https://user-images.githubusercontent.com/92901381/148316989-b90e70e2-5743-4f32-8526-254e70f9d096.jpg)
![슬라이드0037](https://user-images.githubusercontent.com/92901381/148316998-4289d86c-ef6c-42c8-8758-f75ecacf5990.jpg)
![슬라이드0039](https://user-images.githubusercontent.com/92901381/148317005-83dbeb3c-27a7-449d-a0af-e5e7b83bfb58.jpg)


### 개선사항 내용 추가(2022. 01. 10.)
사람이 직접 모든 문장에 태깅을 하는 작업은 데이터 확보나 태그의 일관성 확보에 있어서 상당히 비효율적이었습니다. 

이는 확보할 수 있는 데이터의 절대적인 수를 현저히 감소시켰으며, 사람의 주관이 주입된 태깅은 모델의 정확도가 더 이상 높아지지 못하도록 제한하였습니다.

이에 따라 k평균과 같은 군집화(Clustering) 알고리즘을 적용하는 방안을 추후 모색하고자 합니다.

비지도학습으로 모델링한다면, 태깅 작업에 따른 한계로 발생하는 문제들을 대거 해결할 수 있을 것으로 기대하고 있습니다.
