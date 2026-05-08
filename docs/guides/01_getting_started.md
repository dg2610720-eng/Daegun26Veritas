# 🚀 베리타스 시작 가이드 (Codespaces & Git)

이 가이드는 우리 동아리 활동의 기본인 **GitHub Codespaces** 설정과 **과제 제출 방법**을 설명합니다.

---

## 1. 환경 설정 (최초 1회)
1. 멘토의 레포지토리(`Daegun26Veritas`) 우측 상단의 **Fork** 버튼을 누릅니다.
2. 본인 계정으로 복사된 레포지토리에서 **[<> Code]** -> **[Codespaces]** -> **[Create codespace on main]**을 클릭합니다.
3. 왼쪽 하단에 `Setting up Codespace`가 끝나고 터미널에 `pip install`이 자동으로 실행될 때까지 기다립니다.

## 2. 과제 수행 방법
1. `curriculum/` 폴더에서 오늘 공부할 `.ipynb` 파일을 찾습니다.
2. 해당 파일을 복사(Ctrl+C)하여 `submissions/[본인학년]_year/[이름]/` 폴더 안에 붙여넣기(Ctrl+V) 합니다.
3. 본인 폴더에 복사한 파일로 실습을 진행합니다.

## 3. 내 작업 저장하고 제출하기 (중요!)
작업이 끝났다면 아래 명령어를 터미널(Terminal)에 순서대로 입력하세요.

1. **내 변경사항 저장소에 올리기**
   ```bash
   git add .
   git commit -m "[학년/이름] 1주차 과제 제출"
   git push origin main
   ```
2. 멘토에게 제출하기 (PR)
- 본인의 GitHub 레포지토리 웹페이지로 이동합니다.
- 상단의 **[Contribute]** -> **[Open Pull Request]**를 누릅니다.
- 템플릿 양식에 맞춰 내용을 적고 **[Create pull request]**를 누르면 끝!

## ​💡 팁
- 자동 저장: Codespaces는 자동 저장이 기본이랍니다. 작성한 코드는 Codespaces에 남아 있어요.
- 코파일럿: Codespaces에서는 윈도우에서 제공하는 AI인 코파일럿이 레포지토리마다 맞춤으로 도움을 주게 설정할 수도 있어요.