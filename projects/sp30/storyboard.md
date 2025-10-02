## 1. 콘텐츠 개요

- 콘텐츠 명: 해양안전 캠페인 AI 숏폼 영상 <보이지 않는 승무원 (레저활동 편)>

- 제작 목적: 최근 낚시 및 레저 선박 이용객 증가와 함께 관련 해양사고 또한 꾸준히 증가하는 추세입니다. 특히 수상레저 사고 사망자의 95%가 구명조끼를 착용하지 않는 등, 개인의 안전 불감증이 큰 문제로 지적되고 있습니다.

    본 영상은 해양 레저활동 이용객의 인식을 '안전의 수동적인 객체'에서 '안전의 능동적인 주체'로 전환시키는 것을 목표로 합니다. 선박의 안전을 선장이나 선원의 전유물로 여기는 기존의 시각에서 벗어나, **배에 오른 우리 모두가 서로의 안전을 지키는 '보이지 않는 승무원'**이라는 새로운 역할을 부여하고자 합니다.

    이를 통해 승객 스스로가 주변의 위험 요소를 점검하고, 구명조끼 착용과 같은 기본적인 안전 수칙을 '나와 모두를 위한 약속'으로 여기는 자발적인 해양안전 문화를 확산시키는 데 기여하고자 합니다.

- AI 활용 요약: 본 영상은 기획과 시나리오를 제외한 모든 시각적 요소를 100% AI 영상 생성을 통해 제작한 AI 네이티브 콘텐츠입니다.

    독창적 시각 스타일 구현: 딱딱한 안전 캠페인의 이미지를 탈피하고, 젊은 세대에게 소구력이 높은 '신카이 마코토' 스타일의 감성적인 아니메 비주얼을 AI로 구현했습니다. 이를 통해 시청자의 즉각적인 시선을 사로잡고 메시지에 대한 감성적 몰입도를 극대화했습니다.

    역동적이고 섬세한 연출: 낚싯줄이 감기는 릴의 회전, 물방울이 튀는 스피커의 진동, 라면이 끓어오르는 증기 등 실사 촬영으로는 포착하기 어려운 순간들을 AI를 통해 감각적이고 역동적인 영상으로 시각화했습니다. 또한, 실제로는 위험할 수 있는 버너 옆 부탄가스 방치와 같은 장면을 안전하게 연출했습니다.

    시네마틱 기법 적용: AI 프롬프트를 통해 로우 앵글 샷, 슬로우 모션, 카메라 패닝, 드론 샷 등 전문적인 시네마틱 기법을 적용하여 60초의 짧은 시간 동안 영상의 완성도와 주목도를 높였습니다.


## 2. 활용 AI 도구 및 기술

| 활용 분야 | 사용 AI 도구 | 기술 상세 |
| -- | -- | -- |
| 시나리오 생성 | Gemini 2.5 pro | 대화형 AI를 통해 캠페인 메시지를 효과적으로 전달하는 스토리 구성 |
| 이미지 생성 | Whisk (Imagen 3, Nano Banana) | 텍스트 프롬프트를 기반으로 특정 화풍의 고품질 이미지 생성 |
| 영상 변환 | Flow (Veo3-Fast) | 생성된 이미지를 바탕으로 생동감 있는 고품질 영상 클립 제작 |
| 음성 합성 | AI Studio (Gemini 2.5 Pro Previews TTS) | 텍스트(대본)를 자연스러운 목소리의 나레이션으로 변환 |

## 3. AI 기반 제작 과정
- 1단계: 기획 및 시나리오 구체화
    '보이지 않는 승무원'이라는 핵심 콘셉트를 바탕으로, Gemini 2.5 pro를 활용하여 60초 숏폼 영상에 최적화된 스토리라인과 장면별 나레이션 초안을 구성했습니다. AI와의 대화를 통해 안전 메시지를 감성적으로 전달할 수 있는 아이디어를 발전시켜 최종 시나리오를 완성했습니다.

- 2단계: AI를 활용한 비주얼 콘셉트 구현
    Whisk (Imagen 3, Nano Banana)를 사용하여 '신카이 마코토' 스타일의 감성적인 아니메 비주얼을 구현했습니다. 영상의 전체적인 톤앤매너를 결정하는 주요 장면들을 텍스트 프롬프트로 생성하여 시각적 콘셉트를 확립했습니다.

    **주요 프롬프트 예시:**

    ```
    A low angle shot of a fishing reel spinning in slow motion on a leisure boat, water droplets flying, Shinkai Makoto anime style, cinematic lighting, hyper-detailed.
    (레저 보트 위에서 슬로우 모션으로 회전하는 낚시 릴의 로우 앵글 샷, 물방울이 튀는 모습, 신카이 마코토 애니메이션 스타일, 영화적 조명, 초고화질)
    ```

- 3단계: AI 영상 생성 및 시네마틱 연출
    2단계에서 생성한 주요 이미지들을 Flow (Veo3-Fast)에 입력하여 역동적인 영상 클립으로 변환했습니다. (Image-to-Video) 낚싯줄의 움직임, 스피커의 진동, 증기 표현 등 실사 촬영의 한계를 넘어선 섬세한 연출을 구현했습니다. 또한, 로우 앵글, 슬로우 모션, 드론 샷 등의 시네마틱 기법을 프롬프트로 직접 제어하여 영상의 완성도를 높였습니다.

    **주요 프롬프트 예시:**

    ```
    Makoto Shinkai anime style. Extreme close-up shot. A silver fishing reel's spool **spins rapidly and continuously**, creating intense motion blur. The taut fishing line **is being pulled out** in a smooth, fast motion. Brilliant sunlight creates a beautiful, shimmering lens flare that **moves with the rotation**.
    ```

- 4단계: 최종 편집 및 사운드 디자인
    생성된 AI 영상 클립들을 시나리오의 흐름에 맞게 편집하고, AI Studio (Gemini 2.5 Pro Previews TTS)를 통해 나레이션을 녹음하여 삽입했습니다. 마지막으로, 영상의 몰입감을 극대화하기 위한 배경음악(BGM)과 효과음(SFX)을 추가하여 최종 콘텐츠를 완성했습니다.

---

## 스토리보드

## SCENE 1: 즐거움의 장비 (0-6초)
- ### CUT 1-1 (0-2초)

    - 영상: [Extreme Close Up] 낚싯줄이 팽팽하게 당겨지며 릴이 '파르륵' 소리를 내며 빠르게 돌아간다.

    - 음향: 신나고 역동적인 힙합 비트 BGM 시작. SFX(릴 돌아가는 소리).
```
image prompt

Makoto Shinkai anime style, anime screencap, key visual, extreme close-up, silver fishing reel, spinning fast, cinematic motion blur, glowing fishing line, brilliant sunlight, dramatic lens flare, vibrant colors, detailed anime background, bokeh ocean, sparkling water, masterpiece, 8k, --ar 9:16
```
[image output-whisk](./projects/sp30/images/s1-c1-1.jpeg)
```
movie prompt

Makoto Shinkai anime style. Extreme close-up shot. A silver fishing reel's spool **spins rapidly and continuously**, creating intense motion blur. The taut fishing line **is being pulled out** in a smooth, fast motion. Brilliant sunlight creates a beautiful, shimmering lens flare that **moves with the rotation**.
```

- ### CUT 1-2 (2-4초)

    - 영상: [Medium Shot] 보트 바닥에 놓인 블루투스 스피커가 비트에 맞춰 '쿵쿵' 울린다. 스피커 위로 물방울이 튀는 모습.

    - 음향: BGM의 베이스가 강조됨.
```
image prompt

Makoto Shinkai anime style, anime key visual. A medium shot of a sleek black Bluetooth speaker on a detailed wooden boat deck. The speaker is dynamically vibrating with bass as crystal clear water droplets splash around it. Brilliant sunlight creates beautiful specular highlights on the speaker and the glistening water. Vibrant anime colors, masterpiece, cinematic.
```
[image output-whisk](./images/s1-c1-2.jpeg)
```
movie prompt

Makoto Shinkai anime style. Medium shot. A sleek black Bluetooth speaker on a boat deck **visibly vibrates with the heavy bass** of a song. Crystal clear water droplets **splash up and fall in beautiful slow motion** around it, glistening in the sun.
```

- ### CUT 1-3 (4-6초)

    - 영상: [Close Up] 휴대용 버너 위에서 라면이 '보글보글' 맛있게 끓는다.

    - 음향: SFX(끓는 소리).

    - 자막:
```
#바다 #주말 #힐링
우리가 챙겨온 즐거움들
```
```
image prompt

Makoto Shinkai anime style, focusing on hyper-detailed anime food. An extreme close-up of delicious looking Korean ramen sizzling on a portable gas burner. Billowing, volumetric steam rises and catches the golden hour light, creating a dreamy, luminous effect. Vibrant colors and detailed reflections shimmer in the broth. Theatrical animation quality, masterpiece.
```
[image output-whisk](./images/s1-c1-3.jpeg)
```
movie prompt

Makoto Shinkai anime style. Extreme close-up on hyper-detailed anime food. A pot of ramen is **sizzling and bubbling vigorously** on a portable gas burner. Billowing, volumetric steam **rises and swirls dreamily**, catching the golden hour light.
```

## SCENE 2: 숨겨진 위험 (6-16초)
- ### CUT 2-1 (6-9초)

    - 영상: [Medium Shot] 카메라가 끓고 있는 버너에서 옆으로 천천히 이동(Pan)하면, 바로 옆에 예비 부탄가스가 놓여있는 위험한 모습이 보인다.

    - 음향: BGM 비트만 남고, '삐-'하는 불안한 노이즈 추가.
```
image prompt

Makoto Shinkai anime style, anime screencap with a tense atmosphere. On the deck of a gently rocking leisure boat, with the deep blue ocean visible in the background. A medium shot shows a portable gas burner, **on which a pot of delicious Korean ramen is boiling, with bubbling red broth and noodles visible.** The camera pans slightly to reveal a spare butane gas canister placed dangerously close to the open flame. High-contrast sunlight casts a dramatic shadow over the canister, creating a sense of unease amidst the vibrant colors of the sea and sky.
```
[image output-whisk](./images/s2-c2-1.jpeg)

```
movie prompt

Makoto Shinkai anime style, tense atmosphere. On the deck of a **gently rocking** leisure boat, the camera **slowly pans** from a pot of boiling Korean ramen to reveal a spare butane canister placed dangerously close to the open flame. The **gentle rocking motion** of the boat creates a subtle, uneasy movement in the frame.
```

- ### CUT 2-2 (9-12초)

    - 영상: [Top-down Shot] 바닥에 어지럽게 뒤엉킨 고프로 충전 케이블과 낚싯줄 위로 바닷물이 살짝 튀어 들어온다.

    - 음향: SFX(물 튀는 소리)가 날카롭게 들림.
```
image prompt

Makoto Shinkai anime style, key visual. A top-down shot of a chaotic tangle of black charging cables and colorful fishing lines on a wet boat deck. A dynamic splash of seawater is captured in high detail, with individual glistening droplets frozen in mid-air by the brilliant sunlight. Ultra-detailed, vibrant colors.
```
[image output-whisk](./images/s2-c2-2.jpeg)

```
movie prompt

Makoto Shinkai anime style. High-angle top-down shot. A fishing rod lies on the deck, its line tangled with charging cables. A dynamic splash of seawater **erupts near the tangle and is captured in cinematic slow motion**. Individual glistening droplets **hang suspended in the air for a moment** before hitting the deck.
```

- ### CUT 2-3 (12-16초)

    - 영상: [Close Up] 보트 운전석(스로틀 레버) 바로 옆에 마시다 만 술캔이 위태롭게 놓여 있다.

    - 자막: 하지만, 우리가 놓치고 있는 것들
```
image prompt

Makoto Shinkai anime style, anime screencap. An extreme close-up on a can of korean beer(TERRA), covered in hyper-detailed condensation droplets. The can is placed precariously next to a boat's throttle controls. Dramatic lighting creates a sharp specular highlight on the can, emphasizing it as a point of risk. Sense of impending danger.
```
[image output-whisk](./images/s2-c2-3.jpeg)

```
movie prompt

Makoto Shinkai anime style. Extreme close-up. A can of beer next to a boat's throttle. The boat **has a subtle, gentle sway**, causing light to shimmer across the metallic can. A single drop of condensation **slowly trickles down the side** of the can.
```

## SCENE 3: 진짜 필수 장비 (16-26초)
- ### CUT 3-1 (16-19초)

    - 영상: [Low Angle Shot] 한쪽에 단정하게 걸려있는 선명한 주황색 구명조끼. 마치 영웅처럼 듬직해 보인다. 

    - 내레이션: 최고의 즐거움을 위해
```
image prompt

Makoto Shinkai anime style, key visual. **Inside a boat's wheelhouse (pilothouse),** a heroic low-angle shot of a bright orange life jacket hanging neatly against a wall. **Brilliant morning sun streams through the large windows of the wheelhouse,** backlighting the life jacket and creating a luminous, hopeful glow that makes it look powerful and important. The texture of the fabric is drawn in beautiful detail. **In the soft-focus background, complex navigation equipment and the ship's wheel are visible.** Clean lines, vibrant colors.
```
[image output-whisk](./images/s3-c3-1.jpeg)
```
movie prompt

Makoto Shinkai anime style. Heroic low-angle shot inside a boat's wheelhouse. An orange life jacket hangs against a wall. Brilliant sun **streams through the windows**, its light shifting slightly. Tiny dust motes **float lazily through the volumetric sunbeams**, creating a serene and important atmosphere.
```

- ### CUT 3-2 (19-22초)

    - 영상: [Slow Push-in] 보트 내부에 단단히 고정된 소화기의 모습으로 카메라가 천천히 다가간다.

    - 내레이션: 가장 먼저 챙겨야 할
```
image prompt

Makoto Shinkai anime style, anime screencap. A slow, cinematic push-in shot on a Korean red fire extinguisher mounted securely inside the boat. The lighting is soft and focused, highlighting its sturdy and reliable presence. Detailed logos and instruction labels are visible.
```
[image output-whisk](./images/s3-c3-2.jpeg)
```
movie prompt

Makoto Shinkai anime style. The camera **pushes in slowly and cinematically** on a red fire extinguisher mounted securely inside the boat, passing by soft-focus navigation equipment in the foreground.
```

- ### CUT 3-3 (22-26초)

    - 영상: [Extreme Close Up] 방수팩에 담긴 스마트폰 화면. '해로드' 앱의 지도 화면이 선명하게 보인다. 

    - 내레이션: 진짜 필수 장비들
```
image prompt

Makoto Shinkai anime style. An extreme close-up of a smartphone screen, safe inside a waterproof pouch. The screen is brightly lit, displaying the colorful map and interface of the 'Haeroad' safety app. The background is a soft-focus, sparkling ocean. Luminous and clear.
```
[image output-whisk](./images/s3-c3-3.jpeg)
```
movie prompt

Makoto Shinkai anime style. Extreme close-up of a smartphone in a waterproof pouch. On the screen, the 'Haeroad' safety app is active, with the boat's icon **pulsing gently** on the map. The background is a **softly moving** bokeh ocean.
```

## SCENE 4: 보이지 않는 승무원의 활동 (26-46초)
- ### CUT 4-1 (26-30초)

    - 영상: [Close Up] 익명의 손이 나타나 버너 옆에 있던 부탄가스를 집어 멀리 떨어진 그늘진 수납공간에 넣는다.

    - 음향: 다시 세련된 리듬의 BGM 시작.
```
image prompt

Makoto Shinkai anime style. A close-up shot focusing on a pair of anonymous hands. The hands decisively move a butane gas canister away from a heat source and place it into a shaded, safe storage compartment on the boat. The action is clear and purposeful. Cel-shaded, clean animation style.
```
[image output-whisk](./images/s4-c4-1.jpeg)
```
movie prompt

Makoto Shinkai anime style. Close-up shot. A pair of hands **purposefully enters the frame**, picks up a butane canister, and **moves it smoothly and decisively** into a shaded storage compartment.
```

- ### CUT 4-2 (30-34초)

    - 영상: [Top-down Shot] 다른 손이 뒤엉킨 케이블들을 깔끔하게 말아서 정리한다.

    - 내레이션: 레저의 고수는 안전의 고수입니다.
```
image prompt

Makoto Shinkai anime style. A satisfying top-down shot of hands neatly coiling tangled cables and securing them with a tie. The chaotic mess becomes organized and safe. The colors are bright and clear, conveying a sense of order.
```
[image output-whisk](./images/s4-c4-2.jpeg)
```
movie prompt

Makoto Shinkai anime style. Satisfying top-down shot. Hands **deftly and quickly** untangle and coil a mess of cables and fishing line, creating perfect order from chaos in a **fast-motion (timelapse) effect**.
```

- ### CUT 4-3 (34-38초)

    - 영상: [Medium Shot] 또 다른 손이 술캔을 치우고, 그 자리에 뚜껑이 닫힌 생수병을 놓는다. 

    - 내레이션: 우리는 모두 서로의
```
image prompt

Makoto Shinkai anime style, anime screencap. A medium shot focusing on the **boat's cockpit area, right next to the throttle controls.** A hand reaches in, picks up a can of korean beer, and replaces it with a bottle of korean mineral water. **Sunlight streams through the windscreen,** glinting off the water bottle and creating a bright highlight on the clean, metallic throttle lever. The action feels refreshing and responsible.
```
[image output-whisk](./images/s4-c4-3.jpeg)
```
movie prompt

Makoto Shinkai anime style. Medium shot inside the boat's cockpit. A hand **reaches into the frame**, picks up a can of beer, and **places a bottle of mineral water down** in its spot with a gentle thud. The action is smooth and responsible.
```

- ### CUT 4-4 (38-46초)

    - 영상: [Close Up] 마지막으로, 익명의 손이 구명조끼의 지퍼를 목 끝까지 '착' 올리고 버클을 '딸깍' 소리 나게 채운다.

    - 음향: SFX(지퍼 올리는 소리, 버클 채우는 소리)가 선명하게 들림.

    - 내레이션: **'보이지 않는 승무원'**입니다.
```
image prompt

Makoto Shinkai anime style, anime screencap. An extreme close-up, satisfying shot of hands zipping up a life jacket all the way to the top. The 'click' of the buckle fastening is visually implied. The focus is on the secure and safe feeling of the action. Masterpiece quality.
```
[image output-whisk](./images/s4-c4-4.jpeg)
```
movie prompt (Kling)

Makoto Shinkai anime style, anime screencap. A clean and clear close-up shot, focusing on the torso of a person wearing a bright orange safety vest. Anonymous, graceful hands are shown **skillfully securing the vest.** The hands **confidently cinch the side straps**, ensuring a snug and proper fit without any sense of restriction. After the adjustment, one hand gives a **light, affirmative tap** on the chest panel of the vest, symbolizing that the safety check is complete. The entire motion is fluid and conveys a sense of quiet competence and preparedness. Masterpiece quality.
```

## SCENE 5: 결과 (46-52초)
- ### CUT 5-1 (46-49초)

    - 영상: [Medium Shot] 모든 위험 요소가 사라진, 깔끔하고 정돈된 보트 위의 모습.

    - 음향: BGM이 안정되고 만족스러운 톤으로 전환됨.
```
image prompt

Makoto Shinkai anime style, anime screencap. key visual. A beautiful and serene medium wide shot of the organized deck of a sleek, white yacht, anime style. All leisure equipment is neatly stored: fishing rods are secured, cables are coiled, and the cockpit area is clean. The atmosphere is calm and safe, with warm afternoon sunlight casting soft shadows on the clean teak deck. 
```
[image output-whisk](./images/s5-c5-1.jpeg)
```
movie prompt

Makoto Shinkai anime style. A beautiful and serene medium wide shot of the organized deck of a white yacht. The yacht **rocks gently** on the calm water. The atmosphere is peaceful as the late afternoon sun **slowly moves**, causing the soft shadows to lengthen.
```

- ### CUT 5-2 (49-52초)

    - 영상: 카메라가 부드럽게 뒤로 빠지면서(Pull-out) 평화로운 바다와 함께 안전한 보트의 전경을 보여준다.

    - 자막: 안전이 확보될 때 즐거움은 완성됩니다.
```
image prompt

Makoto Shinkai anime style, key visual. The camera smoothly pulls out from the deck to reveal the entire **beautiful, white yacht** sailing on a peaceful, sparkling blue ocean. The shot transitions to a majestic wide view. The sky above is vast and filled with dramatic, beautifully rendered clouds, with sun rays breaking through. The scene is epic, serene, and breathtaking.
```
[image output-whisk](./images/s5-c5-2.jpeg)
```
movie prompt

Makoto Shinkai anime style. The camera **pulls out smoothly and majestically** from the deck, revealing the entire beautiful, white yacht as it **sails forward across** a sparkling blue ocean. The motion is graceful and epic.
```

## SCENE 6: 결론 (52-59초)
- ### CUT 6-1 (52-59초)

    - 영상: [Drone Shot] 안전하게 정돈된 보트가 시원하게 물살을 가르며 푸른 바다를 향해 나아간다. 화면 중앙에 최종 슬로건과 로고가 나타난다.

    - 음향: 웅장하고 시원하게 마무리.

    - 자막:
```
즐거운 바다, 안전한 레저
당신이 바로 '보이지 않는 승무원'입니다.

[해양수산부 / 해양안전실천본부 로고]
```
```
Makoto Shinkai anime style, epic drone shot. The safe and organized boat cuts cleanly through the vast, beautiful blue ocean towards a brilliant sunrise. The sky is filled with dramatic, luminous clouds and light rays. A breathtaking and hopeful final image. Theatrical animation quality, 8k.
```
[image output-whisk](./images/s6-c6.jpeg)
```
Makoto Shinkai anime style. An epic, sweeping drone shot **flying alongside** a beautiful white yacht as it **cuts cleanly through** the vast blue ocean towards a brilliant sunrise. Luminous clouds **drift slowly** across the sky.
```