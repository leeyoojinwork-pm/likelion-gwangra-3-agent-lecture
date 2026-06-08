# AI 부캐 Agent 강의자료 자료조사 요약

## 강의에 반영한 핵심

1. Agent는 무조건 복잡하게 만드는 것이 아니라, 가장 단순한 업무 구조에서 시작한다.
   - 반영 장표: 자료조사에서 확인한 Agent 설계의 공통 원칙
   - 출처: Anthropic, Building effective agents

2. 워크플로우와 Agent는 구분된다.
   - 워크플로우: 정해진 경로로 LLM과 도구를 실행
   - Agent: LLM이 상황에 따라 과정과 도구 사용을 동적으로 결정
   - 반영 장표: 자료조사에서 확인한 Agent 설계의 공통 원칙
   - 출처: Anthropic, Building effective agents

3. 프롬프트 엔지니어링보다 맥락 엔지니어링이 중요해진다.
   - 핵심은 더 긴 프롬프트가 아니라, 어떤 정보가 모델의 맥락에 들어가야 하는지 큐레이션하는 것
   - 반영 장표: 프롬프트보다 중요한 질문은 어떤 맥락을 준비할 것인가입니다
   - 출처: Anthropic, Effective context engineering for AI agents

4. 폴더와 파일 구조 자체가 Agent의 맥락 설계가 된다.
   - 파일 경로, 폴더명, 문서명이 Agent가 필요한 맥락을 찾는 색인 역할을 함
   - 반영 장표: 콘텐츠 편집장 Agent는 자료를 이 순서로 읽어야 합니다 / 폴더 설계 파트
   - 출처: Claude, Building agents with the Claude Agent SDK

5. Guardrail과 평가 기준은 반복 실행 품질을 만든다.
   - 입력, 출력, 도구 실행 단계에서 무엇을 막고 무엇을 사람이 확인할지 구분해야 함
   - 반영 장표: Guardrail / Rule, Guardrail, Check / 업데이트 루프
   - 출처: OpenAI Agents SDK Guardrails, Anthropic Demystifying evals for AI agents

6. AI Agent의 기본 작동 흐름은 인식, 추론, 실행, 학습/적응으로 설명할 수 있다.
   - 반영 장표: AI Agent는 네 단계를 반복하며 일을 처리합니다
   - 출처: IBM, What is Agentic AI?

## 장표 시각화에 반영한 템플릿

- Maturity Ladder: 단순 사용 -> 템플릿화 -> 워크플로우 -> Agent화
- Lens Filter: 긴 프롬프트가 아니라 필요한 맥락만 통과시키는 구조
- Value Chain Beads: Input -> 분리 -> 변환 -> 검수 -> Output
- Spiral Learning: 실행 -> 비교 -> 수정 -> 기록 -> 재실행

템플릿 출처: https://github.com/leeyoojinwork-pm/idea-visualization-napkin-templates
