# hw02 재활용품 분류기 (개인 과제)

직접 찍은 캔 / 종이팩 / 페트병 사진으로 3클래스 분류기를 만든다.
ImageNet 사전학습 ResNet-18의 특성 추출부를 동결하고 `fc`를 출력 3개로 바꿔 학습한다.

- 과제 안내: https://ralbu85.github.io/lecture_deeplearning/assignments/hw02/hw02.html
- 원본 노트북: https://github.com/ralbu85/lecture_deeplearning_labs/blob/main/hw02.ipynb

## 체크리스트
- [ ] 사진 촬영 (장소·거리·각도 다양하게, 클래스별 비슷한 장수)
- [ ] 구글 드라이브 `내 드라이브/hw02/{can,carton,pet}` 에 업로드
- [ ] Colab에서 Drive에 사본 저장, 런타임 T4 GPU
- [ ] 학번·이름 입력, 빈칸(증강, 데이터 로더, 모델, 학습) 채우기
- [ ] 런타임 재시작 후 전체 실행
- [ ] 8절 테스트 정확도 확인 (하루 5번)
- [ ] '제출 전 확인' 셀 통과 → 가중치, 사진 zip, 노트북 제출

## 주의
- 파일 이름·노트북 변수 이름 변경 금지
- 본인이 찍은 사진만 사용, 타인 가중치 사용·가중치 수정 금지
- 사진과 가중치는 `.gitignore`로 저장소에서 제외
