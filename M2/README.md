# LUMIDROP AI 기반 멀티모달 브랜드 광고

> **핵심 메시지:** 한 모금, 분위기 전환.  
> **과제:** GenAI 기초 2 — 멀티모달 콘텐츠 제작  
> **제작자:** 안소연  
> **제출일:** 2026.07.13.

---

## 1. 프로젝트 개요

가상의 스파클링 워터 브랜드 **LUMIDROP**을 선정하고, 무채색의 반복되는 일상이 제품을 여는 순간 청량한 분위기로 전환되는 짧은 브랜드 광고를 제작하였다.

기획, 이미지 생성, 이미지→영상 변환, 음성·효과음·음악 생성, 통합 편집의 전체 파이프라인을 생성형 AI 중심으로 설계하였다.

### 최종 산출물

- 스토리보드 PDF
- 광고 영상 MP4
- 기획 타임라인: 약 9.5초
- 최종 영상 길이: 약 9.04초
- 목표 해상도: 1920×1080
- 프레임레이트: 30fps
- 비디오 코덱: H.264
- 오디오 코덱: AAC

### 서사 구조

`문제 제시 → 변화 시작 → 제품 가치 → 브랜드 엔드 카드`

---

## 2. 브랜드 아이덴티티

| 항목 | 내용 |
|---|---|
| 브랜드명 | LUMIDROP |
| 제품 | 일상에서 간편하게 즐길 수 있는 기분 전환용 스파클링 워터 |
| 주요 타깃 | 공부나 업무로 피로와 지루함을 느끼는 20~30대 |
| 고객 문제 | 반복되는 공부와 업무로 집중력과 기분이 떨어지고, 일상에 새로운 자극이 필요함 |
| 브랜드 가치 | 음료를 마시는 짧은 순간을 청량하고 감각적인 기분 전환 경험으로 전환 |
| USP | 제품을 여는 순간 무채색 공간이 청량한 색과 빛으로 변화하는 브랜드 경험 |
| 톤앤매너 | 청량함, 미니멀, 미래적, 밝고 세련된 프리미엄 스타일 |
| 메인 색상 | 청록색 |
| 보조 색상 | 코럴 오렌지 |
| 캠페인 목표 | 직접 구매 전환보다 브랜드 인지도와 청량한 이미지 형성 |
| 핵심 메시지 | 한 모금, 분위기 전환. |
| CTA | 지금, 분위기를 바꿔보세요. |

### 브랜드 한 문장 정의

> LUMIDROP은 반복되는 일상에 청량하고 감각적인 변화를 제공하는 스파클링 워터 브랜드다.

### 비주얼 스타일 기준

| 구분 | 기준 |
|---|---|
| 제품 | 슬림한 원통형 캔, 매트 청록색 알루미늄, 작은 코럴 포인트, 물방울 심벌 |
| 구도 | 제품을 중앙에 배치하고 전체가 잘리지 않도록 구성 |
| 조명 | 변화 전에는 어둡고 낮은 채도, 변화 후에는 밝은 림라이트와 청록색 글로우 |
| 움직임 | 제품 변형을 피하고 카메라·빛·기포 중심으로 작게 움직임 |
| 금지 요소 | 사람, 손, 여러 제품, 읽을 수 없는 글자, 과도한 폭발·스플래시 |

---

## 3. 제작 파이프라인 및 사용 도구

`기획 → 기준 이미지 → 씬별 이미지 → 영상 변환 → 오디오 → 통합·출력`

| 구분 | 도구 | 선택 목적 |
|---|---|---|
| 기획·프롬프트 | ChatGPT | 브랜드 정의, 4씬 구조, 프롬프트 작성, 문제 원인 분석과 수정 이유 정리 |
| 이미지 생성 | ChatGPT Images | 대화형 수정과 기준 이미지 참조를 통해 제품·화풍의 일관성 유지 |
| 비디오 생성 | Google Flow | 완성된 키프레임에 카메라, 빛, 기포 등 필요한 움직임 추가 |
| 음성·효과음·음악 | ElevenLabs | 짧은 한국어 내레이션, 캔 개봉 효과음, 브랜드 음악 생성 |
| 통합 편집 | CapCut | 컷 길이, 자막, 장면 전환, 오디오 레벨, 인코딩 스펙 조정 |
| 보고서 제작 | Canva / Word | 스토리보드 표와 이미지를 배치하고 PDF로 출력 |

### 현실적 제작 전략

- **크레딧 절약:** 이미지를 먼저 확정한 후 영상화하고, 각 씬의 영상 생성은 최대 2회로 제한
- **일관성 유지:** 모든 씬에 동일한 제품 마스터 이미지를 첨부하고 형태·색상·심벌을 반복 고정
- **변형 방지:** 제품은 거의 고정하고 빛, 기포, 배경, 카메라에만 움직임 부여
- **텍스트 안정성:** 브랜드명과 슬로건은 생성 이미지에 넣지 않고 CapCut에서 직접 입력
- **대체 전략:** 영상 생성이 제한되면 정지 이미지에 패닝·줌을 적용하고, 오디오는 CapCut TTS로 대체

---

## 4. 씬별 스토리보드

### Scene 1 — 반복되는 일상

- **구간:** 0.0초~2.0초
- **목표 메시지:** 반복되는 공부와 업무로 일상이 무채색처럼 느껴지는 상황을 보여준다.
- **화면 구성:** 어두운 회색 책상 중앙에 제품 1개를 배치한다. 배경은 단순한 작업 공간이며 낮은 채도와 부드러운 어두운 조명을 사용한다. 사람과 손은 등장하지 않는다.
- **화면 카피:** 오늘도 똑같다면?
- **내레이션:** 사용하지 않음

#### 사용 도구 및 목적

| 구분 | 도구 | 목적 |
|---|---|---|
| 이미지 | ChatGPT Images | 무채색 작업 공간과 제품이 등장하는 첫 번째 기준 화면 제작 |
| 비디오 | Google Flow | 정지 이미지에 아주 느린 카메라 줌인 추가 |
| 오디오 | ElevenLabs | 조용한 실내 분위기와 낮은 전자음 생성 |

#### 이미지 생성 프롬프트

```text
Use the uploaded LUMIDROP product image as the exact product reference.
Create scene 1 of a premium cinematic beverage advertisement.
Place the same LUMIDROP can at the center of a dark gray office desk
in a minimal modern workspace.

The scene should feel repetitive, quiet and slightly tiring:
muted monochrome gray colors, low saturation, soft dim lighting,
subtle natural shadow, a clean desk with very few background objects,
slightly top-down camera angle, realistic commercial product photography,
16:9 horizontal composition.

Keep the can design exactly consistent with the reference:
same slim cylindrical shape, matte turquoise body, coral accent,
water-drop symbol, proportions and material.

Do not redesign the product.
Do not add any readable text.
No person, no hand, no extra can, no product deformation,
no logo distortion, no dramatic special effects.
```

#### 비디오 변환 프롬프트

```text
The product can remains completely still and keeps its original shape.
The camera performs a very slow and smooth push-in toward the product.
The dim office lighting changes only slightly,
creating a quiet and repetitive mood.
Subtle realistic ambient movement in the background.
Premium cinematic product advertisement, controlled minimal motion.

No camera shake, no fast movement, no product rotation,
no product deformation, no logo change, no additional objects.
```

#### 오디오 생성 프롬프트

```text
Quiet modern office ambience with a very soft low electronic hum,
subtle and restrained, no voice, no sudden sound,
approximately 2 seconds.
```

#### 결과

- **출력 요약:** 무채색 작업 공간과 중앙 제품을 통해 반복적이고 지루한 일상의 분위기를 표현
- **이미지:** `LD_S01_image_v01.png`
- **영상:** `LD_S01_video_v01.mp4`
- **오디오:** `LD_BGM_v01.mp3`

---

### Scene 2 — 변화의 시작

- **구간:** 2.0초~4.2초
- **목표 메시지:** 제품이 열리는 순간 무채색의 일상이 청량한 분위기로 변화하기 시작한다.
- **화면 구성:** 씬 1과 같은 제품과 구도를 유지한다. 왼쪽은 어두운 회색으로 남기고 오른쪽부터 청록색 빛이 번지도록 한다. 제품 주변에는 소수의 기포와 미세 입자를 배치한다.
- **화면 카피:** 사용하지 않음
- **내레이션:** 사용하지 않음

#### 사용 도구 및 목적

| 구분 | 도구 | 목적 |
|---|---|---|
| 이미지 | ChatGPT Images | 동일 제품과 구도를 유지하며 회색→청록 전환 장면 제작 |
| 비디오 | Google Flow | 제품은 고정하고 청록색 빛과 기포만 부드럽게 움직임 |
| 오디오 | ElevenLabs | 캔 개봉음과 짧은 탄산 효과음 생성 |

#### 이미지 생성 프롬프트

```text
Use the uploaded product master image as the exact product reference.
Improve the uploaded scene 2 image while keeping its overall composition.
Keep the LUMIDROP can in exactly the same position, size and camera angle.

Make the transition effect more controlled and suitable for a premium
beverage advertisement:

- reduce the number of bubbles and particles by approximately 50 percent
- keep all particles away from the front label and water-drop symbol
- soften the turquoise light spreading from the right side
- maintain the dark gray atmosphere on the left side
- create a clear and gradual transition from gray to turquoise
- improve the realistic matte aluminum texture of the can
- keep the background minimal and uncluttered
- 16:9 horizontal composition

Preserve the exact slim can shape, turquoise color, coral accent,
water-drop symbol, proportions and material from the product reference.

No person, no hand, no extra can, no readable text, no splash,
no explosion, no product deformation, no logo distortion.
```

#### 비디오 변환 프롬프트

```text
The LUMIDROP can remains perfectly rigid, centered and unchanged.
A soft turquoise light slowly spreads from the right side
toward the left side of the background.

A small number of sparkling bubbles and fine particles gently rise
around the can without covering the front symbol.

The gray atmosphere gradually transitions into a refreshing turquoise mood.
The camera remains almost stationary with only a very subtle forward movement.

Premium minimal beverage advertisement, smooth and controlled motion.

No explosion, no large splash, no fast movement, no camera shake,
no product rotation, no product deformation, no logo change,
no additional objects.
```

#### 오디오 생성 프롬프트

```text
A clean premium aluminum beverage can opening sound,
a sharp metallic click followed by a short refreshing sparkling fizz,
studio-recorded, crisp and realistic,
no music, no voice, no background noise,
approximately 1.2 seconds.
```

#### 결과

- **출력 요약:** 회색에서 청록색으로 변화하는 흐름과 캔 개봉 순간의 청량감을 표현했으며, 수정 후에는 입자 수를 줄여 제품 가독성을 높임
- **이미지:** `LD_S02_image_v02.png`
- **영상:** `LD_S02_video_v01.mp4`
- **효과음:** `LD_S02_canopen_v01.mp3`

---

### Scene 3 — 청량한 전환

- **구간:** 4.2초~7.0초
- **목표 메시지:** 한 모금이 지루한 일상을 밝고 청량한 순간으로 바꾼다는 제품 가치를 전달한다.
- **화면 구성:** 무채색 공간이 밝은 미래형 청록색 공간으로 완전히 변한다. 중앙 제품 뒤에 부드러운 원형 빛을 배치하고, 물방울과 작은 기포를 제품 주변에 제한적으로 배치한다.
- **화면 카피:** 사용하지 않음
- **내레이션:** 한 모금으로, 분위기를 바꿔.

#### 사용 도구 및 목적

| 구분 | 도구 | 목적 |
|---|---|---|
| 이미지 | ChatGPT Images | 밝고 청량하게 변화한 제품 중심의 핵심 광고 화면 제작 |
| 비디오 | Google Flow | 제품의 미세 회전, 기포·물방울·배경 빛의 움직임 추가 |
| 오디오 | ElevenLabs | 밝고 자신감 있는 한국어 광고 내레이션 제작 |

#### 이미지 생성 프롬프트

```text
Use the uploaded product master image as the exact product reference.
Use the uploaded scene 2 image as the visual continuity reference.

Create scene 3 of the same premium cinematic beverage advertisement.
Transform the background completely into a bright, clean
and futuristic turquoise environment.

Place the same LUMIDROP can prominently at the center of the frame.

Add a soft circular turquoise glow behind the can,
a few transparent water droplets floating around the product,
small sparkling carbonation bubbles,
subtle coral-orange light accents,
bright refreshing commercial lighting,
realistic matte aluminum reflections,
clean symmetrical composition,
16:9 horizontal format.

Keep the can design exactly consistent with the uploaded product reference.
The product must remain clearly visible and unobstructed.

No person, no hand, no extra can, no readable text,
no large splash, no explosion, no product deformation,
no logo distortion.
```

#### 비디오 변환 프롬프트

```text
The LUMIDROP can remains centered and keeps its exact original shape.
The product performs an extremely slow and subtle rotation
of only a few degrees.

Transparent water droplets and small carbonation bubbles
gently float upward around the can.

The soft circular turquoise light behind the product slowly pulses once.
The camera makes a very slight smooth arc movement
while keeping the product centered.

Fresh, clean and premium beverage advertising motion.

No fast rotation, no large splash, no camera shake,
no product deformation, no logo change, no additional product,
no objects covering the front of the can.
```

#### 오디오 생성 프롬프트

```text
Korean line: 한 모금으로, 분위기를 바꿔.
Read in a bright, refreshing and confident adult advertising voice.
Slight smile, clear pronunciation, medium-fast delivery,
no theatrical acting, approximately 1.8 to 2.3 seconds.
```

#### 결과

- **출력 요약:** 밝은 청록색 공간과 제한된 물방울·기포를 활용해 청량한 기분 전환과 제품 가치를 표현
- **이미지:** `LD_S03_image_v01.png`
- **영상:** `LD_S03_video_v01.mp4`
- **내레이션:** `LD_S03_voice_v01.mp3`

---

### Scene 4 — 브랜드 엔드 카드

- **구간:** 7.0초~9.5초
- **목표 메시지:** 광고 마지막에 브랜드명과 핵심 메시지를 분명히 보여주어 LUMIDROP을 기억하게 한다.
- **화면 구성:** 밝은 청록색 배경 중앙 상단에 제품을 정면 배치하고, 제품 아래에 브랜드명과 슬로건을 넣을 충분한 여백을 둔다. 이미지 생성 단계에서는 글자를 넣지 않고 CapCut에서 정확히 입력한다.
- **화면 카피:** LUMIDROP / 한 모금, 분위기 전환.
- **내레이션:** 사용하지 않음

#### 사용 도구 및 목적

| 구분 | 도구 | 목적 |
|---|---|---|
| 이미지 | ChatGPT Images | 브랜드 엔드 카드에 사용할 제품 중심의 깨끗한 최종 이미지 제작 |
| 비디오 | Google Flow | 제품은 고정하고 원형 배경 빛만 부드럽게 확산 |
| 오디오 | ElevenLabs | 음악 마지막의 짧은 브랜드 사운드 활용 |

#### 이미지 생성 프롬프트

```text
Use the uploaded product master image as the exact product reference.
Use the uploaded scene 3 image as the lighting and color reference.

Create the final end-card image for a premium LUMIDROP
beverage advertisement.

Place the same LUMIDROP can front-facing and perfectly centered
in the upper-middle area of the frame.

Use a bright clean turquoise background,
a soft circular turquoise glow behind the product,
subtle coral-orange accent lighting,
realistic matte aluminum reflections,
minimal premium commercial lighting,
a clean symmetrical composition,
generous empty space below the product for a brand name and slogan,
16:9 horizontal format.

Do not generate any brand name, slogan or readable text inside the image.
Keep the can design exactly consistent with the uploaded product reference.

No person, no hand, no extra can, no floating water droplets,
no bubbles, no splash, no readable text,
no product deformation, no logo distortion.
```

#### 비디오 변환 프롬프트

```text
The LUMIDROP can remains perfectly rigid, front-facing and centered.
The soft circular turquoise glow behind the product
slowly expands once and then settles.

A very subtle light reflection moves across the matte aluminum surface.
The camera remains completely still.

Clean, minimal and premium beverage advertisement end card.

No product movement, no product rotation, no camera movement,
no particles, no bubbles, no splash,
no product deformation, no logo change,
no additional objects, no generated text.
```

#### 오디오 생성 프롬프트

```text
A very short clean and refreshing electronic brand sting,
glassy synth tone with a soft final chime,
premium and memorable,
no voice, approximately 1 second.
```

#### 결과

- **출력 요약:** 제품과 브랜드명을 한눈에 인지할 수 있는 미니멀한 엔드 카드 구성
- **이미지:** `LD_S04_image_v01.png`
- **영상:** `LD_S04_video_v01.mp4`
- **브랜드 사운드:** `LD_S04_logo_sound_v01.mp3`

---

## 5. 프롬프트 수정 전·후 비교

### 개선 대상

Scene 2 — 변화의 시작

- **수정 전 이미지:** `LD_S02_image_v01.png`
- **수정 후 이미지:** `LD_S02_image_v02.png`

### 수정 전 문제

- 기포와 입자가 많아 제품 전면 심벌이 잘 보이지 않음
- 청록색 효과가 강해 미니멀한 프리미엄 광고보다 판타지 효과에 가까워짐

### 수정 내용

1. 기포와 입자 수를 약 50% 줄여 제품이 화면의 주인공으로 보이게 함
2. 입자가 제품 전면과 물방울 심벌을 가리지 않도록 위치 제한
3. 오른쪽에서 퍼지는 청록색 빛을 부드럽게 조정
4. 왼쪽 회색 영역 유지
5. 제품 위치, 크기, 카메라 각도를 유지하도록 반복 지시

### 결과 변화

제품의 가독성과 씬 간 연속성이 향상되었고, 회색에서 청록색으로 변하는 메시지가 더 명확해졌다.

### 핵심 판단

> “더 화려하게”가 아니라 “제품을 더 명확하게” 보이게 하는 방향으로 프롬프트를 구체화하였다. 추상적인 분위기 지시를 입자 수, 위치, 빛의 방향, 고정해야 할 요소로 세분화한 것이 개선의 핵심이다.

---

## 6. 통합 편집 및 최종 영상 구성

### 타임라인

| 씬 | 구간 | 길이 | 핵심 화면 | 오디오 |
|---|---:|---:|---|---|
| 1 | 0.0~2.0초 | 2.0초 | 무채색 작업 공간, “오늘도 똑같다면?” | 조용한 BGM |
| 2 | 2.0~4.2초 | 2.2초 | 청록색 빛이 번지는 전환 | 캔 개봉음 + BGM 상승 |
| 3 | 4.2~7.0초 | 2.8초 | 밝은 청록색 제품 가치 화면 | 내레이션 + 밝아진 BGM |
| 4 | 7.0~9.5초 | 2.5초 | 브랜드명·슬로건 엔드 카드 | 짧은 브랜드 마무리음 |

### 오디오 및 자막 편집

- 배경음악: 0초부터 영상 끝까지 배치
- 초기 볼륨: 20~30%
- 시작 페이드 인: 0.3초
- 마지막 페이드 아웃: 0.5초
- 캔 개봉음: 씬 2 시작인 2.0초에 배치
- 내레이션: 씬 3의 4.4초 부근에 시작하고 7.0초 이전 종료
- 내레이션 구간의 BGM: 10~20%로 낮춤
- 씬 1 카피: 0.3초~1.8초
- 엔드 카드: 7.2초부터 영상 종료까지
- 장면 전환: 각 씬 연결에 0.1~0.2초의 짧은 디졸브 사용

### 최종 영상 정보

| 항목 | 값 |
|---|---|
| 파일명 | `LD_brand_ad_final.mp4` |
| 영상 길이 | 약 9.04초 |
| 해상도 | 1920×1080 |
| 프레임레이트 | 30fps |
| 비디오 코덱 | H.264 |
| 오디오 코덱 | AAC |
| 편집 프로젝트 | `LD_capcut_project_v02` |

---

## 7. 문제 대응 및 대체 도구

### 멀티모달 제작 문제와 대응

| 문제 | 대응 |
|---|---|
| 제품·화풍 불일치 | 제품 마스터 이미지를 모든 씬에 첨부하고 형태, 색상, 심벌, 카메라를 반복 고정 |
| 영상 중 제품 변형 | 제품을 정지시키고 빛, 배경, 기포, 카메라만 작게 움직이도록 프롬프트 작성 |
| 해상도·비율 혼재 | 모든 이미지를 16:9로 생성하고 CapCut 프로젝트를 1920×1080, 30fps로 통일 |
| 오디오 톤 미스매치 | 청량함, 미래적, 미니멀이라는 공통 형용사를 음악·음성·효과음 프롬프트에 반복 |
| 생성 글자 오류 | AI 이미지 안에는 글자를 생성하지 않고 CapCut에서 브랜드명과 슬로건을 입력 |
| 크레딧·대기열 | 이미지를 완성한 후 영상화하고 씬당 최대 두 번만 생성 |

### 대체 도구

| 구분 | 대체 도구 | 활용 목적 |
|---|---|---|
| 이미지 | Midjourney | Style/Character Reference 활용 또는 시네마틱 화풍 강화 |
| 이미지 | Adobe Firefly | 이미지 수정과 영상 작업을 한 플랫폼에서 연결 |
| 비디오 | Runway | Google Flow 대기열 또는 크레딧 제한 시 이미지→영상 변환 |
| 오디오 | Suno | 음악 생성 또는 한국어 음성 생성 대체 |
| 편집 | DaVinci Resolve | 무료 환경에서 더 세밀한 색보정과 오디오 편집 |

---

## 8. 제작 회고

### 핵심 학습

좋은 결과는 도구를 많이 사용하는 데서 나오지 않았다.

먼저 브랜드 메시지와 4개의 씬 역할을 확정하고, 제품 마스터 이미지로 시각적 기준을 고정한 뒤, 각 영상 프롬프트에서 움직임을 한 가지씩만 지시한 것이 일관성과 완성도를 높였다.

### 추가 개선 가능성

- 동일한 Scene 2를 Kling 또는 Pika로 재제작하여 제품 형태 유지, 모션 자연스러움, 생성 속도와 크레딧 비교
- 9:16 버전은 단순 크롭보다 동일 레퍼런스를 활용해 세로형 키프레임을 별도로 생성

---

## 9. 제출 전 체크리스트

- [ ] 영상 길이가 10초 이내인지 확인
- [ ] 4개 씬의 이미지와 영상이 생성형 AI 결과물인지 확인
- [ ] 음성·효과음·배경음악 중 1개 이상 포함
- [ ] 문제 → 전환 → 가치 → 브랜드 구조가 보이는지 확인
- [ ] 마지막 구간에 브랜드명과 슬로건 표시
- [ ] 16:9, 1920×1080, 제품 형태와 색상 통일
- [ ] 내레이션이 BGM에 묻히지 않는지 확인
- [ ] 씬별 원문 프롬프트와 출력 결과 요약 포함
- [ ] Scene 2의 수정 전·후 이미지와 수정 이유 포함
- [ ] 모든 결과 파일명이 문서에 기록되어 있는지 확인
- [ ] 최종 PDF 준비
- [ ] 최종 MP4 준비

---

## 10. 최종 제출 파일

- `LUMIDROP_AI_광고_스토리보드_보고서.pdf`
- `LD_brand_ad_final.mp4`
