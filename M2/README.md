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
|오디오 생성|ElevenLabs|내레이션·효과음 생성|
|편집|CapCut|최종 광고 편집|
| 자산 구분 | 생성 방식 및 도구 | 대표 결과 파일 | 사용 목적 |
|---|---|---|---|
| 씬별 모션 영상 | Google Flow 이미지→영상 | `LD_S01_video_v01.mp4` 등 | 생성된 기준 이미지에 카메라 이동, 조명 변화, 기포 움직임을 추가 |

### 영상 생성 도구 — Google Flow

Google Flow의 이미지→영상 기능을 사용하여
ChatGPT Images로 만든 씬별 기준 이미지를 짧은 영상으로 변환하였다.

제품 디자인의 일관성을 유지하기 위해 텍스트만으로 영상을 새로 생성하지 않고,
완성된 제품 이미지를 시작 프레임 또는 레퍼런스로 제공하였다.

영상 프롬프트에서는 제품 자체의 변형을 최소화하고
카메라 줌, 청록색 빛, 기포, 물방울과 배경 조명 등
필요한 움직임만 구체적으로 지시하였다.

대표 결과 파일:

- `LD_S01_video_v01.mp4`
- `LD_S02_video_v01.mp4`
- `LD_S03_video_v01.mp4`
- `LD_S04_video_v01.mp4`
---
## 소스·저작권 및 AI 자산 사용 원칙

### 직접 촬영 및 스톡 소스 사용 여부

- 직접 촬영한 사진이나 영상: 사용하지 않음
- 무료·유료 스톡 이미지와 스톡 영상: 사용하지 않음
- 외부에서 다운로드한 음악 및 효과음: 사용하지 않음
- 실존 인물, 유명인 또는 기존 캐릭터 기반 딥페이크: 사용하지 않음
- 핵심 시각·청각 소스는 생성형 AI로 직접 제작함

CapCut은 AI로 생성한 이미지, 영상, 음성, 음악과 효과음을 연결하고
컷 길이, 자막, 전환, 오디오 볼륨과 출력 설정을 조정하는
통합 편집 용도로만 사용하였다.

### AI 생성 자산별 출처

| 자산 구분 | 생성 방식 및 도구 | 대표 결과 파일 | 사용 목적 |
|---|---|---|---|
| 제품 마스터 이미지 | ChatGPT Images | `LD_product_master_v01.png` | 모든 씬에서 사용할 제품 디자인 기준 고정 |
| 씬 1 이미지 | ChatGPT Images | `LD_S01_image_v01.png` | 무채색의 반복되는 작업 환경 표현 |
| 씬 2 이미지 | ChatGPT Images | `LD_S02_image_v02.png` | 회색에서 청록색으로 변화하는 전환 표현 |
| 씬 3 이미지 | ChatGPT Images | `LD_S03_image_v01.png` | 청량한 제품 가치 장면 표현 |
| 씬 4 이미지 | ChatGPT Images | `LD_S04_image_v01.png` | 브랜드 엔드 카드 배경 제작 |
| 씬별 모션 영상 | Google Flow 이미지→영상 | `LD_S01_video_v01.mp4` 등 | 기준 이미지에 카메라·빛·기포 움직임 추가 |
| 내레이션 | ElevenLabs | `LD_S03_voice_v01.wav` | 핵심 메시지 음성 전달 |
| 캔 개봉 효과음 | ElevenLabs | `LD_S02_canopen_v01.wav` | 제품 개봉 순간의 청량감 강화 |
| 배경음악 | 실제 사용한 음악 생성 도구명 | `LD_BGM_v01.wav` | 광고 전체 분위기와 감정 흐름 구성 |
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
## 프로젝트 폴더 구조와 파일 관리 규칙

### 폴더 구조

```text
M2/
├── README.md
├── planning/
│   ├── LD_brand_identity_v01.docx
│   └── LD_storyboard_final.pdf
├── references/
│   ├── LD_product_master_v01.png
│   └── LD_style_guide_v01.docx
├── assets/
│   ├── images/
│   │   ├── LD_S01_image_v01.png
│   │   ├── LD_S02_image_v01.png
│   │   ├── LD_S02_image_v02.png
│   │   ├── LD_S03_image_v01.png
│   │   └── LD_S04_image_v01.png
│   ├── videos/
│   │   ├── LD_S01_video_v01.mp4
│   │   ├── LD_S02_video_v01.mp4
│   │   ├── LD_S03_video_v01.mp4
│   │   └── LD_S04_video_v01.mp4
│   └── audio/
│       ├── LD_BGM_v01.wav
│       ├── LD_S02_canopen_v01.wav
│       └── LD_S03_voice_v01.wav
├── evidence/
│   ├── scene01_frame.png
│   ├── scene02_frame.png
│   ├── scene03_frame.png
│   ├── scene04_frame.png
│   └── video_metadata.png
└── final/
    ├── LD_brand_ad_final.mp4
    ├── LD_brand_ad_vertical_v02.mp4
    └── LUMIDROP_AI_광고_스토리보드_보고서.pdf
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
## T2I와 I2V 방식 비교 및 선택 기준

### T2I — Text to Image

T2I는 텍스트 프롬프트를 입력하여 정지 이미지를 생성하는 방식이다.

장점:
- 제품 디자인, 배경, 색상, 조명, 구도를 세밀하게 설계할 수 있다.
- 영상 생성보다 상대적으로 비용과 생성 시간이 적게 든다.
- 여러 후보를 비교한 뒤 가장 적합한 이미지를 선택할 수 있다.

단점:
- 결과물에 움직임이 없다.
- 같은 제품을 여러 번 생성하면 형태와 로고가 달라질 수 있다.
- 프롬프트만으로는 씬 간 제품 일관성을 완벽하게 유지하기 어렵다.

본 프로젝트에서는 ChatGPT Images를 이용해 제품 마스터 이미지와
씬 1~4의 키프레임 이미지를 먼저 제작하였다.

모든 씬에 동일한 제품 마스터 이미지를 레퍼런스로 제공하여
제품의 색상, 형태, 심벌과 비율을 최대한 동일하게 유지하였다.

### I2V — Image to Video

I2V는 완성된 정지 이미지를 입력하고,
카메라 움직임이나 피사체의 움직임을 추가하여 영상으로 변환하는 방식이다.

장점:
- 입력 이미지의 제품 디자인과 구도를 유지하기 쉽다.
- 원하는 장면을 먼저 이미지로 검수한 뒤 영상화할 수 있다.
- 텍스트만으로 영상을 생성하는 방식보다 제품 형태 변형 위험을 줄일 수 있다.

단점:
- 움직임이 클 경우 제품 형태나 로고가 변형될 수 있다.
- 생성 비용과 대기 시간이 이미지 생성보다 크다.
- 복잡한 회전, 손의 동작, 큰 물리 변화는 오류가 발생하기 쉽다.

본 프로젝트에서는 Google Flow의 이미지→영상 기능을 사용하였다.

각 씬의 이미지가 확정된 후에만 영상 생성을 진행했고,
제품 자체를 크게 움직이기보다 다음 요소에만 제한적으로 모션을 부여하였다.

- 느린 카메라 줌
- 청록색 조명의 확산
- 기포와 물방울의 움직임
- 원형 배경 빛의 펄스

### 본 프로젝트의 선택 기준

본 프로젝트는 가상의 음료 제품을 씬마다 동일하게 보여주는 것이 중요했기 때문에
텍스트만으로 영상을 바로 생성하지 않았다.

먼저 T2I로 제품과 배경을 확정하고,
그 이미지를 I2V로 변환하는 방식을 선택하였다.

선택 이유는 다음과 같다.

1. 제품 디자인과 브랜드 색상의 일관성 확보
2. 영상 생성 전에 구도와 조명을 미리 검수
3. 실패 가능성이 높은 영상 재생성 횟수 감소
4. 영상 생성 크레딧과 대기 시간 절약
5. 씬별 수정 사항을 이미지 단계에서 먼저 해결 가능

따라서 본 프로젝트의 제작 전략은 다음과 같다.

`T2I로 키프레임 확정 → 이미지 검수 → I2V로 필요한 움직임만 추가`

이 방식은 화려한 움직임보다 제품 일관성과 브랜드 메시지 전달을 우선한 선택이다.
## 도구 선택 우선순위와 비교 기준

### 프로젝트 우선순위

본 프로젝트의 도구 선택 우선순위는 다음과 같다.

1. 제품 형태와 브랜드 스타일의 일관성
2. 최종 결과물의 시각·청각 품질
3. 생성 실패율과 수정 편의성
4. 생성 속도
5. 크레딧 및 비용

10초 광고는 짧지만 모든 씬에서 동일한 제품을 보여줘야 하므로,
단순히 빠르고 저렴한 도구보다 제품 디자인을 안정적으로 유지할 수 있는
워크플로를 우선하였다.

비용 절감은 저품질 도구를 선택하는 방식이 아니라,
이미지 단계에서 충분히 검수한 후 필요한 결과만 영상화하는 방식으로 해결하였다.

### 도구 선택 판단 기준

| 평가 기준 | 확인 내용 |
|---|---|
| 품질 | 제품 형태, 색상, 심벌, 재질과 조명이 의도대로 표현되는가 |
| 일관성 | 이전 씬과 비교했을 때 제품 디자인과 화면 톤이 유지되는가 |
| 속도 | 생성 및 재생성에 필요한 대기 시간이 과도하지 않은가 |
| 비용 | 한 장면을 완성하기 위한 생성 횟수와 크레딧 소비가 적절한가 |
| 수정 편의성 | 특정 요소만 수정하거나 이전 결과를 레퍼런스로 재사용할 수 있는가 |
| 접근성 | 대기열, 사용량 제한 또는 플랜 문제 발생 시 대체가 가능한가 |

## 실제 사용 도구와 선택 이유

| 제작 영역 | 최종 사용 도구 | 선택 이유 | 우선한 기준 |
|---|---|---|---|
| 이미지 생성 | ChatGPT Images | 대화형 수정과 제품 레퍼런스 재사용이 편리함 | 일관성·수정 편의성 |
| 영상 생성 | Google Flow | 확정된 키프레임을 이미지→영상 방식으로 변환 가능 | 품질·모션 자연스러움 |
| 음성·효과음 | ElevenLabs | 음성, 캔 개봉음 등 서로 다른 오디오를 한 환경에서 제작 가능 | 음질·접근성 |
| 통합 편집 | CapCut | 짧은 광고의 컷, 자막, 볼륨과 화면 비율을 빠르게 조정 가능 | 속도·수정 편의성 |

## 대체 도구별 예상 비교

아래 평가는 동일한 프롬프트와 레퍼런스를 사용해 재제작할 경우를 가정한
프로젝트 관점의 예상 비교이다.

플랜, 대기열, 사용 지역과 생성 설정에 따라 실제 결과는 달라질 수 있으므로
정확한 비용이나 생성 시간은 사용 시점에 별도로 확인해야 한다.

### 이미지 생성 도구 비교

| 도구 | 예상 품질 | 예상 속도 | 예상 비용 부담 | 장점 | 주의점 |
|---|---|---|---|---|---|
| ChatGPT Images | 높음 | 보통 | 보통 | 대화형 수정과 레퍼런스 기반 반복 작업이 쉬움 | 복잡한 제품 글자와 로고는 변형될 수 있음 |
| Midjourney | 높음 | 보통 | 보통 | 시네마틱한 질감과 스타일 표현에 강점 | 정확한 제품 구조 수정에는 반복 생성이 필요할 수 있음 |
| Adobe Firefly | 보통~높음 | 보통 | 보통 | 이미지 수정과 Adobe 작업 환경 연결이 편리함 | 모델과 설정에 따라 결과 스타일 차이가 발생 |
| 로컬 생성 도구 | 설정에 따라 다름 | 초기 설정은 느림 | 장기적으로 낮을 수 있음 | 세부 제어와 반복 생성 가능 | 설치, 모델, 하드웨어 지식이 필요함 |

### 영상 생성 도구 비교

| 도구 | 예상 품질 | 예상 속도 | 예상 비용 부담 | 장점 | 주의점 |
|---|---|---|---|---|---|
| Google Flow | 높음 | 보통~느림 | 보통~높음 | 이미지 기반 시네마틱 모션과 장면 연출에 적합 | 대기열과 사용량 제한 가능 |
| Kling | 높음 | 보통~느림 | 보통~높음 | 물체와 카메라 움직임 표현에 대안이 될 수 있음 | 생성 시간이 길거나 형태가 변할 수 있음 |
| Pika | 보통~높음 | 빠름~보통 | 보통 | 짧은 효과 영상과 빠른 실험에 적합 | 제품 광고에서는 효과가 과장될 수 있음 |
| 정지 이미지+CapCut 모션 | 보통 | 빠름 | 낮음 | 크레딧 없이 패닝·줌으로 안정적인 영상 제작 가능 | 생성형 영상 특유의 자연스러운 움직임은 제한됨 |

### 오디오 생성 도구 비교

| 도구 | 예상 품질 | 예상 속도 | 예상 비용 부담 | 장점 | 주의점 |
|---|---|---|---|---|---|
| ElevenLabs | 높음 | 빠름 | 보통 | 자연스러운 음성과 효과음 제작 가능 | 선택한 음성에 따라 한국어 억양 차이 발생 |
| Suno | 음악 품질 높음 | 보통 | 보통 | 짧은 브랜드 음악 후보를 다양하게 생성 가능 | 원하는 길이와 전개를 정확히 맞추기 어려울 수 있음 |
| CapCut TTS | 보통 | 빠름 | 낮음 | 편집 중 바로 음성을 생성할 수 있음 | 광고 음성의 감정과 개성 표현이 제한될 수 있음 |

## 최종 의사결정

본 프로젝트는 속도와 비용만을 최우선으로 선택하지 않았다.

음료 캔의 형태와 색상이 씬마다 달라질 경우 브랜드 광고의 신뢰도가 떨어지므로,
제품 일관성과 최종 품질을 가장 중요한 기준으로 설정하였다.

따라서 다음과 같은 결정을 내렸다.

- 이미지는 수정과 레퍼런스 재사용이 쉬운 ChatGPT Images를 사용하였다.
- 영상은 확정된 이미지를 Google Flow로 변환하여 제품 변형 위험을 줄였다.
- 오디오는 ElevenLabs로 통일하여 음성·효과음의 품질 차이를 줄였다.
- 크레딧 절감을 위해 모든 후보를 영상화하지 않고 최종 이미지 한 장만 영상화하였다.

### 비용·시간 기록 방법

실제 제작 시 다음 항목을 기록하면 도구 비교의 객관성을 높일 수 있다.

| 기록 항목 | 실제 값 |
|---|---|
| 이미지 후보 생성 횟수 | 직접 입력 |
| 씬별 영상 생성 횟수 | 직접 입력 |
| 가장 많은 수정이 필요했던 씬 | 직접 입력 |
| 전체 영상 생성 대기 시간 | 직접 입력 |
| 사용한 크레딧 또는 플랜 | 확인 가능한 경우 입력 |
| 최종 선택 도구 | ChatGPT Images / Google Flow / ElevenLabs |
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
