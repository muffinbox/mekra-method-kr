# Profiles

profile은 특정 사용 방식에서 여러 pattern을 조합한 출발점입니다. 상황에 따라 불필요한 부분을 줄이거나 필요한 구조를 확장하고, 여러 profile의 pattern을 함께 조합할 수 있습니다. 디렉터리 이름과 예시 구조도 문맥에 맞게 바꿀 수 있으며, profile 일치 여부가 OKF 적합성을 결정하지 않습니다.

profile은 하나의 상호배타적 분류 체계를 이루지 않으며, 하나의 저장소에 여러 profile을 함께 적용할 수 있습니다. 이 판단의 근거는 [프로필의 조합과 경계](../okf/profile-composition.md)에 둡니다. 대상·환경, 운영 형태, 자료 특성처럼 보이는 아래의 `관점`은 현재 차이를 이해하기 위한 설명이며 고정 taxonomy가 아닙니다. 관점 분류의 남은 가설은 [Profile 관점과 조합](../notes/profile-perspectives.md)에 기록합니다.

| Profile | 관점 | 적합한 경우 |
| --- | --- | --- |
| [Software project](software-project/README.md) | 대상·환경 | 소프트웨어 코드와 설정이 구현의 중심이고 OKF가 프로젝트 지식을 보조할 때 |
| [Knowledge-only](knowledge-only/README.md) | 운영 형태·산출물 | 지식 자체가 주된 산출물일 때 |
| [Large corpus](large-corpus/README.md) | 자료 특성 | 수백~수천 개의 PDF·문서·자료를 다룰 때 |
| [Personal context (preview)](personal-context/README.md) | 대상·환경 | 개인의 삶·관계·상태·선호를 장기 맥락으로 다루는 방식을 실험할 때 |

새로운 사용 사례가 생기면 [프로필의 조합과 경계](../okf/profile-composition.md)에 따라 새 profile이 필요한지, 기존 profile의 조합·변형으로 충분한지, 또는 여러 상황에 재사용되는 일반 OKF pattern으로 다룰 문제인지 먼저 판단합니다. 전문 지식, 혼합형 저장소 등은 실제 사례가 쌓여 현재 profile로 설명하기 어려워질 때 추가합니다. 미래의 경우의 수를 미리 profile로 채우지 않습니다.

실제 검증을 진행 중인 후보는 `preview`로 명시해 발견 가능하게 둘 수 있으며, preview 상태 자체를 채택된 운영 방식으로 간주하지 않습니다.

설계 판단의 근거는 [OKF 지식망](../okf/index.md)에 둡니다. 프로필은 그 지식을 특정 사용 방식에 적용한 구성입니다.

프로필은 적용 맥락의 한 관점을 나타낼 수 있으며, 신규 구축·기존 운영 갱신 같은 작업 유형이나 이번 적용 범위를 정하지는 않습니다. 이 구분의 근거는 [적용 판단](../okf/adoption.md), 실제 진행의 출발점은 [적용 안내](../APPLICATION.md)에 있습니다. 적용 후에는 선택한 구성에 맞는 원자료·새 지식의 투입 위치와 반영 방법을 대상 저장소에 남깁니다.
