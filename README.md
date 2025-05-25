물론입니다! 아래는 **한 번에 복사 가능한 `README.md` 전체 내용**이며, 프로젝트의 **상세 기능, 사용 기술 언어, 실행 방법** 등을 포함한 완성본입니다.

---

```markdown
# Chat ICT - Text Image Scanner

웹 기반 OCR(Text Scanner) 서비스로, 이미지 또는 PDF 파일에서 텍스트를 추출하고 음성으로 재생할 수 있는 기능을 제공합니다.

---

## 📌 주요 기능

### ✅ 1. 이미지 업로드 및 OCR 인식
- JPG, PNG 등의 이미지 파일을 업로드하면 `Tesseract.js`를 통해 한글 + 영어 텍스트 인식
- 인식된 텍스트는 우측 패널에 실시간 출력

### ✅ 2. PDF 파일 업로드 및 텍스트 추출
- PDF 파일에서 텍스트 추출 가능
- 텍스트가 없는 PDF는 캔버스로 렌더링 후 OCR 처리
- 다중 페이지 지원 및 처리 진행률 표시

### ✅ 3. 다국어 텍스트 지원
- 한글 + 영어가 혼합된 문장도 정확히 인식
- 음성 출력 시 각 언어 감지 후 해당 음성으로 자동 재생

### ✅ 4. 텍스트 복사 및 음성 재생
- 버튼 클릭으로 텍스트 복사 가능
- 브라우저 내장 TTS 기능을 활용한 음성 재생
- 재생 중지 기능 제공

---

## 🛠️ 사용된 기술 스택

| 구분 | 기술 |
|------|------|
| 프론트엔드 | HTML5, CSS3, JavaScript |
| OCR 라이브러리 | [Tesseract.js](https://github.com/naptha/tesseract.js) |
| PDF 파서 | [pdf.js](https://mozilla.github.io/pdf.js/) |
| 텍스트 음성 변환 | Web Speech API (`SpeechSynthesisUtterance`) |
| 호스팅 | GitHub Pages |

---

## 🌐 배포 URL

👉 [https://gd000908.github.io/Chat-ICT/](https://gd000908.github.io/Chat-ICT/)

---

## 📂 프로젝트 구조

```

Chat-ICT/
├── index.html                # 메인 페이지
├── README.md
├── image/                    # 프로젝트에 사용되는 아이콘 및 이미지
│   ├── ocr-icon.png
│   ├── upload-icon.png
│   ├── pdf-upload-icon.png
│   ├── copy-icon.png
│   ├── play-icon.png
│   ├── stop-icon.png
│   └── anu.gif

```

---

## ⚙️ 실행 방법

1. 이 저장소를 클론하거나 `index.html`을 웹 브라우저에서 실행
2. 이미지(`.jpg`, `.png`) 또는 PDF 파일을 업로드
3. 자동으로 텍스트가 추출되어 우측에 표시됨
4. 복사 버튼 클릭 시 텍스트 클립보드 복사
5. 음성 재생 버튼으로 텍스트를 읽을 수 있음 (언어 자동 감지)

---

## 📝 라이선스

MIT License  
본 프로젝트에서 사용된 아이콘 및 이미지의 저작권은 각 제작자에게 있으며, 비상업적 목적의 사용만을 권장합니다.

```

---

이제 복사해서 `README.md` 파일에 그대로 붙여넣기만 하면 됩니다.
필요하면 `한글/영문 혼합 버전`, `전부 한글`, `전부 영어` 버전도 만들어드릴 수 있어요.
