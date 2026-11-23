# docs — 데모 자료

메인 README의 "🎬 데모" 섹션이 **`docs/demo.gif`** 를 참조합니다.
아래 순서로 데모 GIF를 추가하면 바로 표시됩니다.

## 데모 GIF 만드는 법

1. 백엔드·프론트 로컬 실행 (루트 README의 실행 방법 참고)
2. 화면 녹화 → GIF 변환
   - Windows: [ScreenToGif](https://www.screentogif.com/) (무료, 영역 지정 녹화 → GIF 저장)
   - 또는 `Win + G`(Xbox Game Bar)로 mp4 녹화 후 GIF 변환
3. 핵심 플로우 20~40초: **출발/도착 검색 → 경로 추천(노출부하) → 이동 중 지도·그늘막**
4. 폰 비율로 자르면 깔끔 (메인 README가 `width="320"`로 표시)
5. 파일명을 **`demo.gif`** 로 해서 이 폴더(`docs/`)에 커밋

```bash
# 예시
git add docs/demo.gif
git commit -m "docs: 데모 GIF 추가"
git push
```

> 용량이 크면(>10MB) 프레임레이트/길이를 줄이거나 색상 수를 낮춰 최적화하세요.
