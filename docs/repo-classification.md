# 📚 Repository Classification Rules

이 문서는 저장소를 정리/관리하기 위한 기준을 정의합니다.  
목적은 레포를 체계적으로 분류하고, 관리 활용을 용이하게 하는 것입니다.

---

## 1. Topic 정의

- **portfolio**  
  - 포트폴리오로 활용할 수 있는 대표 프로젝트
  - 외부에 공개할 가치가 있는 레포  
  - `game-dev`, `tool` 등 다른 topic과 중복 가능  

- **game-dev**  
  - Unity 기반 게임 관련 프로젝트  
  - 프로토타입, 엔진, 샘플 게임 포함  

- **tool**  
  - Unity/개발 툴, 유틸리티, 재사용 가능한 라이브러리  

- **study**  
  - 학습/정리용 레포  
  - 책/강의/스터디 기록, 디자인 패턴, 아키텍처 실험  

- **algo**  
  - 알고리즘/코딩 테스트 풀이  
  - Programmers, LeetCode, Baekjoon 등  

- **exp**  
  - 단기 실험/PoC(Proof of Concept)  
  - 1~2일짜리 테스트 코드, 실험적인 시도  

- **archive**  
  - 더 이상 유지하지 않지만 보관할 가치가 있는 레포  
  - 옛날 프로토타입, 과거 학습물  

---

## 2. 네이밍 규칙

형식: **`[접두사]-[핵심이름]-[필요시 접미사]`**

- **접두사 (카테고리)**  
  - `game-` : 게임/프로토타입  
  - `tool-` : 유니티 툴/라이브러리  
  - `study-` : 학습/정리  
  - `algo-` : 알고리즘  
  - `exp-` : 단기 실험  
  - `archive-` : 과거/보관  

- **접미사 (상세 구분)**  
  - `-unity` : Unity 기반  
  - `-csharp` : C# 기반  
  - `-demo` : 샘플/데모  
  - `-2025` : 연도별 버전  

---

## 3. 예시 매핑

- `game-match3-demo-unity` → `portfolio, game-dev`  
- `tool-unity-popup-manager` → `portfolio, tool`  
- `study-csharp-design-patterns` → `study`  
- `algo-programmers-lv1` → `algo`  
- `exp-di-framework` → `exp`  
- `archive-ngui-demo` → `archive`  

---

## 4. 관리 원칙

1. **중복 태깅 허용**  
   - 예: `portfolio + game-dev`  
2. **archive 토픽은 과감히 활용**  
   - 삭제하지 않고 보관만 하는 레포는 모두 `archive`로 이동  
3. **Pinned Repo는 portfolio만 노출**  
   - 대표작 6개 이내로 유지  
4. **주기적 점검**  
   - 분기별로 새로운 레포가 생기면 topic/tag 부여  
