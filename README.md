# style-atelier-img

[style-atelier(화풍공방)](https://github.com/polos0117/style-atelier) 의 그림 저장소 — 일감 · 시험 그림 · 기록 · 색인.

## GPT 세션이 할 일

[`jobs/NEXT.md`](jobs/NEXT.md) 에서 일감 **하나**를 골라 그 `REQUEST.md` 만 읽고 그대로 한다. 그림은 `inbox/` 에 정해진 이름으로 올린다(main 에 일반 push). 나머지는 워크플로가 한다.

## 자리

```
jobs/NEXT.md                         열린 일감 목록(워크플로가 다시 쓴다)
jobs/<일감>/REQUEST.md               세션이 읽는 주문 — 칸 4개, 칸마다 파일 이름 · 지시문
jobs/<일감>/slots.json               같은 내용을 기계용으로
jobs/<일감>/prompts/<그림 이름>.txt  지시문 원문
inbox/                               세션이 올리는 곳 — 수거 뒤 빈다
img/<캐릭터>/<세계>/<그림 이름>.webp  1024×1536, 품질 90
thumb/<캐릭터>/<세계>/<그림 이름>.webp 긴 변 512
rec/<그림 이름>.json                 그림 한 장에 기록 하나(조합 · 부품 판 · 캐릭터 판 · 모델 · 일감 · 지시문 해시 · 메모 · 평)
rec/blocked/<그림 이름>.json         막힌 칸
index/images.json                    검색 색인(rec 에서 다시 짓는다 — 손대지 않는다)
index/blocked.json · problems.json   막힌 칸 · inbox 에 남은 것
```

그림 이름 = `<조합>__<캐릭터>__<세계>-<갈래>[-<노출>]__<모델>__<번호>` — 예: `km1-ss1-sm1-mu1-xf1__sam.wenyang__samguk-world__chatgpt__1`. 꼴과 뜻은 코드 저장소 `docs/STRUCTURE.md`.
