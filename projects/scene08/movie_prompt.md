## 이미지 prompt

```
1. 공통 요소 프롬프트 (Consistent Element Prompts)
모든 샷에서 캐릭터와 배경의 일관성을 유지하기 위한 기본 설정값입니다.

인물 1 - 남자 (Man) Prompt:

a handsome 30s East Asian man with sharp features and black hair, wearing a charcoal-grey utility jacket.
(이목구비가 뚜렷하고 검은 머리를 한 30대 동양인 남성. 차콜 그레이 색상의 유틸리티 재킷을 입고 있다.)

인물 2 - 아이 (Child) Prompt:

a 6-year-old Korean boy with short black hair, wearing a grey and orange long-sleeve shirt.
(짧은 검은 머리를 한 6살 한국인 남자아이. 회색과 주황색이 섞인 긴팔 셔츠를 입고 있다.)

배경 (Location) Prompt:

The scene is inside a modern, minimalist elevator with metallic walls. The view looks out into a long, brightly lit, clean corridor with white walls and rectangular fluorescent ceiling lights. The overall color palette is cool and clean.
(현대적이고 미니멀한 금속 벽의 엘리베이터 안. 길고 밝으며 깨끗한 복도가 내다보인다. 복도는 흰색 벽과 직사각형의 천장 형광등으로 되어 있다. 전체적인 색감은 차갑고 깨끗하다.)

스타일 (Style) Prompt:

--style cinematic, photorealistic, 8K, shallow depth of field, dramatic lighting
(--스타일 시네마틱, 극사실주의, 8K, 얕은 피사계 심도, 드라마틱한 조명)

2. Shot별 상세 프롬프트 (Detailed Prompts per Shot)
Shot #1: 시선의 이동 (Full Shot)
프롬프트:

(인물 1 Prompt) + (인물 2 Prompt) + (배경 Prompt).
An over-the-shoulder Full Shot from behind the man. The man has just lifted his head from his glowing AI wristwatch and is now looking down the long corridor at the boy. The **focus is sharp on the small boy** who is running down the hallway with arms outstretched, while the **man in the foreground is slightly out of focus.** The shot captures the moment the man's attention shifts from technology to human connection. (스타일 Prompt)
(남자의 등 뒤에서 촬영하는 오버더숄더 풀샷. 남자는 빛나는 AI 손목시계에서 막 고개를 들어, 이제 긴 복도 저편의 아이를 바라보고 있다. 초점은 팔을 벌리고 복도를 달려오는 작은 아이에게 선명하게 맞춰져 있고, 전경의 남자는 살짝 초점이 맞지 않는다. 이 샷은 남자의 관심이 기술에서 인간적인 연결로 이동하는 순간을 포착한다.)

Shot #2: 배려의 손길 (Extreme Close-Up)
프롬프트:

An extreme close-up shot of a man's hand. The cuff of a charcoal-grey jacket is visible. His index finger is pressing the illuminated **'open doors' [<|>] button** on a brushed metal elevator control panel. The button glows softly with a white light as it is pressed. The focus is on the finger and the button, showing macro details like fingerprints on the metallic surface. --style cinematic, photorealistic, 8K
(남자의 손을 촬영한 익스트림 클로즈업 샷. 차콜 그레이 재킷의 소매 끝이 보인다. 그의 검지 손가락이 헤어라인 마감된 금속 엘리베이터 제어판의 '문 열림' [<|>] 버튼을 누르고 있다. 버튼은 눌리면서 부드러운 흰색 빛을 낸다. 손가락과 버튼에 초점이 맞춰져, 금속 표면의 지문과 같은 매크로 디테일이 보인다.)

Shot #3: 아이의 미소 (Single Shot)
프롬프트:

(인물 2 Prompt) + (배경 Prompt의 엘리베이터 부분).
A heart-warming single shot, eye-level with the child. The boy has just run into the elevator and is straightening up after a polite 90-degree bow. He is looking directly up towards the camera (the man's perspective) with a **bright, innocent, and slightly breathless smile** on his face. The background is the blurred interior of the metallic elevator. (스타일 Prompt)
(아이와 눈높이를 맞춘, 마음이 따뜻해지는 단독 샷. 아이가 막 엘리베이터로 뛰어 들어와 정중하게 90도로 인사한 후 허리를 펴고 있다. 그는 카메라(남자의 시점)를 향해 위를 올려다보며, 밝고 순수하며 살짝 숨이 찬 미소를 짓고 있다. 배경은 흐릿한 금속 재질의 엘리베이터 내부다.)

Shot #4: 남자의 미소 (Tight Shot)
프롬프트:

(인물 1 Prompt).
A tight shot focusing on the man's face. He is looking down slightly (towards the child's height) with a **warm, genuine, and gentle smile**. The cool, neutral light of the elevator is softened by the warmth of his expression. The shot captures the subtle crinkles around his eyes as he smiles, conveying a sense of quiet joy. (스타일 Prompt)
(남자의 얼굴에 초점을 맞춘 타이트 샷. 그는 아이의 키에 맞춰 살짝 아래를 내려다보며, 따뜻하고, 진심 어리며, 부드러운 미소를 짓고 있다. 엘리베이터의 차갑고 중성적인 빛이 그의 표정의 따뜻함으로 인해 부드러워진다. 이 샷은 그가 미소 지을 때 눈가에 생기는 미세한 주름을 포착하여, 조용한 기쁨의 느낌을 전달한다.)
```

```
🎬 Shot별 상세 무비 프롬프트 (Movie Prompts per Shot)
Shot #1: 시선의 이동 (Full Shot)
프롬프트:

(Shot Type & Style): A cinematic, photorealistic, 4K video. The scene opens with a perfectly stable, over-the-shoulder full shot from behind a man standing before the open doors of a futuristic elevator. The aesthetic is clean, minimalist, and slightly sterile, contrasting with the human element.

(Scene Description & Action Sequence):

(Initial State): The camera's focus is initially razor-sharp on the man in the foreground. He is looking down intently at his AI smartwatch. The watch face is not a simple screen but a glowing, intricate blue holographic display, reminiscent of a sophisticated AI interface like JARVIS, casting a subtle cyan light onto his wrist and sleeve.

(0 to 2 seconds): He slowly and deliberately lifts his head, his attention being drawn away from the data on his wrist towards the scene down the long corridor before him.

(2 to 5 seconds): As his head rises, the camera executes a flawless and elegant focus pull (rack focus). The shallow depth of field smoothly shifts, transitioning the focal plane from the intricate details of the man and his holographic watch in the foreground to the distant background.

(5 to 8 seconds): Now in sharp focus at the end of the long, brightly-lit white hallway is a small boy, running with joyful abandon directly towards the elevator. His arms are outstretched to his sides like airplane wings, his face alight with pure, energetic glee. The sterile environment is filled with his vibrant, innocent energy. The camera remains perfectly still, emphasizing that this is not a camera movement, but a profound and deliberate shift in the man's point of view—from the world of data to a moment of human connection.



Shot #2: 배려의 손길 (Extreme Close-Up)
프롬프트:

Animate the reference image. A 2-second video clip. An extreme close-up shot. A man's index finger moves smoothly into the frame and presses down on the illuminated 'open doors' button. As the button is pressed, its light brightens for a moment and we hear a soft click. The movement is deliberate and gentle.



Shot #3: 아이의 미소 (Single Shot)
프롬프트:

Animate the reference image. A 4-second video clip. A heart-warming single shot, eye-level with the child. The boy runs into the frame, coming to a slightly breathless stop. He immediately bows a polite 90-degrees, then straightens up, lifting his head to look directly at the camera (the man's perspective) with a bright, innocent smile blooming on his face. His eyes are sparkling with life.



Shot #4: 남자의 미소 (Tight Shot)
프롬프트:

Animate the reference image. A 3-second video clip. A tight shot focusing on the man's face. He is looking down slightly. His neutral expression softens and transforms into a warm, genuine smile as he watches the child. The change is subtle but deeply felt, conveyed through the gentle upturn of his lips and the crinkling around his eyes. The camera is completely still, capturing the pure, quiet emotion.



```