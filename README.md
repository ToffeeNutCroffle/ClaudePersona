# ClaudePersona

클로드 커스텀을 해보아요

## 소개

클로드에 다양한 캐릭터 페르소나를 씌워 대화하는 프로젝트입니다.
슬래시 커맨드 하나로 캐릭터를 전환할 수 있습니다.

## 사용법

`.claude/commands/` 안의 파일이 슬래시 커맨드로 등록됩니다.

```
/char-<캐릭터명>
```

예시:
```
/char-tsundere
/char-pirate
```

## 프로젝트 구조

```
ClaudePersona/
├── .claude/
│   └── commands/
│       └── char-<캐릭터명>.md   ← 슬래시 커맨드로 등록되는 파일
├── personas/
│   └── <캐릭터명>.md            ← 캐릭터 원본 정의 파일 (참고용)
└── TEMPLATE.md                  ← 캐릭터 작성 템플릿
```

## 캐릭터 추가 방법

1. `TEMPLATE.md`를 참고해서 캐릭터를 정의합니다.
2. `personas/<캐릭터명>.md`에 정의 파일을 저장합니다.
3. `.claude/commands/char-<캐릭터명>.md`에 커맨드 파일을 만듭니다.
