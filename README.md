# JAYPEE 골프 조추첨 사다리

## 폴더 구성
- `index.html` : 프로그램 본체
- `photos/jaypee.jpg` : 골프장 배경 사진
- `photos/ball.png` : (선택) 골프공 사진. 넣으면 굴러가는 공이 이 사진으로 표시됨. 없으면 기본 공 그림
- (선택) 시드별 배경음악 파일: `bgm_exc.mp3`, `bgm_s2.mp3`, `bgm_s3.mp3`, `bgm_s4.mp3`, `bgm_mix.mp3`(MODE 3 통합), `bgm_top.mp3`. index.html 과 같은 위치에 넣으면 해당 라운드에서 재생. 없는 시드는 내장 멜로디 재생
- `photos/이름.jpg` : 참가자 사진 (예: `photos/서보철.jpg`). jpg / jpeg / png / webp 가능. 없으면 이름 아이콘으로 표시

## GitHub 업로드 절차
1. github.com 로그인 → 우측 상단 `+` → `New repository`
2. Repository name 입력 (예: `golf-ladder`), `Public` 선택 → `Create repository`
3. `uploading an existing file` 클릭 → 압축을 푼 `index.html`, `photos` 폴더를 끌어다 놓기 → `Commit changes`
4. `Settings` → `Pages` → Branch 를 `main` / `(root)` 로 선택 → `Save`
5. 1~2분 후 `https://<계정>.github.io/golf-ladder/` 로 접속

## 사용 방법
- 상단 MODE 1 / 2 / 3 클릭 → 모드 설명 팝업 → `MODE n 시작` (전환 시 결과 초기화)
- 🔊 효과음 켜기/끄기, 🎵 배경음악 켜기/끄기 (음악은 기본 꺼짐)
- 라운드 시작 전: `이름 순서 섞기`(상단 이름 배치 재추첨), `조 위치 섞기`(하단 조 배치 재추첨), `사다리 보기`(3초간 사다리 공개), `사다리 추가`(누를 때마다 가로줄 1개 추가)
- 빛나는 사진 클릭 → 스윙 → 공이 사다리를 따라 홀컵 도착 → 우측 표 자동 반영
- 라운드 인원이 모두 끝나면 `다음 라운드 ▶` 클릭
- 결과는 브라우저에 자동 저장 (새로고침해도 유지). `초기화` 로 삭제
- 화면이 좁으면 F11 전체 화면 권장
