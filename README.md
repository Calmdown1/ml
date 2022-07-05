# Github_StayCalmDown

---

- **파일 다운로드 방법**

```powershell
git clone https://github.com/StayCalmdown/ml.git
```

- **ml 폴더로 이동**

```powershell
cd /
cd apps 
cd ml
```

- **jupyter notebook을 활용하여 사용**

```powershell
jupyter notebook
```

- [DecisionTree.ipynb](https://github.com/StayCalmdown/ml/blob/b16f1f398fd504becf0df787933012852bb4b205/DecisionTree.ipynb) - 의사결정나무 예제
- [앙상블.ipynb](https://github.com/StayCalmdown/ml/blob/b16f1f398fd504becf0df787933012852bb4b205/%EC%95%99%EC%83%81%EB%B8%94.ipynb) - 앙상블 부스팅 관련 예제

테스트 스플릿을 라이브러리에서 가져오고 

원본 사이트에 의하면 얘네는 array를 필요로 하기에

data(features)와 label 레이블 값을 넣어줘야 함

**`test_size`** 는 인풋 데이터의 0.2를 테스트 데이터로 사용한다는 것

`**random_state**`는 학습데이터와 테스트데이터를 각 해당 데이터로 고정불변하게 하는 것

따라서 시드를 배정하는 것임


![image](https://user-images.githubusercontent.com/105197372/177272737-9cab0c17-907f-4303-89bf-1d8d55dbcc33.png)