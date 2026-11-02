# 복합운동 논문 발표 — GitHub Pages 웹 슬라이드

총 45장의 웹 슬라이드와 수정 가능한 PowerPoint 파일입니다.

## 게시 방법
1. GitHub에서 새 공개 저장소를 만듭니다 (예: `combined-exercise-slides`).
2. 이 폴더 안의 파일과 폴더를 저장소 최상위(root)에 모두 업로드합니다. ZIP 파일 자체를 업로드하면 안 됩니다.
3. GitHub 저장소 **Settings → Pages → Build and deployment → Deploy from a branch** 를 선택합니다.
4. Branch를 `main`, 폴더를 `/(root)`로 설정한 다음 저장합니다.
5. 페이지 주소는 보통 `https://사용자명.github.io/저장소명/` 형식입니다.

## 발표 조작
- ←/→ 또는 Space: 앞/뒤 슬라이드
- F: 전체화면
- N: 발표 메모 표시/숨기기
- M: 목차 표시/숨기기
- Home/End: 처음/마지막 슬라이드
- 슬라이드 번호는 URL 해시로 보존되어 공유 가능

## 파일 구성
- `index.html`, `style.css`, `app.js`, `slides.json`: 정적 웹 발표 앱
- `assets/slides`: 45장 이미지 — 파워포인트 원본으로부터 렌더링한 슬라이드
- `assets/source/paper.pdf`: 출처 논문 PDF 14페이지
- `발표자료_편집가능.pptx`: 편집 가능한 PowerPoint 파일 (원문 표 및 부록은 그림)

## 편집 가이드
웹 슬라이드의 **이미지는 PPTX를 렌더링한 것**입니다. 시각적인 내용을 편집할 때는 PPTX를 수정하고 해당 슬라이드를 다시 렌더링하여 `assets/slides` 이미지를 교체해야 합니다. 제목과 노트는 `slides.json`에서 변경할 수 있습니다.

## 근거와 한계
원문: 임영훈·최고은·이만균(2026), 한국체육학회지 65(2), 317–330. DOI: https://doi.org/10.23949/kjpe.2026.3.65.2.19
선행연구 분석은 기존 발표자료에 포함된 Cortes et al.(2023), Sardeli et al.(2022) 비교를 유지했습니다. 원문 Table의 이미지와 기존 자료의 재구성표는 구분해서 사용해야 합니다.

이 저장소는 정적 HTML이며 별도 빌드 단계가 필요하지 않습니다.
