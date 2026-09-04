# 스킬 저장소

## 현재 규칙

- 이 저장소는 `purpose-first-design` 독립 스킬의 정본이다. 저장소 이름과 설치 URL은 `purpose-first-design`이다.
- 기본 README 언어는 한국어이고, 영어 문서는 `README.en.md`에 둔다.
- 설치 가능한 스킬은 `skills/purpose-first-design/` 아래에 둔다.
- `SKILL.md`는 영문 base skill이며 frontmatter metadata를 가진다.
- `SKILL.ko.md`는 한국어 페어이며 frontmatter를 넣지 않는다.
- `skills/purpose-first-design/agents/openai.yaml`은 OpenAI-facing interface metadata를 제공한다.
- 프로젝트 라이선스는 MIT다.
- 저장소 로컬 운영 지침은 `AGENTS.md`에 둔다.
- README는 스킬 저장소 형태를 따른다: 요약, 빠른 시작, 사용 사례, 짧은 지원/라이선스 안내.
- 방향 문서는 `docs/` 아래에 두되, 스킬 사용자가 런타임에 참고해야 하는 내용은 배포 스킬 본문이나 스킬 패키지 내부 reference로만 둔다.

## 범위 경계

- 스킬은 어떤 저장소에서도 독립적으로 쓸 수 있어야 한다.
- 스킬 본문은 목적 우선 방향 결정을 맡고, owner discovery, 확정된 구현 구조화나 문서 편집을 직접 대체하지 않는다.
- 저장소 맥락, 패키징, 반복되는 유지보수 필요를 지원하지 않는 추가 파일은 피한다.
