# 일감 j0006-base — 1차 · 그림 2장

polos0117/style-atelier-img 저장소의 일감이야. 아래 칸마다 그림 한 장씩 그려서 WebP 로 바꿔 `inbox/` 폴더에 정해진 이름으로 올려줘(main 에 일반 push). ChatGPT 이미지 생성으로 그린다(세로 2:3, 1024×1536).

진행 방식 — **묻지 않고 끝까지 한다**(사용자 2026-11-10 「gpt쪽 작업이 둘 다 채팅창에 멈춰서 진행이 안되고있어」)
- 그림을 보여 주고 확인을 기다리지 않는다. 「계속할까요?」 도 묻지 않는다 — 사용자는 올라간 뒤 화풍공방 화면에서 본다.
- 이 환경에서 그림 파일을 저장소에 올릴 수 없으면(파일 쓰기 · push 가 안 되는 채팅) 그리지 말고 예약도 하지 말고, 바로 「이 환경에선 그림을 올릴 수 없다」 고 한 줄 말하고 끝낸다.

시작 전 — 예약(다른 세션과 겹치지 않게)
1. `jobs/j0006-base/CLAIM.md` 를 **새 파일로** 만들어 올린다. 내용은 두 줄 — 이 세션을 알아볼 이름(대화 제목 같은 것) · 지금 시각.
2. 이미 `CLAIM.md` 가 있으면(새로 만들기가 실패하면) 다른 세션이 하는 중이다 — `jobs/NEXT.md` 로 돌아가 「예약」 칸이 — 인 다른 일감을 고른다.
   예외: 사용자가 이 일감을 콕 집어 이어서 하라고 했거나 NEXT.md 에 「예약 만료」 로 나오면, 그 파일 끝에 두 줄(이름 · 시각)을 더 적고 이어서 한다.
3. 예약했으면 `rec/` 에 기록이 없는 칸만 그린다.

그리기
- 이미지 도구(image_gen)로, **크기를 세로 1024×1536 으로 지정**해서, 칸 하나에 호출 한 번. 「아래 지시문을 고치지 말고 그대로 그려라」 로 지시문만 넘긴다.
- 올리는 꼴은 **다른 공방과 같게** — 원본 PNG 는 올리지 않고, WebP(품질 90, 1024×1536)로 바꿔 `inbox/<이름>.webp` 로 올린다(장당 수백 KB).
- 이 일감의 칸을 다 그린 뒤 **한 커밋으로** 올린다(main 에 일반 push). 예약(`CLAIM.md`)만 시작할 때 따로 올린다.

규칙
- 지시문(코드 블록 안 영어)은 **한 글자도 바꾸지 않고** 그대로 넣는다. 설명 · 앞말을 붙이지 않는다.
- 파일 이름은 칸에 적힌 이름 그대로 + `.webp`. 예: `inbox/ja1-ag1-cg1-hp1-xs1__el.fe__fantasy-world__chatgpt__1.webp`
- 막히면(정책 거절) 같은 지시문으로 한 번 더. 그래도 막히면 그림 대신 `inbox/<이름>.blocked.txt` 에 거절 문구 한 줄. 지시문은 고치지 않는다.
- 그림을 보고 한 줄 남기고 싶으면 `inbox/<이름>.note.txt`(선택).
- `CLAIM.md` 말고 다른 파일은 고치지 않는다. 이미 있는 이름은 덮지 않는다.
- 하다 끊기면 이어받는 세션은 위 예외대로 `CLAIM.md` 에 두 줄을 더 적고, `rec/` 에 기록이 없는 칸만 그린다.
- 다 올리면 끝. 변환 · 썸네일 · 기록 · 목록은 워크플로가 한다.

## 1. `ja1-ag1-cg1-hp1-xs1__el.fe__fantasy-world__chatgpt__1`

가챠 애니 · 큰 눈 · 홍조 · 선화 + 셀~그라데이션 — 하이키 파스텔 · 햇빛 광택 · 이펙트 부드럽게(블룸 · 작은 반짝임) (일본 가챠 애니) — el.fe · fantasy · 노출 bold

```text
A full-body vertical 2:3 (1024×1536) character card image of an adult woman — the personification of the element Iron (철) itself — the sovereign of the Iron Nation. A female character who IS the element; her costume, ornaments and colors carry the element’s traits. Both hands are ordinary human hands and hold nothing. Age: late twenties — a settled, mature adult face with defined cheekbones; no wrinkles, folds or under-eye bags.

1. STYLE
Polished Japanese anime gacha character illustration in clean 2D. An elegant adult anime face with large, finely detailed eyes with layered highlights and a soft blush. Crisp thin dark linework, hair drawn as many fine strands with light along every lock, and soft airy cel-to-gradient shading; the face and body stay visibly illustrated in 2D, never a 3D render.
Face proportions: a short midface and a soft, gently rounded jawline with a small soft chin — never a long face or a long, pointed or heavy jaw; any crown or headpiece sits above her hairline and never lengthens her face. Her eyes keep the shape described above at a natural open size — never squeezed into narrow slits.

2. CHARACTER
Look: a glamorous, sultry allure; bronze-brown skin; oval face; moderately sized, realistically proportioned eyes — wide almond eyes, level outer eye corners; soft rounded brows; straight narrow nose; full heart-shaped lips; ember-orange eyes; bold red lipstick. toned athletic-curvy, full-busted with rounded hips build; long wavy hair with center-parted bangs framing the face; iron-grey hair with a brushed-steel sheen.
Element: dark grey iron with bright steel highlights, orange-brown rust and glowing forge-orange heat, magnetism (iron filings, lodestone), hardness and weight, the smell of a smithy; it is the element of tools, weapons, bridges, machines and blood. Palette: iron grey, steel silver, rust orange, ember red, black soot.

3. COSTUME AND EQUIPMENT — HIGH FANTASY
World and costume: a fantasy kingdom of smiths: a mountain fortress built around a great forge, rivers of molten iron glowing in channels, hammered-iron gates, anvils as altars, iron filings drawn into patterns by magic magnetism, ember sparks in the air. COSTUME (fantasy): a high-fantasy royal or warrior costume — plate pauldrons or a gorget, mail or scale over a long tabard or robe, a circlet or crown, a flowing cape; metal ornament and regalia built from the traits above, subtle magical glow along the patterns. No corset, no bustle, no Victorian tailoring, no modern material, no machinery.
Silhouette: dragon-scale armor covering the body with horn-shaped shoulder and head ornaments — a beastly, imposing silhouette. Only the overall shape is fixed; design the details freely in the element's materials and palette. This silhouette overrides the overall shape of the costume above.
Exposure (bold): her regalia opens to show skin — bare shoulders and arms between pauldron and bracer, a deep open neckline under the gorget with natural cleavage, a high slit in the tabard or robe showing the thigh; armor pieces stay on and symmetrical. Nothing slipped off. Intimate areas covered; no corset; keep the costume WORLD describes, material and palette.

4. SCENE
Pose: standing confidently, her body turned slightly while her face looks toward the viewer. Expression: level brow, direct unhurried gaze, chin slightly raised, mouth closed and composed.
Light: bright, high-key outdoor daylight; her costume colours lifted toward soft pastel tints while the darkest accents stay deep and clean; a broad, soft sunlit sheen on skin, hair and armour, never wet, oily or plastic. Gentle bloom and a few small sparkles in the air.
Composition: vertical 2:3 full-body framing with modest headroom and clear space below the boots — the whole figure from the top of her head or headpiece to both feet stays inside the frame, occupying about four-fifths of the image height, with the same camera distance in every world; her hands stay inside the frame. Camera at chest height with natural portrait perspective — no wide-angle distortion, no low angle, no close crop.

5. CONSTRAINTS
One figure only, natural hands with five fingers; no text or numbers except her element's own chemical symbol (Fe) and atomic number (26) — and those only as part of the scene: engraved, embroidered or glowing on her costume, a banner, a sign or a machine, never as a floating label, corner badge, periodic-table tile, caption or overlay on the picture; no logo or watermark.
```

## 2. `kp1-ss1-ob1-hn1-x01__el.fe__fantasy-world__chatgpt__1`

반실사 · 작고 부드러운 얼굴 · 유화 붓질 · 글레이즈 — 하이키 자연광 (한국 MMORPG 프로모) — el.fe · fantasy · 노출 bold

```text
A full-body vertical 2:3 (1024×1536) character card image of an adult woman — the personification of the element Iron (철) itself — the sovereign of the Iron Nation. A female character who IS the element; her costume, ornaments and colors carry the element’s traits. Both hands are ordinary human hands and hold nothing. Age: late twenties — a settled, mature adult face with defined cheekbones; no wrinkles, folds or under-eye bags.

1. STYLE
Korean MMORPG promotional key art. A mature, idealised semi-realistic beauty with a small, soft face and delicate features. Delicate oil brushwork and layered glazes of colour, soft edges, refined detail kept for the face and costume, and silk and metal each with their own painterly texture.
Face proportions: a short midface and a soft, gently rounded jawline with a small soft chin — never a long face or a long, pointed or heavy jaw; any crown or headpiece sits above her hairline and never lengthens her face. Her eyes keep the shape described above at a natural open size — never squeezed into narrow slits.

2. CHARACTER
Look: a glamorous, sultry allure; bronze-brown skin; oval face; moderately sized, realistically proportioned eyes — wide almond eyes, level outer eye corners; soft rounded brows; straight narrow nose; full heart-shaped lips; ember-orange eyes; bold red lipstick. toned athletic-curvy, full-busted with rounded hips build; long wavy hair with center-parted bangs framing the face; iron-grey hair with a brushed-steel sheen.
Element: dark grey iron with bright steel highlights, orange-brown rust and glowing forge-orange heat, magnetism (iron filings, lodestone), hardness and weight, the smell of a smithy; it is the element of tools, weapons, bridges, machines and blood. Palette: iron grey, steel silver, rust orange, ember red, black soot.

3. COSTUME AND EQUIPMENT — HIGH FANTASY
World and costume: a fantasy kingdom of smiths: a mountain fortress built around a great forge, rivers of molten iron glowing in channels, hammered-iron gates, anvils as altars, iron filings drawn into patterns by magic magnetism, ember sparks in the air. COSTUME (fantasy): a high-fantasy royal or warrior costume — plate pauldrons or a gorget, mail or scale over a long tabard or robe, a circlet or crown, a flowing cape; metal ornament and regalia built from the traits above, subtle magical glow along the patterns. No corset, no bustle, no Victorian tailoring, no modern material, no machinery.
Silhouette: dragon-scale armor covering the body with horn-shaped shoulder and head ornaments — a beastly, imposing silhouette. Only the overall shape is fixed; design the details freely in the element's materials and palette. This silhouette overrides the overall shape of the costume above.
Exposure (bold): her regalia opens to show skin — bare shoulders and arms between pauldron and bracer, a deep open neckline under the gorget with natural cleavage, a high slit in the tabard or robe showing the thigh; armor pieces stay on and symmetrical. Nothing slipped off. Intimate areas covered; no corset; keep the costume WORLD describes, material and palette.

4. SCENE
Pose: standing confidently, her body turned slightly while her face looks toward the viewer. Expression: level brow, direct unhurried gaze, chin slightly raised, mouth closed and composed.
Light: soft, rich, bright natural light with gentle, subtle shadows; luminous, clear skin and vivid, full-bodied midtones that never wash out; small, soft highlights.
Composition: vertical 2:3 full-body framing with modest headroom and clear space below the boots — the whole figure from the top of her head or headpiece to both feet stays inside the frame, occupying about four-fifths of the image height, with the same camera distance in every world; her hands stay inside the frame. Camera at chest height with natural portrait perspective — no wide-angle distortion, no low angle, no close crop.

5. CONSTRAINTS
One figure only, natural hands with five fingers; no text or numbers except her element's own chemical symbol (Fe) and atomic number (26) — and those only as part of the scene: engraved, embroidered or glowing on her costume, a banner, a sign or a machine, never as a floating label, corner badge, periodic-table tile, caption or overlay on the picture; no logo or watermark.
```
