# DOT BLOCKS — 히어로 배너 · 카드 썸네일 생성 프롬프트

나노바나나(Gemini 이미지 모델)용. **이미지에 텍스트를 넣지 않고**, 게임명·설명이 올라갈 여백을
비워두는 방향입니다. `UI-ASSET-GUIDE.md`의 "게임명·설명·버튼은 HTML/CSS" 원칙과 맞고, 다국어와
스크린리더·확대 대응에도 유리합니다.

---

## 0. 먼저 알아둘 것

### 팔레트 (게임 코드에서 그대로 가져온 값)

| 용도 | HEX | 비고 |
|---|---|---|
| 배경 | `#0A0C0F` | 보드 배경, 거의 검정 |
| 패널 | `#151A22` | 설정·카드 표면 |
| 올라온 핀 / 텍스트 | `#D8DEE7` · `#F5F7FA` | 차가운 밝은 회색 |
| 강조 | `#FF5B22` | 따뜻한 주황. 브랜드 색 |
| 포커스 | `#FFC928` | 노랑. 아주 조금만 |
| 위험 | `#FF5D6C` | 붉은 산호색. 아주 조금만 |

### 반드시 지킬 형태

- 닷패드는 **세로로 세운** 상태입니다. 가로로 눕히면 안 됩니다
- 촉각 화면은 **작고 동그란 핀이 촘촘한 격자**입니다. LED·픽셀·LCD가 아닙니다
- 올라온 핀만 빛을 받고, 내려간 핀은 면과 거의 평평합니다 — 이 **높이 차이**가 핵심입니다
- 블록은 **빈틈 없이 꽉 찬 덩어리**입니다 (게임의 실제 촉각 표현과 일치)
- 촉각 화면 아래에 **점자 표시줄 한 줄**이 따로 있습니다
- 기기 하단에 **기능키 4개와 좌우 패닝 키**가 있습니다

### 반드시 피할 것

- **"Tetris"라는 단어, 그 로고 서체, 그 브랜드의 무지개색 블록 팔레트** — 상표 문제입니다.
  블록은 위 팔레트의 회색과 주황만 씁니다
- 화면을 **눈으로 응시하는 인물** — 이 게임은 시각장애인이 주 사용자입니다. 사람이 등장한다면
  손끝으로 읽는 손이어야 합니다
- 이미지에 박힌 글자·로고·UI 목업
- 과한 네온, 사이버펑크, 렌즈 플레어

---

## 1. 히어로 배너 — 제품샷 (메인 추천)

가로로 긴 배너. **왼쪽 1/3을 비워** 게임명과 설명을 얹습니다.

> A cinematic low-key product photograph of a slim matte-black tactile braille
> display standing upright in portrait orientation on a dark matte surface. Its
> face is a dense, evenly spaced grid of tiny round physical pins. A group of
> pins near the middle is raised, forming three solid, gap-free geometric block
> shapes — an L shape, an S shape and a square — that read as one continuous
> raised mass; the surrounding pins sit flush and read as soft cool-grey dots.
> Below the pin area sits a separate single row of braille cells, and along the
> bottom edge of the device are four small physical function keys. A single hand
> enters from the right edge of the frame, fingertips resting lightly on the
> raised pins, reading them by touch, eyes not present in frame. Lighting is soft
> and directional from the upper right, with deep falloff into shadow and a
> narrow warm orange rim light (#FF5B22) tracing the right edge of the device and
> catching the tops of the raised pins. Background is a near-black gradient
> (#0A0C0F) with a very faint dot texture, completely empty and unobstructed
> across the entire left third of the frame. Palette limited to near-black, cool
> light grey (#D8DEE7) and a single warm orange accent. Photorealistic, shallow
> depth of field, 50mm lens, no text, no logos, no on-screen graphics.

**비율**: 16:9 또는 21:9 (플랫폼 규격에 맞추세요)
**여백**: 왼쪽 1/3

---

## 2. 히어로 배너 — 추상 그래픽 (대안)

제품이 아직 확정 노출이 곤란하거나 더 그래픽한 톤을 원할 때.

> A wide flat graphic poster composition on a near-black background (#0A0C0F). The
> entire canvas is covered by a precise grid of small circular dots in cool grey,
> most of them dim and flat at low opacity, like a field of lowered pins. Toward
> the right side, a subset of these dots is "raised" — rendered noticeably larger
> and brighter with soft contact shadows beneath them — and they cluster into
> three interlocking tetromino silhouettes with no gaps inside each shape: an L,
> an S and a 2x2 square. One shape is filled in warm orange (#FF5B22) while the
> others stay in light grey (#D8DEE7). A single thin horizontal line of raised
> dots runs beneath the shapes, suggesting a landing guide. Beneath everything, a
> separate short row of small braille dot cells. Clean, geometric, generous
> spacing, minimal Swiss poster sensibility, subtle soft shadows giving the dots
> real physical height. The left third of the composition is completely empty
> near-black space. No text, no logos, no gradients other than a faint vignette.

**비율**: 16:9 또는 21:9
**여백**: 왼쪽 1/3

---

## 3. 카드 썸네일 — 추상 그래픽 (메인 추천)

작게 표시되므로 요소를 줄이고 대비를 키웁니다. **하단 1/4을 비워** 제목 줄을 얹습니다.

> A bold, simple square graphic icon on a near-black background (#0A0C0F). A tight
> grid of small circular dots fills the frame; most sit dim and flat, while a
> centered cluster is raised — larger, brighter circles with soft contact shadows
> — forming two interlocking gap-free block shapes, an L and a square, seen
> straight on. The L shape is warm orange (#FF5B22), the square is cool light grey
> (#D8DEE7). The raised dots have visible physical height and a soft highlight on
> top, so the shapes read as something you could feel with a fingertip. Strong
> figure-ground contrast, thick forms, very few elements so it stays legible at
> small size. The bottom quarter of the frame is empty near-black space. Flat
> vector-like rendering with subtle depth, centered composition, no text, no
> logos, no outlines.

**비율**: 1:1 또는 16:9 (플랫폼 카드 규격에 맞추세요)
**여백**: 하단 1/4

---

## 4. 카드 썸네일 — 제품샷 (대안)

배너와 톤을 통일하고 싶을 때. 기기를 가까이 잡아 촉감이 보이게 합니다.

> A tight macro product photograph of the upper portion of a slim matte-black
> tactile braille display standing upright, shot slightly from above at an angle
> so the physical height of the pins is clearly visible. A dense grid of tiny
> round pins covers the surface; a cluster of them is raised into one solid
> gap-free block shape, catching a warm orange rim light (#FF5B22) along their
> tops, while the lowered pins around them stay flat and cool grey. Extremely
> shallow depth of field with the raised cluster in sharp focus and the rest
> falling into soft near-black. Low-key studio lighting, single soft key from the
> upper left. Background is empty near-black. Palette limited to near-black, cool
> light grey and one warm orange accent. Photorealistic, tactile, no text, no
> logos.

**비율**: 1:1 또는 16:9
**여백**: 하단 1/4

---

## 5. 결과물 체크리스트

생성된 이미지를 아래로 걸러내세요. 나노바나나는 몇 번 돌려 고르는 편이 빠릅니다.

- [ ] 닷패드가 **세로**로 서 있는가
- [ ] 촉각면이 **동그란 핀 격자**인가 (LCD·픽셀·LED가 아님)
- [ ] 블록이 **빈틈 없이 꽉 찬 덩어리**인가 (테두리만 있거나 성기지 않은가)
- [ ] 올라온 핀과 내려간 핀의 **높이 차이**가 보이는가
- [ ] 색이 **검정·회색·주황**으로 절제되어 있는가 (무지개색 블록이 아닌가)
- [ ] 텍스트를 올릴 **여백**이 실제로 비어 있는가
- [ ] 글자·로고가 섞여 들어오지 않았는가
- [ ] 사람이 있다면 **손끝으로 읽는 손**인가

---

## 6. 팁

**참고 이미지를 같이 넣으세요.** 나노바나나는 이미지 입력을 받습니다. 저장소의
`assets/board-frame.webp`(실제 닷패드 베젤 아트워크)와 `previews/intro-desktop.png`(인트로 화면)을
함께 넣고 *"match the device shape and color palette of the reference image"* 를 덧붙이면 제품
형태와 톤이 훨씬 안정적으로 나옵니다.

**여백은 프롬프트만으로 잘 안 지켜집니다.** "left third completely empty"를 넣어도 채워 오는
경우가 많습니다. 넓게 뽑아 크롭하거나, 생성 후 후속 지시로 *"remove everything from the left third
and extend the dark background"* 처럼 한 번 더 수정하는 편이 확실합니다.

**한 번에 하나씩 고치세요.** 결과가 아쉬우면 프롬프트를 통째로 다시 쓰기보다
*"make the pins rounder and increase the height difference between raised and lowered pins"* 처럼
한 가지씩 후속 지시를 주는 쪽이 잘 먹습니다.

**최종 파일은 WebP로.** 저장소의 다른 에셋과 같은 형식입니다. 배너는 `assets/`에 두고
카드 썸네일은 플랫폼 규격에 맞춰 별도 관리하세요.
