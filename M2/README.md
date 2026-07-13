# 🥤 LUMIDROP | AI 기반 멀티모달 브랜드 광고 제작

> GenAI 기초 2 : 멀티모달 콘텐츠 제작 프로젝트

**한 모금, 분위기 전환.**

---

# 📌 프로젝트 소개

LUMIDROP은 반복되는 일상 속에서 한 모금으로 기분을 전환해주는 가상의 프리미엄 스파클링 워터 브랜드입니다.

본 프로젝트는 생성형 AI를 활용하여

- 브랜드 기획
- 스토리보드 작성
- 이미지 생성
- 영상 생성
- 오디오 생성
- 최종 광고 제작

까지의 전체 제작 과정을 직접 설계하고 구현한 프로젝트입니다.

---

# ✅ 과제 요구사항 체크

|항목|충족 여부|
|------|:---:|
|브랜드 정의|✅|
|캠페인 목표 정의|✅|
|스토리보드 작성|✅|
|Scene별 필수 항목 작성|✅|
|프롬프트 작성|✅|
|프롬프트 수정 전/후 비교|✅|
|이미지 AI 사용|✅|
|비디오 AI 사용|✅|
|오디오 AI 사용|✅|
|최종 광고 제작(10초 이내)|✅|
|브랜드 노출|✅|
|CTA 포함|✅|

---

# 🎯 프로젝트 목표

생성형 AI를 활용하여

> 기획 → 프롬프트 → 이미지 → 영상 → 오디오 → 편집

까지의 멀티모달 광고 제작 파이프라인을 구축하는 것을 목표로 하였습니다.

---

# 🏷 브랜드 아이덴티티

|항목|내용|
|------|------|
|브랜드|LUMIDROP|
|제품|스파클링 워터|
|Target|20~30대|
|Tone & Manner|청량함 / 미니멀 / 미래적|
|USP|제품을 여는 순간 분위기가 전환되는 경험|
|Campaign Goal|브랜드 인지도 향상|
|Key Message|한 모금, 분위기 전환.|
|CTA|지금, 분위기를 바꿔보세요.|

---

# 🛠 사용한 AI 도구

|분야|도구|선택 이유|
|------|------|----------------|
|기획|ChatGPT|브랜드 기획 및 프롬프트 작성|
|이미지 생성|ChatGPT Images|제품 디자인 일관성 유지|
|영상 생성|Runway|Image to Video 생성|
|오디오 생성|ElevenLabs|내레이션·효과음 생성|
|편집|CapCut|최종 광고 편집|

---

# 🔄 제작 파이프라인

```text
브랜드 기획
      │
      ▼
스토리보드 작성
      │
      ▼
프롬프트 작성
      │
      ▼
ChatGPT Images
      │
      ▼
Runway
(Image → Video)
      │
      ▼
ElevenLabs
(Audio)
      │
      ▼
CapCut
      │
      ▼
최종 광고 제작
```

---

# 🎬 광고 구성

## Scene 1

### 반복되는 일상

- 무채색 작업 공간
- 낮은 채도
- 반복되는 분위기 표현

화면 카피

> 오늘도 똑같다면?

---

## Scene 2

### 변화의 시작

- 캔이 열리는 순간
- 청록색 빛 확산
- 탄산 기포 생성

---

## Scene 3

### 청량한 전환

- 미래적인 공간
- 제품 가치 전달

내레이션

> 한 모금으로, 분위기를 바꿔.

---

## Scene 4

### 브랜드 엔드카드

```text
LUMIDROP

한 모금, 분위기 전환.
```

브랜드명과 슬로건을 노출하여 광고를 마무리합니다.

---

# 💡 프롬프트 개선

## 수정 전

- 기포가 너무 많음
- 제품 심벌이 가려짐
- 효과가 과도함

## 수정 후

- 입자 수 감소
- 심벌 보호
- 조명 방향 고정
- 제품 위치 유지

### 결과

- 제품 가독성 향상
- 브랜드 일관성 유지
- 장면 연결성 개선
## 씬별 기획 및 생성 프롬프트

### Scene 1 — 반복되는 일상

- 시간: 0.0~2.0초
- 목표: 반복되는 공부와 업무로 일상이 무채색처럼 느껴지는 상황 표현
- 화면 카피: 오늘도 똑같다면?
- 이미지 결과: `assets/images/LD_S01_image_v01.png`
- 영상 결과: `assets/videos/LD_S01_video_v01.mp4`

#### 이미지 생성 프롬프트

> Use the uploaded LUMIDROP product image as the exact product reference.
> Create scene 1 of a premium cinematic beverage advertisement.
> Place the same LUMIDROP can at the center of a dark gray office desk
> in a minimal modern workspace.
> Use muted monochrome gray colors, low saturation, soft dim lighting,
> a clean desk, a slightly top-down camera angle, and a 16:9 composition.
> Keep the product shape, turquoise color, coral accent,
> water-drop symbol, proportions, and material consistent.
> No person, no hand, no extra can, no product deformation,
> no logo distortion, and no dramatic special effects.

#### 이미지→영상 프롬프트

> The product can remains completely still and keeps its original shape.
> The camera performs a very slow and smooth push-in toward the product.
> The dim office lighting changes only slightly.
> No camera shake, no fast movement, no product rotation,
> no product deformation, no logo change, and no additional objects.

---

### Scene 2 — 변화의 시작

- 시간: 2.0~4.2초
- 목표: 제품이 열리는 순간 무채색 공간이 청량한 분위기로 변화하기 시작함
- 이미지 결과: `assets/images/LD_S02_image_v02.png`
- 영상 결과: `assets/videos/LD_S02_video_v01.mp4`
- 효과음: `assets/audio/LD_S02_canopen_v01.wav`

#### 이미지 생성 프롬프트

> Use the uploaded product master image as the exact product reference.
> Keep the LUMIDROP can in exactly the same position, size,
> and camera angle as the previous scene.
> Maintain the dark gray atmosphere on the left side
> and allow a soft turquoise light to spread from the right side.
> Add a small number of bubbles and particles without covering
> the front symbol.
> Preserve the exact can shape, color, proportions, and material.
> No person, no hand, no extra can, no explosion,
> no splash, and no product deformation.

#### 이미지→영상 프롬프트

> The LUMIDROP can remains perfectly rigid, centered, and unchanged.
> A soft turquoise light slowly spreads from right to left.
> A small number of bubbles and fine particles gently rise
> without covering the product.
> The camera remains nearly stationary.
> No explosion, no fast movement, no camera shake,
> no product rotation, and no logo change.

---

### Scene 3 — 청량한 전환

- 시간: 4.2~7.0초
- 목표: 한 모금이 지루한 일상을 밝고 청량한 순간으로 전환한다는 가치 전달
- 내레이션: 한 모금으로, 분위기를 바꿔.
- 이미지 결과: `assets/images/LD_S03_image_v01.png`
- 영상 결과: `assets/videos/LD_S03_video_v01.mp4`
- 음성 결과: `assets/audio/LD_S03_voice_v01.wav`

#### 이미지 생성 프롬프트

> Use the uploaded product master image as the exact product reference.
> Transform the background into a bright, clean,
> futuristic turquoise environment.
> Place the same LUMIDROP can at the center.
> Add a soft circular turquoise glow,
> a few transparent water droplets,
> small carbonation bubbles, and subtle coral accents.
> Keep the product clearly visible and unobstructed.
> No person, no hand, no extra can, no large splash,
> no explosion, and no product deformation.

#### 이미지→영상 프롬프트

> The LUMIDROP can remains centered and keeps its original shape.
> Transparent droplets and small bubbles gently float upward.
> The circular turquoise light slowly pulses once.
> The camera makes a very slight smooth arc movement.
> No fast rotation, no camera shake, no product deformation,
> and no additional product.

---

### Scene 4 — 브랜드 엔드 카드

- 시간: 7.0~9.04초
- 목표: 브랜드명을 명확하게 노출해 LUMIDROP을 기억하게 함
- 화면 카피: LUMIDROP / 한 모금, 분위기 전환.
- 이미지 결과: `assets/images/LD_S04_image_v01.png`
- 영상 결과: `assets/videos/LD_S04_video_v01.mp4`

#### 이미지 생성 프롬프트

> Use the uploaded product master image as the exact product reference.
> Create a minimal final end card with a bright turquoise background.
> Place the product front-facing in the upper-middle of the frame.
> Add a soft circular turquoise glow and subtle coral lighting.
> Leave generous empty space below the product for the brand name
> and slogan, which will be added during editing.
> No person, no hand, no extra can, no bubbles,
> no splash, no generated text, and no product deformation.

#### 이미지→영상 프롬프트

> The LUMIDROP can remains perfectly rigid,
> front-facing, and centered.
> Only the circular turquoise glow slowly expands once.
> The camera remains completely still.
> No product movement, no camera movement,
> no particles, no generated text, and no logo change.
---

# 🚨 문제 해결

|문제|해결 방법|
|------|----------------|
|제품 변형|제품 Reference 고정|
|스타일 불일치|동일 Reference 사용|
|텍스트 오류|CapCut에서 직접 입력|
|크레딧 부족|이미지 먼저 생성 후 영상 변환|
|오디오 톤 차이|공통 키워드 반복 사용|

---

# 🔀 대체 가능한 AI 도구

|분야|대체 도구|
|------|-------------|
|이미지|Midjourney|
|이미지|Adobe Firefly|
|영상|Kling|
|영상|Pika|
|음악|Suno|
|음성|CapCut TTS|

---

# 📁 프로젝트 구조

```text
LUMIDROP
│
├── README.md
├── storyboard.pdf
├── LUMIDROP_brand_ad.mp4
├── scene01.png
├── scene02.png
├── scene03.png
└── scene04.png
```

---

# 🎥 최종 결과

|항목|내용|
|------|------|
|영상 길이|약 9.5초|
|해상도|1920×1080|
|Frame Rate|30fps|
|Video Codec|H.264|
|Audio Codec|AAC|

---

# 📷 결과 화면

> Scene 1

(이미지 삽입)

> Scene 2

(이미지 삽입)

> Scene 3

(이미지 삽입)

> Scene 4

(이미지 삽입)

---

# 🎬 최종 광고 영상

GitHub에 MP4 파일 업로드

또는 YouTube 링크 첨부

---

# 📄 프로젝트 보고서

스토리보드 및 상세 제작 과정은 아래 PDF에서 확인할 수 있습니다.

- storyboard.pdf

---

# 📚 회고

이번 프로젝트를 통해

- AI 광고 제작 파이프라인을 설계하는 방법
- 프롬프트 수정의 중요성
- 멀티모달 AI 도구의 역할
- 브랜드 일관성을 유지하는 방법

을 학습하였습니다.
