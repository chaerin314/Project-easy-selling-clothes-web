## Code Description
### 📌 category_classification.ipynb
옷의 종류를 분류하는 AI  
- code : data preprocessing, model training, inference
- train input : (35518, 100, 100, 3)
- inference input : (1, 100, 100, 3) (배치 단위로 입력하게 코드 변경도 가능)
- inference output : (1, 4)
    - label  
    0: 아우터  
    1: 하의   
    2: 원피스  
    3: 상의  

### 📌 style_classification.ipynb
옷의 스타일을 분류하는 AI  
- code : data preprocessing, model training, inference
- train input : (35518, 100, 100, 3)
- inference input : (1, 100, 100, 3) (배치 단위로 입력하게 코드 변경도 가능)
- inference output : (1, 9)
    - label  
    0: 레트로  
    1: 로맨틱   
    2: 매니시  
    3: 모던  
    4: 밀리터리  
    5: 섹시  
    6: 스포티  
    7: 페미닌  
    8: 프레피  

### 📌 initial_code.ipynb
여러가지 시도 및 아이디어 code

<br></br>

## Improvement
- 각 이미지 사이즈에 맞춰 전처리하기(현재는 메모리부족)
- 더 많은 데이터로 학습
- 커스텀 모델 만들기
- hyperparameter 조정
