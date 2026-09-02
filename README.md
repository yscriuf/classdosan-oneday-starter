# classdosan-oneday-starter

바이브코딩 원데이 클래스 진행용 스타터 패키지입니다. 이 폴더를 Claude Code에서 열면, Claude가 `CLAUDE.md`를 읽고 수업을 단계별로 안내합니다.

## 시작하는 법
1. Claude Code Desktop을 설치하고 로그인합니다.
2. 빈 `my-service` 폴더를 만들고, 새 Claude Code 세션에서 그 폴더를 엽니다.
3. Claude에 이렇게 부탁하세요:
   > 이 폴더에 수업 패키지를 받아줘. 폴더에 .DS_Store 같은 파일이 남아 clone이 안 되면 그것들을 정리하고 현재 폴더에 그대로 받아줘: https://github.com/yscriuf/classdosan-oneday-starter.git

   Claude가 `git clone https://github.com/yscriuf/classdosan-oneday-starter.git .` 로 **현재 폴더에 flat하게** 받아 수업을 시작합니다. (끝의 `.`이 "현재 폴더로"라는 뜻 — 하위 폴더를 만들지 않아야 루트 `CLAUDE.md`가 자동 로드됩니다.)

   > ⚠️ `git clone … .`은 **폴더가 비어 있어야** 됩니다. Finder로 폴더를 열어봤거나 편집기가 파일을 만들어 `.DS_Store`·`.claude/` 등이 있으면 `destination path '.' already exists and is not an empty directory`로 거부됩니다 — 위처럼 부탁하면 Claude가 정리 후 받습니다.
4. 이후 Claude의 안내를 따라가면 됩니다.

> `steps/`, `PROGRESS.md`, 진행 규칙, 이 안내는 수업이 끝나면 정리(삭제)됩니다.
