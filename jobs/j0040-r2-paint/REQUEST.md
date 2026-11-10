# 일감 j0040-r2-paint — 2차 · 그림 6장

polos0117/style-atelier-img 저장소의 일감이야. 아래 칸마다 그림 한 장씩 그려서 WebP 로 바꿔 `inbox/` 폴더에 정해진 이름으로 올려줘(main 에 일반 push). ChatGPT 이미지 생성으로 그린다(세로 2:3, 1024×1536).

진행 방식 — **묻지 않고 끝까지 한다**(사용자 2026-11-10 「gpt쪽 작업이 둘 다 채팅창에 멈춰서 진행이 안되고있어」)
- 그림을 보여 주고 확인을 기다리지 않는다. 「계속할까요?」 도 묻지 않는다 — 사용자는 올라간 뒤 화풍공방 화면에서 본다.
- 이 환경에서 그림 파일을 저장소에 올릴 수 없으면(파일 쓰기 · push 가 안 되는 채팅) 그리지 말고 예약도 하지 말고, 바로 「이 환경에선 그림을 올릴 수 없다」 고 한 줄 말하고 끝낸다.

시작 전 — 예약(다른 세션과 겹치지 않게)
1. `jobs/j0040-r2-paint/CLAIM.md` 를 **새 파일로** 만들어 올린다. 내용은 두 줄 — 이 세션을 알아볼 이름(대화 제목 같은 것) · 지금 시각.
2. 이미 `CLAIM.md` 가 있으면(새로 만들기가 실패하면) 다른 세션이 하는 중이다 — `jobs/NEXT.md` 로 돌아가 「예약」 칸이 — 인 다른 일감을 고른다.
   예외: 사용자가 이 일감을 콕 집어 이어서 하라고 했거나 NEXT.md 에 「예약 만료」 로 나오면, 그 파일 끝에 두 줄(이름 · 시각)을 더 적고 이어서 한다.
3. 예약했으면 `rec/` 에 기록이 없는 칸만 그린다.

그리기
- 이미지 도구(image_gen)로, **크기를 세로 1024×1536 으로 지정**해서, 칸 하나에 호출 한 번. 「아래 지시문을 고치지 말고 그대로 그려라」 로 지시문만 넘긴다.
- 올리는 꼴은 **다른 공방과 같게** — 원본 PNG 는 올리지 않고, WebP(품질 90, 1024×1536)로 바꿔 `inbox/<이름>.webp` 로 올린다(장당 수백 KB).
- 이 일감의 칸을 다 그린 뒤 **한 커밋으로** 올린다(main 에 일반 push). 예약(`CLAIM.md`)만 시작할 때 따로 올린다.

규칙
- 지시문(코드 블록 안 영어)은 **한 글자도 바꾸지 않고** 그대로 넣는다. 설명 · 앞말을 붙이지 않는다.
- 파일 이름은 칸에 적힌 이름 그대로 + `.webp`. 예: `inbox/km2-ss2-cg2-mu1-xf1__sam.wenyang__samguk-world-low__chatgpt__1.webp`
- 막히면(정책 거절) 같은 지시문으로 한 번 더. 그래도 막히면 그림 대신 `inbox/<이름>.blocked.txt` 에 거절 문구 한 줄. 지시문은 고치지 않는다.
- 그림을 보고 한 줄 남기고 싶으면 `inbox/<이름>.note.txt`(선택).
- `CLAIM.md` 말고 다른 파일은 고치지 않는다. 이미 있는 이름은 덮지 않는다.
- 하다 끊기면 이어받는 세션은 위 예외대로 `CLAIM.md` 에 두 줄을 더 적고, `rec/` 에 기록이 없는 칸만 그린다.
- 다 올리면 끝. 변환 · 썸네일 · 기록 · 목록은 워크플로가 한다.

## 1. `km2-ss2-cg2-mu1-xf1__sam.wenyang__samguk-world-low__chatgpt__1`

반실사 · 이상화 · 섬세 · 2D 셀~그라데이션 · 선화 — 차분 · 낮은 채도 · 깊은 그림자 · 이펙트 옅게(발광은 가늘고 적게) (한국 MMORPG) — sam.wenyang · samguk · 노출 low

```text
A full-body character image, vertical 2:3 (1024×1536): Wen Yang of the Romance of the Three Kingdoms, reimagined as an adult woman — the young warrior who turned alone and drove back hundreds.

1. STYLE
Korean MMORPG character artwork. An idealised face with semi-realistic structure and delicate features. Clean 2D cel-to-gradient shading: crisp thin dark linework, hair drawn as many fine strands, and soft airy gradients.
Her face is small and soft: a short midface, a softly rounded jaw and a small chin, about 1.3 times as long as it is wide, with her eyes open at their natural size. Bangs, side locks and headpieces frame the face without lengthening it.

2. CHARACTER
Age: late twenties — a graceful grown-up face with soft, smooth contours.
Face — her own, recognisably this character, a woman's face with no beard or facial hair: a fierce, wild ferocity; fair skin; heart-shaped face; large eyes — large round eyes, outer eye corners drooping downward; thin arched brows; small button nose; full wide lips; ice-blue eyes; sharp winged eyeliner.
Body and hair: tall and statuesque with long legs and a full, curvaceous figure — full bust and hips, narrow waist build; a bob with long bangs falling over one eye; glossy jet-black hair.
Expression: a composed, self-assured look, subtle and relaxed.
Legend, carried in her design and bearing: peerless solo courage, a steel whip-sword.
Anatomy: one head, two arms and two legs, each joined at its natural joint; natural hands with five fingers.

3. COSTUME AND EQUIPMENT — THREE KINGDOMS
Costume: Three Kingdoms war general's armor — lamellar scale armor laced over a silk battle robe, beast-head shoulder guards, a plumed helmet or a war headband, a long war cape, her weapon at hand. Late-Han Chinese dress — cross-collared silk robes with wide sleeves and a broad sash, lamellar or scale armor laced with cords where armor is worn, bronze, jade and lacquer ornament, Han court hair ornaments; silk, lacquered leather, bronze and iron.
Silhouette: layered laced lamellar armor, big heavy beast-head pauldrons and armored skirts to the knees — a broad, weighty general's silhouette. The overall shape is fixed; the details are free.
Colours: deep navy blue, black lacquer, cold steel silver, ivory white.
Signature item: a steel whip-sword. She holds it at full scale: one whole object, drawn once, held in front of or beside her body; a long weapon keeps one straight, unbroken shaft with a single head or blade.
Exposure (low): a mostly covered version of the costume WORLD describes; face, neck and hands show.

4. SCENE
World: Cao Wei in northern China, around 200–235 AD: the walled capitals of Xuchang, Ye and Luoyang, rammed-earth ramparts and tiled watchtowers, black-and-navy banners over vast northern plains, armoured cavalry, bronze ritual vessels and lacquered halls.
Pose: standing confidently, her body turned slightly while her face looks toward the viewer.
Light: soft, even key light on her face; a muted, slightly desaturated palette with deep soft shadows and small restrained highlights. Any glowing details stay thin, sparse and pale, lighting only their own edges.
Composition: her whole figure from the top of her head or headpiece to both feet inside the frame with clear margins, about four-fifths of the image height; camera at chest height with natural portrait perspective.

5. CONSTRAINTS
One figure only — no second character, horse or other creature. No readable text or numbers, except that a banner, seal or emblem may carry the single character 魏 or 文. No logo, watermark, speech bubble or frame border. Three Kingdoms-era Chinese dress, architecture and materials only.
Avoid: 3D rendering, photographic skin texture.
```

## 2. `km2-ss2-ms2-mu1-xf1__sam.wenyang__samguk-world-low__chatgpt__1`

반실사 · 이상화 · 섬세 · 2D 무광 소프트 — 차분 · 낮은 채도 · 깊은 그림자 · 이펙트 옅게(발광은 가늘고 적게) (한국 MMORPG) — sam.wenyang · samguk · 노출 low

```text
A full-body character image, vertical 2:3 (1024×1536): Wen Yang of the Romance of the Three Kingdoms, reimagined as an adult woman — the young warrior who turned alone and drove back hundreds.

1. STYLE
Korean MMORPG character artwork. An idealised face with semi-realistic structure and delicate features. 2D soft matte painting: smooth gentle gradients and quiet, powdery surfaces.
Her face is small and soft: a short midface, a softly rounded jaw and a small chin, about 1.3 times as long as it is wide, with her eyes open at their natural size. Bangs, side locks and headpieces frame the face without lengthening it.

2. CHARACTER
Age: late twenties — a graceful grown-up face with soft, smooth contours.
Face — her own, recognisably this character, a woman's face with no beard or facial hair: a fierce, wild ferocity; fair skin; heart-shaped face; large eyes — large round eyes, outer eye corners drooping downward; thin arched brows; small button nose; full wide lips; ice-blue eyes; sharp winged eyeliner.
Body and hair: tall and statuesque with long legs and a full, curvaceous figure — full bust and hips, narrow waist build; a bob with long bangs falling over one eye; glossy jet-black hair.
Expression: a composed, self-assured look, subtle and relaxed.
Legend, carried in her design and bearing: peerless solo courage, a steel whip-sword.
Anatomy: one head, two arms and two legs, each joined at its natural joint; natural hands with five fingers.

3. COSTUME AND EQUIPMENT — THREE KINGDOMS
Costume: Three Kingdoms war general's armor — lamellar scale armor laced over a silk battle robe, beast-head shoulder guards, a plumed helmet or a war headband, a long war cape, her weapon at hand. Late-Han Chinese dress — cross-collared silk robes with wide sleeves and a broad sash, lamellar or scale armor laced with cords where armor is worn, bronze, jade and lacquer ornament, Han court hair ornaments; silk, lacquered leather, bronze and iron.
Silhouette: layered laced lamellar armor, big heavy beast-head pauldrons and armored skirts to the knees — a broad, weighty general's silhouette. The overall shape is fixed; the details are free.
Colours: deep navy blue, black lacquer, cold steel silver, ivory white.
Signature item: a steel whip-sword. She holds it at full scale: one whole object, drawn once, held in front of or beside her body; a long weapon keeps one straight, unbroken shaft with a single head or blade.
Exposure (low): a mostly covered version of the costume WORLD describes; face, neck and hands show.

4. SCENE
World: Cao Wei in northern China, around 200–235 AD: the walled capitals of Xuchang, Ye and Luoyang, rammed-earth ramparts and tiled watchtowers, black-and-navy banners over vast northern plains, armoured cavalry, bronze ritual vessels and lacquered halls.
Pose: standing confidently, her body turned slightly while her face looks toward the viewer.
Light: soft, even key light on her face; a muted, slightly desaturated palette with deep soft shadows and small restrained highlights. Any glowing details stay thin, sparse and pale, lighting only their own edges.
Composition: her whole figure from the top of her head or headpiece to both feet inside the frame with clear margins, about four-fifths of the image height; camera at chest height with natural portrait perspective.

5. CONSTRAINTS
One figure only — no second character, horse or other creature. No readable text or numbers, except that a banner, seal or emblem may carry the single character 魏 or 文. No logo, watermark, speech bubble or frame border. Three Kingdoms-era Chinese dress, architecture and materials only.
```

## 3. `km2-ss2-r32-mu1-xf1__sam.wenyang__samguk-world-low__chatgpt__1`

반실사 · 이상화 · 섬세 · 스타일라이즈드 3D 렌더 — 차분 · 낮은 채도 · 깊은 그림자 · 이펙트 옅게(발광은 가늘고 적게) (한국 MMORPG) — sam.wenyang · samguk · 노출 low

```text
A full-body character image, vertical 2:3 (1024×1536): Wen Yang of the Romance of the Three Kingdoms, reimagined as an adult woman — the young warrior who turned alone and drove back hundreds.

1. STYLE
Korean MMORPG character artwork. An idealised face with semi-realistic structure and delicate features. Stylised 3D rendering: smooth appealing forms, hair modelled in clean chunky shapes, soft subsurface skin and simplified, readable materials.
Her face is small and soft: a short midface, a softly rounded jaw and a small chin, about 1.3 times as long as it is wide, with her eyes open at their natural size. Bangs, side locks and headpieces frame the face without lengthening it.

2. CHARACTER
Age: late twenties — a graceful grown-up face with soft, smooth contours.
Face — her own, recognisably this character, a woman's face with no beard or facial hair: a fierce, wild ferocity; fair skin; heart-shaped face; large eyes — large round eyes, outer eye corners drooping downward; thin arched brows; small button nose; full wide lips; ice-blue eyes; sharp winged eyeliner.
Body and hair: tall and statuesque with long legs and a full, curvaceous figure — full bust and hips, narrow waist build; a bob with long bangs falling over one eye; glossy jet-black hair.
Expression: a composed, self-assured look, subtle and relaxed.
Legend, carried in her design and bearing: peerless solo courage, a steel whip-sword.
Anatomy: one head, two arms and two legs, each joined at its natural joint; natural hands with five fingers.

3. COSTUME AND EQUIPMENT — THREE KINGDOMS
Costume: Three Kingdoms war general's armor — lamellar scale armor laced over a silk battle robe, beast-head shoulder guards, a plumed helmet or a war headband, a long war cape, her weapon at hand. Late-Han Chinese dress — cross-collared silk robes with wide sleeves and a broad sash, lamellar or scale armor laced with cords where armor is worn, bronze, jade and lacquer ornament, Han court hair ornaments; silk, lacquered leather, bronze and iron.
Silhouette: layered laced lamellar armor, big heavy beast-head pauldrons and armored skirts to the knees — a broad, weighty general's silhouette. The overall shape is fixed; the details are free.
Colours: deep navy blue, black lacquer, cold steel silver, ivory white.
Signature item: a steel whip-sword. She holds it at full scale: one whole object, drawn once, held in front of or beside her body; a long weapon keeps one straight, unbroken shaft with a single head or blade.
Exposure (low): a mostly covered version of the costume WORLD describes; face, neck and hands show.

4. SCENE
World: Cao Wei in northern China, around 200–235 AD: the walled capitals of Xuchang, Ye and Luoyang, rammed-earth ramparts and tiled watchtowers, black-and-navy banners over vast northern plains, armoured cavalry, bronze ritual vessels and lacquered halls.
Pose: standing confidently, her body turned slightly while her face looks toward the viewer.
Light: soft, even key light on her face; a muted, slightly desaturated palette with deep soft shadows and small restrained highlights. Any glowing details stay thin, sparse and pale, lighting only their own edges.
Composition: her whole figure from the top of her head or headpiece to both feet inside the frame with clear margins, about four-fifths of the image height; camera at chest height with natural portrait perspective.

5. CONSTRAINTS
One figure only — no second character, horse or other creature. No readable text or numbers, except that a banner, seal or emblem may carry the single character 魏 or 文. No logo, watermark, speech bubble or frame border. Three Kingdoms-era Chinese dress, architecture and materials only.
Avoid: photoreal skin detail.
```

## 4. `km2-ss2-p31-mu1-xf1__sam.wenyang__samguk-world-low__chatgpt__1`

반실사 · 이상화 · 섬세 · 핸드페인팅 텍스처 3D — 차분 · 낮은 채도 · 깊은 그림자 · 이펙트 옅게(발광은 가늘고 적게) (한국 MMORPG) — sam.wenyang · samguk · 노출 low

```text
A full-body character image, vertical 2:3 (1024×1536): Wen Yang of the Romance of the Three Kingdoms, reimagined as an adult woman — the young warrior who turned alone and drove back hundreds.

1. STYLE
Korean MMORPG character artwork. An idealised face with semi-realistic structure and delicate features. In-engine 3D character rendering with hand-painted textures: semi-realistic volumetric forms and porcelain skin with a soft subsurface glow.
Her face is small and soft: a short midface, a softly rounded jaw and a small chin, about 1.3 times as long as it is wide, with her eyes open at their natural size. Bangs, side locks and headpieces frame the face without lengthening it.

2. CHARACTER
Age: late twenties — a graceful grown-up face with soft, smooth contours.
Face — her own, recognisably this character, a woman's face with no beard or facial hair: a fierce, wild ferocity; fair skin; heart-shaped face; large eyes — large round eyes, outer eye corners drooping downward; thin arched brows; small button nose; full wide lips; ice-blue eyes; sharp winged eyeliner.
Body and hair: tall and statuesque with long legs and a full, curvaceous figure — full bust and hips, narrow waist build; a bob with long bangs falling over one eye; glossy jet-black hair.
Expression: a composed, self-assured look, subtle and relaxed.
Legend, carried in her design and bearing: peerless solo courage, a steel whip-sword.
Anatomy: one head, two arms and two legs, each joined at its natural joint; natural hands with five fingers.

3. COSTUME AND EQUIPMENT — THREE KINGDOMS
Costume: Three Kingdoms war general's armor — lamellar scale armor laced over a silk battle robe, beast-head shoulder guards, a plumed helmet or a war headband, a long war cape, her weapon at hand. Late-Han Chinese dress — cross-collared silk robes with wide sleeves and a broad sash, lamellar or scale armor laced with cords where armor is worn, bronze, jade and lacquer ornament, Han court hair ornaments; silk, lacquered leather, bronze and iron.
Silhouette: layered laced lamellar armor, big heavy beast-head pauldrons and armored skirts to the knees — a broad, weighty general's silhouette. The overall shape is fixed; the details are free.
Colours: deep navy blue, black lacquer, cold steel silver, ivory white.
Signature item: a steel whip-sword. She holds it at full scale: one whole object, drawn once, held in front of or beside her body; a long weapon keeps one straight, unbroken shaft with a single head or blade.
Exposure (low): a mostly covered version of the costume WORLD describes; face, neck and hands show.

4. SCENE
World: Cao Wei in northern China, around 200–235 AD: the walled capitals of Xuchang, Ye and Luoyang, rammed-earth ramparts and tiled watchtowers, black-and-navy banners over vast northern plains, armoured cavalry, bronze ritual vessels and lacquered halls.
Pose: standing confidently, her body turned slightly while her face looks toward the viewer.
Light: soft, even key light on her face; a muted, slightly desaturated palette with deep soft shadows and small restrained highlights. Any glowing details stay thin, sparse and pale, lighting only their own edges.
Composition: her whole figure from the top of her head or headpiece to both feet inside the frame with clear margins, about four-fifths of the image height; camera at chest height with natural portrait perspective.

5. CONSTRAINTS
One figure only — no second character, horse or other creature. No readable text or numbers, except that a banner, seal or emblem may carry the single character 魏 or 文. No logo, watermark, speech bubble or frame border. Three Kingdoms-era Chinese dress, architecture and materials only.
```

## 5. `km2-ss2-pc2-mu1-xf1__sam.wenyang__samguk-world-low__chatgpt__1`

반실사 · 이상화 · 섬세 · 포토리얼 CGI — 차분 · 낮은 채도 · 깊은 그림자 · 이펙트 옅게(발광은 가늘고 적게) (한국 MMORPG) — sam.wenyang · samguk · 노출 low

```text
A full-body character image, vertical 2:3 (1024×1536): Wen Yang of the Romance of the Three Kingdoms, reimagined as an adult woman — the young warrior who turned alone and drove back hundreds.

1. STYLE
Korean MMORPG character artwork. An idealised face with semi-realistic structure and delicate features. Photorealistic CGI rendering: lifelike translucent skin with subtle subsurface scattering and microtexture, individually resolved hair strands, and silk, lacquer, leather, metal and gems with physically convincing roughness and reflections.
Her face is small and soft: a short midface, a softly rounded jaw and a small chin, about 1.3 times as long as it is wide, with her eyes open at their natural size. Bangs, side locks and headpieces frame the face without lengthening it.

2. CHARACTER
Age: late twenties — a graceful grown-up face with soft, smooth contours.
Face — her own, recognisably this character, a woman's face with no beard or facial hair: a fierce, wild ferocity; fair skin; heart-shaped face; large eyes — large round eyes, outer eye corners drooping downward; thin arched brows; small button nose; full wide lips; ice-blue eyes; sharp winged eyeliner.
Body and hair: tall and statuesque with long legs and a full, curvaceous figure — full bust and hips, narrow waist build; a bob with long bangs falling over one eye; glossy jet-black hair.
Expression: a composed, self-assured look, subtle and relaxed.
Legend, carried in her design and bearing: peerless solo courage, a steel whip-sword.
Anatomy: one head, two arms and two legs, each joined at its natural joint; natural hands with five fingers.

3. COSTUME AND EQUIPMENT — THREE KINGDOMS
Costume: Three Kingdoms war general's armor — lamellar scale armor laced over a silk battle robe, beast-head shoulder guards, a plumed helmet or a war headband, a long war cape, her weapon at hand. Late-Han Chinese dress — cross-collared silk robes with wide sleeves and a broad sash, lamellar or scale armor laced with cords where armor is worn, bronze, jade and lacquer ornament, Han court hair ornaments; silk, lacquered leather, bronze and iron.
Silhouette: layered laced lamellar armor, big heavy beast-head pauldrons and armored skirts to the knees — a broad, weighty general's silhouette. The overall shape is fixed; the details are free.
Colours: deep navy blue, black lacquer, cold steel silver, ivory white.
Signature item: a steel whip-sword. She holds it at full scale: one whole object, drawn once, held in front of or beside her body; a long weapon keeps one straight, unbroken shaft with a single head or blade.
Exposure (low): a mostly covered version of the costume WORLD describes; face, neck and hands show.

4. SCENE
World: Cao Wei in northern China, around 200–235 AD: the walled capitals of Xuchang, Ye and Luoyang, rammed-earth ramparts and tiled watchtowers, black-and-navy banners over vast northern plains, armoured cavalry, bronze ritual vessels and lacquered halls.
Pose: standing confidently, her body turned slightly while her face looks toward the viewer.
Light: soft, even key light on her face; a muted, slightly desaturated palette with deep soft shadows and small restrained highlights. Any glowing details stay thin, sparse and pale, lighting only their own edges.
Composition: her whole figure from the top of her head or headpiece to both feet inside the frame with clear margins, about four-fifths of the image height; camera at chest height with natural portrait perspective.

5. CONSTRAINTS
One figure only — no second character, horse or other creature. No readable text or numbers, except that a banner, seal or emblem may carry the single character 魏 or 文. No logo, watermark, speech bubble or frame border. Three Kingdoms-era Chinese dress, architecture and materials only.
Avoid: outlines, cel shading, broad brushwork, waxy or uniformly glossy skin.
```

## 6. `km2-ss2-pp2-mu1-xf1__sam.wenyang__samguk-world-low__chatgpt__1`

반실사 · 이상화 · 섬세 · 사진적 렌더링 — 차분 · 낮은 채도 · 깊은 그림자 · 이펙트 옅게(발광은 가늘고 적게) (한국 MMORPG) — sam.wenyang · samguk · 노출 low

```text
A full-body character image, vertical 2:3 (1024×1536): Wen Yang of the Romance of the Three Kingdoms, reimagined as an adult woman — the young warrior who turned alone and drove back hundreds.

1. STYLE
Korean MMORPG character artwork. An idealised face with semi-realistic structure and delicate features. Photographic rendering: real skin texture, natural hair, real fabric and metal, a shallow depth of field and true lens rendering.
Her face is small and soft: a short midface, a softly rounded jaw and a small chin, about 1.3 times as long as it is wide, with her eyes open at their natural size. Bangs, side locks and headpieces frame the face without lengthening it.

2. CHARACTER
Age: late twenties — a graceful grown-up face with soft, smooth contours.
Face — her own, recognisably this character, a woman's face with no beard or facial hair: a fierce, wild ferocity; fair skin; heart-shaped face; large eyes — large round eyes, outer eye corners drooping downward; thin arched brows; small button nose; full wide lips; ice-blue eyes; sharp winged eyeliner.
Body and hair: tall and statuesque with long legs and a full, curvaceous figure — full bust and hips, narrow waist build; a bob with long bangs falling over one eye; glossy jet-black hair.
Expression: a composed, self-assured look, subtle and relaxed.
Legend, carried in her design and bearing: peerless solo courage, a steel whip-sword.
Anatomy: one head, two arms and two legs, each joined at its natural joint; natural hands with five fingers.

3. COSTUME AND EQUIPMENT — THREE KINGDOMS
Costume: Three Kingdoms war general's armor — lamellar scale armor laced over a silk battle robe, beast-head shoulder guards, a plumed helmet or a war headband, a long war cape, her weapon at hand. Late-Han Chinese dress — cross-collared silk robes with wide sleeves and a broad sash, lamellar or scale armor laced with cords where armor is worn, bronze, jade and lacquer ornament, Han court hair ornaments; silk, lacquered leather, bronze and iron.
Silhouette: layered laced lamellar armor, big heavy beast-head pauldrons and armored skirts to the knees — a broad, weighty general's silhouette. The overall shape is fixed; the details are free.
Colours: deep navy blue, black lacquer, cold steel silver, ivory white.
Signature item: a steel whip-sword. She holds it at full scale: one whole object, drawn once, held in front of or beside her body; a long weapon keeps one straight, unbroken shaft with a single head or blade.
Exposure (low): a mostly covered version of the costume WORLD describes; face, neck and hands show.

4. SCENE
World: Cao Wei in northern China, around 200–235 AD: the walled capitals of Xuchang, Ye and Luoyang, rammed-earth ramparts and tiled watchtowers, black-and-navy banners over vast northern plains, armoured cavalry, bronze ritual vessels and lacquered halls.
Pose: standing confidently, her body turned slightly while her face looks toward the viewer.
Light: soft, even key light on her face; a muted, slightly desaturated palette with deep soft shadows and small restrained highlights. Any glowing details stay thin, sparse and pale, lighting only their own edges.
Composition: her whole figure from the top of her head or headpiece to both feet inside the frame with clear margins, about four-fifths of the image height; camera at chest height with natural portrait perspective.

5. CONSTRAINTS
One figure only — no second character, horse or other creature. No readable text or numbers, except that a banner, seal or emblem may carry the single character 魏 or 文. No logo, watermark, speech bubble or frame border. Three Kingdoms-era Chinese dress, architecture and materials only.
Avoid: illustration, painting, CGI look.
```
