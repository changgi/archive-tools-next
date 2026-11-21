# archive-tools-next — 「고문서 한 장」 영상 저장소

[archive-tools](https://github.com/changgi/archive-tools) 예시 사이트(「고문서 한 장」)의 **영상(mp4)만** 따로 두는 곳입니다.
GitHub Pages가 사이트 하나를 1GB까지만 올려 주어, 가장 큰 영상을 이쪽으로 옮겼습니다. 전시 · 카드 · 자막 · 포스터 · 기록 꾸러미는 원래 저장소에 있습니다.

- 갤러리: https://changgi.github.io/archive-tools/examples/
- 영상 주소: `https://changgi.github.io/archive-tools-next/media/<편 ID>_reel.mp4` (9:16) · `_wide.mp4` (16:9)
- 고정값(SHA-256)은 각 편 폴더의 `record.json` · `checksums.sha256`(원래 저장소)에 있고, 원래 저장소 CI가 이 저장소를 함께 가져와 대조합니다.
- 옮기기 · 링크 바꾸기: 원래 저장소의 `tools/series/media_offload.py`

## 이용 조건

- 영상 속 고문서 이미지: 한국학중앙연구원 한국고문서자료관 소장 · 제공(각 소장처 기탁). 다시 쓰려면 자료관을 통한 소장처 동의가 필요하며, 문제가 있으면 내립니다.
- 영상의 글 · 구성(판독 · 번역 · 이야기): CC BY 4.0 — 「고문서 한 장」 Song Chang-gi
- 음성: Microsoft Edge TTS로 합성

만든 사람: Song Chang-gi · chgsong@naver.com · https://github.com/changgi
