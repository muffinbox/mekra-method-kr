# Versions

upstream OKF의 변화를 추적하고 이 저장소의 원칙·pattern·profile에 미치는 영향을 기록합니다.

- [`current.md`](current.md): 현재 권장 기준과 확인한 upstream 기준점
- [`migrations/`](migrations/): 버전 간 실제 전환이 필요한 변경

## 새 변경을 반영하는 흐름

1. 공식 `SPEC.md`의 버전과 diff를 확인합니다.
2. 형식 호환성, 의미 변화, 운영 원칙과 template에 미치는 영향을 나눠 평가합니다.
3. 필요한 문서만 갱신하고 기존 프로젝트의 migration 필요 여부를 기록합니다.
4. 새 프로젝트 권장 버전과 기존 프로젝트의 전환 우선순위를 별도로 판단합니다.

버전 번호만으로 호환성을 단정하지 않습니다. 같은 버전 표기 아래 명세가 바뀔 수 있으므로 확인일과 upstream 파일 기준점을 함께 남깁니다.
