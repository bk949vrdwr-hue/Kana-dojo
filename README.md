# かな道場 (카나 도장)

하루 5분씩 히라가나·가타카나 92자를 배우는 학습 앱입니다. iPhone·iPad에서 홈 화면에 추가해 앱처럼 쓸 수 있습니다.

- 글자 카드 학습: 한국어 연상법과 일본어 원어민 발음
- 퀴즈 10문제: 7초 제한, 콤보 보너스, 듣기 문제
- 따라쓰기: 손가락으로 쓰면 자동 채점
- 오프라인 사용 가능, 학습 기록은 기기에 저장

## GitHub Pages로 배포하기

폴더 없이 **파일 15개만 모두 올리면 됩니다** (아이콘 PNG도 루트에 있습니다).

1. GitHub에서 새 저장소(Repository)를 만듭니다. 예: `kana-dojo`, **Public**
2. 저장소 화면에서 **uploading an existing file** 링크를 클릭합니다
3. 이 폴더의 파일을 **모두 선택**(마우스로 드래그하거나, 하나 클릭 후 `Ctrl+A`/`Cmd+A`)해 끌어다 놓습니다
   - 숨김 파일 `.nojekyll`은 드래그 시 빠질 수 있습니다. 없어도 앱은 동작합니다
4. **Commit changes**를 누릅니다
5. **Settings → Pages** → Source: `Deploy from a branch`, Branch: `main` / `(root)` → **Save**
6. 1~2분 뒤 `https://<내아이디>.github.io/kana-dojo/` 가 열립니다

## iPhone·iPad에 설치하기

1. 위 주소를 **Safari**로 엽니다
2. 공유 버튼(□↑) → **홈 화면에 추가**
3. 홈 화면의 「かな道場」 아이콘으로 실행합니다

## 업데이트

`index.html`을 새 버전으로 바꿔 올리면(Pencil 아이콘 → 파일 교체 → Commit), 앱을 다시 열 때 자동 반영됩니다.
