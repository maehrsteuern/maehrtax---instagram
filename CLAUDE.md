# maehrtax – Instagram (US)

- Start of every session: use the skill `status` – run `python3 automation/status.py`, read `STATUS.md`, then tell Loris what goes live next and what's open.
- **Talk to Loris in German.** Everything in the repo (posts, captions, docs, code comments, commit messages) is US English.
- After every change: descriptive English commit message; update `automation/status_notes.md` if something was decided or is in progress; regenerate `STATUS.md` + `STATUS.html` (`python3 automation/status.py`) and commit them too.
- Source of truth: `strategy/00_us_brief.md`. Repo overview: `README.md`.
- Rules: no employer data (names, numbers, logos – demo data only) · AI label for realistic AI people, no AI-generated on-screen text · compliance footer `Educational content – not tax, legal or accounting advice.` on every educational post, `fact_check.md` for tax law · no individual tax advice · never claim CPA, EA, tax attorney or former IRS.

## EVA-Prinzip (Daueranweisung von Loris, 16.10.2026)

Eingabe → Verarbeitung → Ausgabe. Loris gibt eine menschliche Eingabe. Claude übersetzt sie für sich in Code und Plan und arbeitet dort so effizient wie möglich. **Vor der Ausgabe wird alles wieder vermenschlicht:** Jede Antwort, jeder Bericht, jede Oberfläche beginnt mit der Kernaussage in drei bis vier Sätzen ohne Fachsprache, ist für Menschen ohne Code-Kenntnis verständlich und visuell sauber (keine Überläufe, keine Funktionen als bloßer Text, echte Knöpfe, lesbare Beschriftungen, ruhige Formulare). Nach jedem Plan für Code folgt deshalb ein zweiter Plan: Wie wird das Ergebnis für Menschen lesbar und ansprechend? Gilt für alle Repos und alle Arbeitsbereiche.
