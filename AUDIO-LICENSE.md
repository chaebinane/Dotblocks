# DOT BLOCKS Audio License

`audio-engine.js`에 포함된 절차형 배경음악 시퀀스와 효과음 합성 코드는 DOT BLOCKS를 위해 새로 작성되었습니다.

- 라이선스: CC0 1.0 Universal
- 외부 MP3/WAV/샘플: 없음
- 상업적 이용: 가능
- 수정/재배포: 가능
- 저작자 표시: 요구하지 않음

SPDX identifier: `CC0-1.0`

## 배경음악 스타일별 출처

### 기본 (앰비언트)

DOT BLOCKS를 위해 처음부터 작성한 창작 절차형 시퀀스입니다. 원곡·편곡 모두 자체 제작.

### 코로베이니키 (러시아 민요, 1861)

니콜라이 네크라소프의 시에 붙은 **1861년 러시아 민요**입니다. 저작권 보호 기간이 만료되어
**전 세계적으로 퍼블릭 도메인**입니다. 흔히 "테트리스 음악"으로 알려진 선율의 원곡입니다.

### 칼린카 (Калинка / Kalinka, 1860)

**이반 라리오노프**가 1860년에 작곡했습니다. 라리오노프는 1889년에 사망했으므로 사후 70년을
훨씬 넘겨 **전 세계적으로 퍼블릭 도메인**입니다. 후렴부 선율만 사용합니다.

### 설탕요정의 춤 (Dance of the Sugar Plum Fairy, 1892)

**표트르 일리치 차이콥스키**의 발레 「호두까기 인형」 중 한 곡입니다. 차이콥스키는 1893년에
사망했으므로 **전 세계적으로 퍼블릭 도메인**입니다. 도입부 첼레스타 선율만 사용합니다.

### 세 곡 공통

`audio-engine.js`의 `TUNES` 객체는 각 곡의 전통 선율(음정과 박자)만을 담고 있으며,
그 주변의 **편곡 — 성부 구성, 베이스 라인, 퍼커션, 스테레오 배치, 템포·위험도 반응 로직 — 은
DOT BLOCKS를 위해 처음부터 작성한 창작물**로 이 파일의 나머지 코드와 함께 CC0로 배포됩니다.

**중요**: 이 편곡들은 특정 상용 게임의 사운드트랙이나 저작권이 있는 편곡을 채보하거나 복제한 것이
아닙니다. 퍼블릭 도메인 선율을 자체 절차형 합성 엔진으로 독자 편곡한 결과물입니다.

**저작권과 상표는 별개입니다.** 위 선율들은 저작권이 소멸해 자유롭게 사용할 수 있지만, 상표는
별도의 문제입니다. 아래 항목을 참고하세요. 이 문서는 법률 자문이 아니며, 상업 배포 전에는
법무 검토를 권합니다.

「테트리스(Tetris)」는 The Tetris Company의 등록 상표이며, 본 프로젝트는 해당 상표와 무관하고
어떠한 제휴 관계도 없습니다. 게임명·마케팅·UI 문구에 해당 상표를 사용하지 않습니다.

---

The procedural music sequences and synthesized earcons in `audio-engine.js` are dedicated to the
public domain under CC0 1.0 Universal. No third-party samples or recorded music assets are bundled.

Three melody presets are included, all in the **public domain worldwide**:

- **"Korobeiniki"** — Russian folk song published in **1861**.
- **"Kalinka"** — Ivan Larionov, **1860** (Larionov died 1889).
- **"Dance of the Sugar Plum Fairy"** from The Nutcracker — Pyotr Ilyich Tchaikovsky, **1892**
  (Tchaikovsky died 1893).

Only the traditional melody lines are used; the surrounding arrangements (voicing, bass, percussion,
panning, tempo and danger response) were written from scratch for DOT BLOCKS and are released under
CC0. They are **not** transcribed from, and do not reproduce, any commercial game soundtrack or
copyrighted arrangement of these melodies.

Copyright and trademark are separate matters, and this document is not legal advice.

"Tetris" is a registered trademark of The Tetris Company. This project is not affiliated with or
endorsed by them, and does not use the mark in its name, marketing, or interface copy.
