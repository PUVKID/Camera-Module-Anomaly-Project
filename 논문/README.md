<!-- language-choice:start -->
🔵 **한국어** · [English overview](../en/README.md)
<!-- language-choice:end -->

<a id="-논문"></a>

# 논문

<!-- reading-levels17:start -->
<details>
<summary>읽기 수준 선택</summary>

| 레벨 | 읽는 목적 |
| --- | --- |
| [LEVEL 1 - Beginner](../docs/%EC%9D%BD%EA%B8%B0%EC%95%88%EB%82%B4/%EB%A0%88%EB%B2%A81.md) | 목적과 입력·출력을 쉬운 말로 이해하기 |
| [LEVEL 2 - Explorer](../docs/%EC%9D%BD%EA%B8%B0%EC%95%88%EB%82%B4/%EB%A0%88%EB%B2%A82.md) | 주요 기능과 전체 처리 흐름 살펴보기 |
| [LEVEL 3 - Practitioner](../docs/%EC%9D%BD%EA%B8%B0%EC%95%88%EB%82%B4/%EB%A0%88%EB%B2%A83.md) | 설정·실행 순서와 결과 확인하기 |
| [LEVEL 4 - Advanced](../docs/%EC%9D%BD%EA%B8%B0%EC%95%88%EB%82%B4/%EB%A0%88%EB%B2%A84.md) | 구현 선택과 조건·한계 비교하기 |
| [LEVEL 5 - Expert](../docs/%EC%9D%BD%EA%B8%B0%EC%95%88%EB%82%B4/%EB%A0%88%EB%B2%A85.md) | 세부 근거와 재현 조건 검토하기 |

</details>
<!-- reading-levels17:end -->

스마트 장치의 카메라 모듈 영상을 정상·불량으로 분류할 때 YOLOv8·Vision Transformer·자체 CNN의 성능과 처리 비용을 비교한 7 쪽 연구 원고입니다.

| 주요 구성 | 내용 |
| --- | --- |
| <a id="layout18-table-1-row-1"></a> 정상·불량 데이터 구성 | OK/NG 영상을 학습 80%·검증 20%로 분할하는 실험을 설명합니다. |
| <a id="layout18-table-1-row-2"></a> YOLOv8 분류 | 원고의 학습 호출은 imgsz64·batch32·최대 3000epoch·patience100을 사용합니다. |
| <a id="layout18-table-1-row-3"></a> ViT와 CNN 비교 | 사전 학습 ViT와 합성곱·풀링·완전 연결층 CNN을 분류 지표로 비교합니다. |
| <a id="layout18-table-1-row-4"></a> 성능과 비용 해석 | 정확도·정밀도·재현율·F1과 처리 시간·모델 크기를 함께 제시합니다. |


<a id="-이용-순서"></a>

## 이용 순서

1. 초록과 데이터 구성에서 정상·불량 분류 문제와 분할을 확인합니다.
2. 모델별 구현 설명을 읽으며 입력 크기와 학습 조건을 나란히 기록합니다.
3. 5 쪽 결과 표와 그래프, 6 쪽 결론의 수치를 대조합니다.
4. 같은 조건의 외부 시험인지, 원고 내부 검증인지 구분한 뒤 결과를 인용합니다.

| 차수·단계 | 주요 내용 | 자료 | 직전 비교 |
| --- | --- | --- | --- |
| <a id="layout18-table-2-row-1"></a> [최종 원고](../docs/versions/final-paper.md) | 스마트 장치의 카메라 모듈 영상을 정상·불량으로 분류할 때 YOLOv8·Vision Transformer·자체 CNN의 성능과 처리 비용을 비교한 7 쪽 연구 원고입니다. | [폴더](.) | [전체 비교](../docs/VERSIONS.md) |


[프로젝트](../README.md) · [전체 차수](../docs/REVISION_INDEX.md)
