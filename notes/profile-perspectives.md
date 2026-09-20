# Profile 관점과 조합에 대한 가설

프로필이 하나의 상호배타적 taxonomy가 아니며 조합·변형할 수 있다는 결론과, 새 사용 사례에서 profile과 일반 pattern을 구분하는 판단은 [프로필의 조합과 경계](../okf/profile-composition.md)로 승격했다.

이 노트에는 아직 확정하지 않은 **관점 분류 자체**와 별도 composition 계층의 필요성만 남긴다.

## 현재 보이는 관점

### 대상과 환경

무엇을 중심으로 이해하고 운영하는지를 설명하는 관점으로 보인다.

현재 예:
- software project
- personal context

향후 organization, business project, case 같은 후보가 생길 수 있지만 필요가 확인되기 전에 profile로 만들지는 않는다.

### 운영 형태와 목적

지식을 어떤 산출물과 활동에 사용하고 운영하는지를 설명하는 관점으로 보인다.

현재 Knowledge-only는 지식 자체가 주된 산출물인 운영 형태를 설명하지만, 단순한 하나의 목적 값으로 환원되는지는 아직 확정하지 않는다.

governance, operations, research/evidence, decision support 같은 후보도 이 관점에서 검토할 수 있다.

### 자료 특성

원자료의 규모와 형태 때문에 달라지는 운영 요구를 설명하는 관점으로 보인다.

현재 Large corpus가 여기에 가장 가깝다. 대량 자료를 모두 내재화하지 않고 핵심 지식과 탐색 경로를 조합하는 문제를 다룬다.

### 통제와 제약

공개 범위, 규제, 감사처럼 지식의 사용에 추가적인 경계가 필요한 경우를 하나의 관점으로 설명할 수 있는지는 아직 불확실하다.

일부는 profile보다 일반 OKF pattern으로 다루는 편이 적절할 수 있다. 실제로 정보 접근과 외부 공개의 구분은 [공개 경계](../okf/disclosure-boundary.md)라는 일반 pattern으로 승격했다.

## 아직 결정하지 않은 구조

현재의 관점들을 고정된 축, frontmatter 값, 디렉터리 계층으로 만들지 않는다. 하나의 profile이 여러 관점에 걸칠 수도 있다.

별도 `compositions/` 계층도 아직 만들지 않는다. [프로필 조합 원칙](../okf/profile-composition.md)에 따라 실제 사례에서 같은 조합이 반복되고, 개별 profile을 함께 적용하는 것만으로 설명되지 않는 고유한 상호작용이 생기는지 관찰한다.

## 다음 검증

- profile 수가 늘어날 때 현재의 설명용 `관점` 열만으로 탐색이 충분한가?
- 같은 관점의 profile이 반복해서 생겨 실제 taxonomy가 유용해지는가?
- 반복되는 profile 조합에 고유한 운영 지식이 생기는가?
- 통제·제약처럼 보이는 특성이 profile보다 일반 pattern으로 계속 승격되는가?
