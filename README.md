# final
깃허브에 올린 코드 말고 e class에 제출한 코드로 채점해주시면 감사하겠습니다.
2022.12.16
학번 : 20223933, 이름 : 한재호.
저는 서포트 벡터 머신을 이용해서 코드를 작성해 보았습니다.
서포트 벡터 머신의 기본형이 가장 정확도가 잘 나왔기 때문에 이 모델을 선택하게 되었습니다.
처음에는 과대적합 된 것이라고 생각해서 C와 gamma 값을 낮추어야 겠다고 생각했었습니다.
하지만 인터넷에서 뇌종양 데이터를 다운받아서 제가 만든 모델을 테스트 해 보았을 때, 파라미터들의 값을 올려야 정확도가 올라간다는 것을 알게 되었습니다.
따라서 C와 gamma를 기본값보다 상향조정하여서 코드를 작성하게 되었습니다.
