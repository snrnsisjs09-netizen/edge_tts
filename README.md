# lecture-tts

강의 영상 내레이션을 edge-tts로 생성하는 레포.

- `<프로젝트>/scenes.json`을 올리면 GitHub Actions가 `audio/*.mp3`와 `tts.json`을 만들어 커밋한다.
- 수동 실행: Actions ▸ Generate narration ▸ Run workflow
- 음성: 여성 ko-KR-SunHiNeural, 남성 ko-KR-InJoonNeural (장면마다 교대)
