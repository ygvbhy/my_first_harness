# Commit Message Review Report

- 검토 대상: `_workspace/commit-draft.md`
- 대조 기준: `git diff --cached`
- 검토 회차: 1회차

## 커밋 초안

```
docs: add README

Add initial README with project title to start the project documentation.
```

## 판정: PASS

## 사유

1. **형식**: `docs: add README` — `type: subject` 패턴을 따름. `type`은 유효한 Conventional Commits 타입(`docs`)이며, `scope`는 생략되었으나 Conventional Commits 스펙상 scope는 선택 사항이므로 형식 이탈 아님. subject는 소문자 시작, 명령형(`add`), 마침표 없음 — 규칙 준수.
2. **제목 길이**: `docs: add README` = 17자로 일반 권장 한도(50자) 내에 충분히 들어옴.
3. **본문-제목 구분**: 제목과 본문 사이 빈 줄 존재 — 형식 정상.
4. **diff 일치 여부**: `git diff --cached` 결과 `README.md` 신규 파일에 `# my-first-harness` 한 줄만 추가됨. 초안 본문 "Add initial README with project title to start the project documentation."은 이 변경 내용(신규 README, 프로젝트 타이틀 추가)과 정확히 일치하며 과장·누락된 사실 없음.

## 수정 지시

해당 없음 (PASS).
