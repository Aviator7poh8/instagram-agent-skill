# Instagram – Avrora Design (@avrora_design_interiery.praha)

Tento repozitář je fork Jakeschincariol/instagram-agent-skill upravený pro
Kateřinu (Avrora Design, návrhy interiérů Praha a Praha-východ).

## Jak skilly používat

- Skilly `/ig-*` jsou ve složce `.claude/skills/` (kopie `skills/` z originálu
  včetně Python nástrojů `hookscore.py`, `beats.py`, `caption.py`,
  `humanize.py`, `detect.py`, `swipe.py`).
- **Profil hlasu je v `instagram/voice.md`** (ne v `~/.claude/instagram/`).
  Na začátku práce ho zkopíruj: `mkdir -p ~/.claude/instagram && cp instagram/voice.md ~/.claude/instagram/voice.md`.
  Log příspěvků (`log.md`) a swipe file (`swipe.md`) ukládej také do `instagram/`
  a nabídni commit, ať zůstanou mezi relacemi.
- Nic se nepublikuje automaticky. Skilly píšou, Kateřina publikuje.

## Pravidla pro tento účet

- Piš **česky, s vykáním**, klidně a prakticky – rada z praxe, ne lifestyle.
- Tempo voiceoveru: `beats.py --wpm 150` (čeština je delší než angličtina).
- `hookscore.py`, `caption.py` a `detect.py` jsou laděné na angličtinu –
  u českého textu ber skóre orientačně, rozhoduje srozumitelnost a konkrétnost.
- Klíčové slovo pro ManyChat: **DOMOV** (posílá checklist + nabídku konzultace).
- Odkaz pouze v biu: avrora-interiery.cz. V popisku žádné URL.
- Vizualizace vždy označit jako vizualizaci. Nevymýšlet čísla, klienty ani
  reference – chybějící údaj nech jako `{{doplnit}}`.
- Hashtagy max. 5, česky a konkrétně (např. #navrhinterieru #interierpraha
  #rekonstrukcebytu #panelak #bytovydesign).
