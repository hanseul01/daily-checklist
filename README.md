# 오늘 할 일 수첩

그날그날 할 일을 적고 체크하는 개인용 웹 앱. 맥과 아이폰에서 같은 목록을 쓴다.

- 앱 주소: https://hanseul01.github.io/daily-checklist/
- 앱 코드(공개): `hanseul01/daily-checklist` — `index.html` 한 파일. 할 일 내용은 여기에 들어가지 않는다.
- 할 일 기록(비공개): `hanseul01/daily-checklist-data`의 `data.json`. 저장할 때마다 커밋이 하나씩 쌓인다.

## 기기 연결

기기마다 처음 한 번 GitHub 토큰(fine-grained, `daily-checklist-data` 저장소만, Contents 읽기·쓰기)을 넣는다. 토큰은 그 기기 브라우저에만 저장된다. 아이폰에서 '홈 화면에 추가'로 연 앱은 Safari와 저장 공간이 따로라서, 홈 화면 앱에서 한 번 더 넣어야 한다. 토큰이 만료되면 앱이 새 토큰을 요구한다.

## 고치는 법

`index.html`을 고쳐서 커밋·푸시하면 1~2분 뒤 앱 주소에 반영된다.
