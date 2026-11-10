# 일감 j0079-r13-canvas2 — 13차 · 그림 3장

**초점 밖 · 사용자가 정한 일감** — sam.wenyang · fantasy, sam.wenyang · mecha. `NEXT.md` 의 「sam.wenyang · samguk 만」 과 달라도 이 일감은 그대로 그린다.

polos0117/style-atelier-img 저장소의 일감이야. 아래 칸마다 그림 한 장씩 그려서 WebP 로 바꿔 `inbox/` 폴더에 정해진 이름으로 올려줘(main 에 일반 push). 그림 API(api26)로 그린다 — Claude 쪽 일감.

진행 방식 — **묻지 않고 끝까지 한다**(사용자 2026-11-10 「gpt쪽 작업이 둘 다 채팅창에 멈춰서 진행이 안되고있어」)
- 그림을 보여 주고 확인을 기다리지 않는다. 「계속할까요?」 도 묻지 않는다 — 사용자는 올라간 뒤 화풍공방 화면에서 본다.
- 이 환경에서 그림 파일을 저장소에 올릴 수 없으면(파일 쓰기 · push 가 안 되는 채팅) 그리지 말고 예약도 하지 말고, 바로 「이 환경에선 그림을 올릴 수 없다」 고 한 줄 말하고 끝낸다.

시작 전 — 예약(다른 세션과 겹치지 않게)
1. `jobs/j0079-r13-canvas2/CLAIM.md` 를 **새 파일로** 만들어 올린다. 내용은 두 줄 — 이 세션을 알아볼 이름(대화 제목 같은 것) · 지금 시각.
2. 이미 `CLAIM.md` 가 있으면(새로 만들기가 실패하면) 다른 세션이 하는 중이다 — `jobs/NEXT.md` 로 돌아가 「예약」 칸이 — 인 다른 일감을 고른다.
   예외: 사용자가 이 일감을 콕 집어 이어서 하라고 했거나 NEXT.md 에 「예약 만료」 로 나오면, 그 파일 끝에 두 줄(이름 · 시각)을 더 적고 이어서 한다.
3. 예약했으면 `rec/` 에 기록이 없는 칸만 그린다.

그리기
- 이미지 도구(image_gen)로, **크기를 세로 1024×1536 으로 지정**해서, 칸 하나에 호출 한 번. 「아래 지시문을 고치지 말고 그대로 그려라」 로 지시문만 넘긴다.
- 올리는 꼴은 **다른 공방과 같게** — 원본 PNG 는 올리지 않고, WebP(품질 90, 1024×1536)로 바꿔 `inbox/<이름>.webp` 로 올린다(장당 수백 KB).
- 이 일감의 칸을 다 그린 뒤 **한 커밋으로** 올린다(main 에 일반 push). 예약(`CLAIM.md`)만 시작할 때 따로 올린다.

규칙
- 지시문(코드 블록 안 영어)은 **한 글자도 바꾸지 않고** 그대로 넣는다. 설명 · 앞말을 붙이지 않는다.
- 파일 이름은 칸에 적힌 이름 그대로 + `.webp`. 예: `inbox/km2-il2-ba3-rg2-x01__sam.wenyang__samguk-world-slit~cr2__api26__1.webp`
- 막히면(정책 거절) 같은 지시문으로 한 번 더. 그래도 막히면 그림 대신 `inbox/<이름>.blocked.txt` 에 거절 문구 한 줄. 지시문은 고치지 않는다.
- 그림을 보고 한 줄 남기고 싶으면 `inbox/<이름>.note.txt`(선택).
- `CLAIM.md` 말고 다른 파일은 고치지 않는다. 이미 있는 이름은 덮지 않는다.
- 하다 끊기면 이어받는 세션은 위 예외대로 `CLAIM.md` 에 두 줄을 더 적고, `rec/` 에 기록이 없는 칸만 그린다.
- 다 올리면 끝. 변환 · 썸네일 · 기록 · 목록은 워크플로가 한다.

## 1. `km2-il2-ba3-rg2-x01__sam.wenyang__samguk-world-slit~cr2__api26__1`

그린 얼굴 · 가볍게 단순화 · 2D 붓질 · 색 선 — 림 라이트 · 강한 하이라이트 (한국 MMORPG) — sam.wenyang · samguk · 노출 slit · 배경 거친 유화 붓질 캔버스 · 배경은 덜 그림

```text
A full-body character image, vertical 2:3 (1024×1536): Wen Yang of the Romance of the Three Kingdoms, reimagined as an adult woman — the young warrior who turned alone and drove back hundreds.

1. STYLE
Korean MMORPG character artwork. A recognisably drawn face with gently simplified anatomical structure. 2D painting with visible brushwork: layered strokes of colour, soft broken edges, thin coloured linework and a few crisp accents on the face and costume.
Her face is small and soft: a short midface, a softly rounded jaw and a small chin, about 1.3 times as long as it is wide, with her eyes open at their natural size. Bangs, side locks and headpieces frame the face without lengthening it.

2. CHARACTER
Age: late twenties — a graceful grown-up face with soft, smooth contours.
Face — her own, recognisably this character, a woman's face with no beard or facial hair: a fierce, wild ferocity; fair skin; heart-shaped face; large eyes — large round eyes, outer eye corners drooping downward; thin arched brows; small button nose; full wide lips; ice-blue eyes; sharp winged eyeliner.
Body and hair: tall and statuesque with long legs and a full, curvaceous figure — full bust and hips, narrow waist build; a bob with long bangs falling over one eye; glossy jet-black hair.
Expression: a composed, self-assured look, subtle and relaxed.
Legend, carried in her design and bearing: peerless solo courage, a steel whip-sword.
Anatomy: one head, two arms and two legs, each joined at its natural joint; natural hands with five fingers.

3. COSTUME AND EQUIPMENT — THREE KINGDOMS
Costume: Three Kingdoms war general's armor — lamellar scale armor laced over a silk battle robe, beast-head shoulder guards, a war headband with a single white plume, a long war cape, her weapon at hand. Late-Han Chinese dress — cross-collared silk robes with wide sleeves and a broad sash, lamellar or scale armor laced with cords where armor is worn, bronze, jade and lacquer ornament, Han court hair ornaments; silk, lacquered leather, bronze and iron.
Silhouette: layered laced lamellar armor, big heavy beast-head pauldrons and armored skirts to the knees — a broad, weighty general's silhouette. The overall shape is fixed; the details are free.
Colours: deep navy blue, black lacquer, cold steel silver, ivory white.
Signature item: a steel whip-sword. She holds it at full scale: one whole object, drawn once, held in front of or beside her body; a long weapon keeps one straight, unbroken shaft with a single head or blade.
Exposure (slit): the costume WORLD describes opens at the collarbone and shows the arms, and a high slit in the skirt panels shows one leg up to the thigh; armor pieces stay on and symmetrical; intimate areas covered.

4. SCENE
World: Cao Wei in northern China, around 200–235 AD: the walled capitals of Xuchang, Ye and Luoyang, rammed-earth ramparts and tiled watchtowers, black-and-navy banners over vast northern plains, armoured cavalry, bronze ritual vessels and lacquered halls.
Pose: standing confidently, her body turned slightly while her face looks toward the viewer.
Light: a soft key light with a strong rim light tracing her hair, shoulders and armour; bright, crisp specular highlights on metal and jewellery, and a clean, warm-neutral sheen on her skin.
Background treatment: the setting behind her is loosely blocked in with thick, rough oil brushstrokes and palette-knife marks, with the canvas weave showing through thin passages; the background stays less detailed than the figure.
Composition: her whole figure from the top of her head or headpiece to both feet inside the frame with clear margins, about four-fifths of the image height; camera at chest height with natural portrait perspective.

5. CONSTRAINTS
One figure only — no second character, horse or other creature. No readable text or numbers, except that a banner, seal or emblem may carry the single character 魏 or 文. No logo, watermark, speech bubble or frame border. Three Kingdoms-era Chinese dress, architecture and materials only.
Avoid: a blue or bruise-like tint on the skin around the eyes.
```

## 2. `km2-il2-ba3-rg2-x01__sam.wenyang__fantasy-world-slit~cr2__api26__1`

그린 얼굴 · 가볍게 단순화 · 2D 붓질 · 색 선 — 림 라이트 · 강한 하이라이트 (한국 MMORPG) — sam.wenyang · fantasy · 노출 slit · 배경 거친 유화 붓질 캔버스 · 배경은 덜 그림

```text
A full-body character image, vertical 2:3 (1024×1536): Wen Yang of the Romance of the Three Kingdoms, reimagined as an adult woman — the young warrior who turned alone and drove back hundreds.

1. STYLE
Korean MMORPG character artwork. A recognisably drawn face with gently simplified anatomical structure. 2D painting with visible brushwork: layered strokes of colour, soft broken edges, thin coloured linework and a few crisp accents on the face and costume.
Her face is small and soft: a short midface, a softly rounded jaw and a small chin, about 1.3 times as long as it is wide, with her eyes open at their natural size. Bangs, side locks and headpieces frame the face without lengthening it.

2. CHARACTER
Age: late twenties — a graceful grown-up face with soft, smooth contours.
Face — her own, recognisably this character, a woman's face with no beard or facial hair: a fierce, wild ferocity; fair skin; heart-shaped face; large eyes — large round eyes, outer eye corners drooping downward; thin arched brows; small button nose; full wide lips; ice-blue eyes; sharp winged eyeliner.
Body and hair: tall and statuesque with long legs and a full, curvaceous figure — full bust and hips, narrow waist build; a bob with long bangs falling over one eye; glossy jet-black hair.
Expression: a composed, self-assured look, subtle and relaxed.
Legend, carried in her design and bearing: peerless solo courage, a steel whip-sword.
Anatomy: one head, two arms and two legs, each joined at its natural joint; natural hands with five fingers.

3. COSTUME AND EQUIPMENT — MEDIEVAL FANTASY
Costume: a knight-champion's armor — articulated plate with a heraldic tabard in her faction's colours, a circlet with a single white plume, a battle cape, her weapon at hand. Western medieval high-fantasy dress — plate, mail and heraldic tabards, gowns and mantles, circlets and crowns; steel, leather, wool, velvet and gold, with a subtle magical glow along the patterns. Her Three Kingdoms origin shows through her signature item, her colours and her bearing.
Silhouette: a fitted breastplate and pauldrons above a gown skirt flaring to the floor — an elegant lady-knight silhouette. The overall shape is fixed; the details are free.
Colours: deep navy blue, black lacquer, cold steel silver, ivory white.
Signature item: a steel whip-sword, reimagined as a Western high-fantasy version of the same kind of object with the same silhouette — polished steel and silvered mithril throughout, the shaft or hilt also forged metal with engraved runes (never plain wood), a faint magical glow running along the edge and the runes, a gem-set guard or socket, a leather-wrapped grip and heraldic or elven ornament, with any animal motif re-sculpted in Western heraldic style. She holds it at full scale: one whole object, drawn once, held in front of or beside her body; a long weapon keeps one straight, unbroken shaft with a single head or blade.
Exposure (slit): the costume WORLD describes opens at the collarbone and shows the arms, and a high slit in the tabard or gown shows one leg up to the thigh; armor pieces stay on and symmetrical; intimate areas covered.

4. SCENE
World: a stern northern empire of medieval high fantasy: black-stone citadels with blue banners, iron-shod heavy cavalry, snowy plains and pine forests, a court ruled by strict law, cold blue sigil-magic.
Pose: standing confidently, her body turned slightly while her face looks toward the viewer.
Light: a soft key light with a strong rim light tracing her hair, shoulders and armour; bright, crisp specular highlights on metal and jewellery, and a clean, warm-neutral sheen on her skin.
Background treatment: the setting behind her is loosely blocked in with thick, rough oil brushstrokes and palette-knife marks, with the canvas weave showing through thin passages; the background stays less detailed than the figure.
Composition: her whole figure from the top of her head or headpiece to both feet inside the frame with clear margins, about four-fifths of the image height; camera at chest height with natural portrait perspective.

5. CONSTRAINTS
One figure only — no second character, horse or other creature. No readable text or numbers — banners and shields carry only heraldic devices (a beast or a crest), never letters or Chinese characters. No logo, watermark, speech bubble or frame border. A Western medieval setting and dress only — stone castles, Romanesque or Gothic architecture — with no Chinese architecture, robes or hanzi.
Avoid: a blue or bruise-like tint on the skin around the eyes.
```

## 3. `km2-il2-ba3-rg2-x01__sam.wenyang__mecha-world-slit~cr2__api26__1`

그린 얼굴 · 가볍게 단순화 · 2D 붓질 · 색 선 — 림 라이트 · 강한 하이라이트 (한국 MMORPG) — sam.wenyang · mecha · 노출 slit · 배경 거친 유화 붓질 캔버스 · 배경은 덜 그림

```text
A full-body character image, vertical 2:3 (1024×1536): Wen Yang of the Romance of the Three Kingdoms, reimagined as an adult woman — the young warrior who turned alone and drove back hundreds.

1. STYLE
Korean MMORPG character artwork. A recognisably drawn face with gently simplified anatomical structure. 2D painting with visible brushwork: layered strokes of colour, soft broken edges, thin coloured linework and a few crisp accents on the face and costume.
Her face is small and soft: a short midface, a softly rounded jaw and a small chin, about 1.3 times as long as it is wide, with her eyes open at their natural size. Bangs, side locks and headpieces frame the face without lengthening it.

2. CHARACTER
Age: late twenties — a graceful grown-up face with soft, smooth contours.
Face — her own, recognisably this character, a woman's face with no beard or facial hair: a fierce, wild ferocity; fair skin; heart-shaped face; large eyes — large round eyes, outer eye corners drooping downward; thin arched brows; small button nose; full wide lips; ice-blue eyes; sharp winged eyeliner.
Body and hair: tall and statuesque with long legs and a full, curvaceous figure — full bust and hips, narrow waist build; a bob with long bangs falling over one eye; glossy jet-black hair.
Expression: a composed, self-assured look, subtle and relaxed.
Legend, carried in her design and bearing: peerless solo courage, a steel whip-sword.
Anatomy: one head, two arms and two legs, each joined at its natural joint; natural hands with five fingers.

3. COSTUME AND EQUIPMENT — MECHA
Costume: a female mecha personification built as an assault-type mecha frame — heavy armor plates, thruster packs, reinforced limbs, her weapon rebuilt as a large mecha armament. Solid hard-surface plates with visible joints cover her whole frame; any cape or skirt is made of rigid armored plates; her face and hair stay human.
Silhouette: several long rigid jointed plates hanging from behind the shoulders to the ankles like a cape — plates, not cloth. The overall shape is fixed; the details are free.
Colours: deep navy blue, black lacquer, cold steel silver, ivory white. Faction frame: navy-blue and black lacquer heavy plating with cold steel-silver edges, angular command fins, a disciplined symmetrical frame, cold blue glow lines.
Signature item: a steel whip-sword, rebuilt as a far-future high-tech version of the same kind of object with the same silhouette — hard-surface alloy plates with panel lines, mechanical joints, vents and emitter nodes, an energy edge, plasma blade or glowing core in her glow-line colour and small status lights, with any animal motif re-sculpted as sleek machined armour. She holds it at full scale: one whole object, drawn once, held in front of or beside her body; a long weapon keeps one straight, unbroken shaft with a single head or blade.
Exposure (slit): the frame opens at the collarbone and shows the arms, and bare upper thighs show between the hip armor and thigh-high leg plates; the plates stay on, fitted and symmetrical; intimate areas covered.

4. SCENE
World: year 2190, the Wei Federation in orbit: a navy-black orbital fortress and capital-ship fleet above a cold blue planet, starfields and a distant sun, hard white floodlights on armored hulls.
Pose: standing confidently, her body turned slightly while her face looks toward the viewer.
Light: a soft key light with a strong rim light tracing her hair, shoulders and armour; bright, crisp specular highlights on metal and jewellery, and a clean, warm-neutral sheen on her skin.
Background treatment: the setting behind her is loosely blocked in with thick, rough oil brushstrokes and palette-knife marks, with the canvas weave showing through thin passages; the background stays less detailed than the figure.
Composition: her whole figure from the top of her head or headpiece to both feet inside the frame with clear margins, about four-fifths of the image height; camera at chest height with natural portrait perspective.

5. CONSTRAINTS
One figure only — no second character, horse or other creature. No readable text or numbers — emblems are abstract insignia shapes only, never letters or Chinese characters. No logo, watermark, speech bubble or frame border. A far-future setting only — space stations, starships and high-tech structures — with no traditional East-Asian architecture.
Avoid: a blue or bruise-like tint on the skin around the eyes.
```
