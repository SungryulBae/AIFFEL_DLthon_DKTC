# AIFFEL_DLthon_DKTC

## 과제 설명
- [2021 인공지능 그랜드 챌린지](https://www.ai-challenge.kr/) 대회에 참가하기 위해 [TUNiB](http://tunib.ai/)이 자체적으로 제작한 데이터셋을 활용하여 해당 데이터셋을 잘 분류할 수 있는 방법을 찾는 것, 그리고 분류 성능을 높이는 것을 목표로 함

- DLthon 은 다음 페이지에서 진행됩니다!  
[Aiffel Online 17th DLThon Competition](https://www.kaggle.com/t/cd4bea45c52646bbbaebe7b31f01f20c)

## 폴더 구조

```
.
├── data/                   # 원본 데이터 및 전처리된 데이터
│   ├── raw/                # 제공된 원본 csv (수정 및 파일 추가 X)
│   │   ├── train.csv       # train 용 원본 csv
│   │   ├── test.csv        # test  용 원본 csv
│   │   └── submission.csv  # Kaggle 제출 양식 csv
│   ├── team_data/          # 프롬프트로 직접 생성한 일상 대화 데이터 등록
│   ├── processed/          # [sep] 치환 등 전처리가 완료된 csv
│   ├── image/              # 기타 이미지 데이터
│   └── final/              # submission 으로 제출할 csv
├── notebooks/              # 실행 코드
├── src/                    # 재사용 가능한 모듈 
├── requirements/           # conda 가상 환경 설정 (YAML)
├── experiments/            # 실험 설정값 관리 (YAML 또는 JSON)
└── README.md               # 프로젝트 설명

```