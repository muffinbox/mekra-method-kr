# okf-lab-kr

OKF의 변화와 실제 활용 방식을 연구하고, 재사용 가능한 운영 지식으로 정리하는 한국어 공개 저장소입니다.

> English version: [muffinbox/okf-lab](https://github.com/muffinbox/okf-lab)

> 예시와 적용 맥락은 특정 개인·조직을 식별하지 않도록 일반화해 서술합니다.

> 이 저장소는 OKF 명세의 복사본이나 모든 프로젝트가 따라야 할 프레임워크가 아닙니다.  
> 공식 형식의 정본은 [GoogleCloudPlatform/open-knowledge-format](https://github.com/GoogleCloudPlatform/open-knowledge-format)입니다.

## 하는 일

- upstream 버전 변화와 마이그레이션 영향을 추적합니다.
- 채택한 운영 원칙, 재사용 가능한 패턴, 사용 방식별 프로필을 구분해 축적합니다.
- 실제 프로젝트에 복사해 조정할 수 있는 최소 템플릿을 제공합니다.
- 아직 검증되지 않은 생각과 실험을 확정된 지침과 분리합니다.

## 구조

| 위치 | 역할 |
| --- | --- |
| [`okf/`](okf/index.md) | OKF에 대한 이해, 운영 철학, 재사용 패턴과 개념 관계 |
| [`profiles/`](profiles/README.md) | 특정 사용 방식에 맞춘 패턴의 조합과 출발점 |
| [`templates/`](templates/README.md) | 프로젝트에 복사한 뒤 문맥에 맞게 고치는 최소 뼈대 |
| [`versions/`](versions/README.md) | 기준 OKF 버전, 영향 분석, 마이그레이션 기록 |
| [`experiments/`](experiments/README.md) | 가설과 검증 중인 방법 |
| [`notes/`](notes/README.md) | 아직 정리되지 않은 관찰과 고찰 |

## 사용하는 법

1. 상황에 가장 가까운 [프로필](profiles/README.md)을 출발점으로 고릅니다.
2. 필요한 [지식과 패턴](okf/index.md)만 선택해 적용합니다.
3. [템플릿](templates/README.md)을 복사하고 실제 저장소의 문맥에 맞게 줄이거나 바꿉니다.
4. 대상 OKF 버전이 다르면 [버전 기록](versions/README.md)과 migration 문서를 확인합니다.
5. 실제 운영에서 얻은 관찰은 notes 또는 experiments에 남기고, 반복해서 유효한 것만 OKF 개념과 profile에 반영합니다.

프로필과 템플릿은 예시이자 기본값입니다. 적합성은 파일 수나 구조 일치 여부가 아니라, 지식이 올바른 맥락에서 이해되고 변경의 영향이 필요한 곳에 반영되는지로 판단합니다.

## 현재 기준

- OKF: **v0.2**
- 확인일: **2026-09-18**
- 상세 기준점: [`versions/current.md`](versions/current.md)
