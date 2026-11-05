# Privacy policy – Kanji Quest RPG

The public privacy policy of the Android game (game repo: KanjiRPG_Godot). `index.html` is one bilingual page (English + Japanese) meant for GitHub Pages.

## Before publishing
1. Developer: Ray Hidaka (Naomi.Jpn), contact nomi.ai.jpn@gmail.com (filled in 2026-10-30).
2. If the store name changes from "Kanji Quest RPG" / 「漢字クエストRPG」, change it in the `<title>`, the first lines and the Japanese 運営者 section.

## Publish with GitHub Pages
1. Create a public repo, e.g. `kanji-quest-privacy`, and push this folder.
2. Repo → Settings → Pages → Deploy from a branch → `main` / root.
3. The page is then at `https://<user>.github.io/kanji-quest-privacy/`. That URL goes into Play Console (App content → Privacy policy) and into the game (`data/credits.json` → `privacy_url`).

## Terms of service
`terms.html` (English + Japanese) is at `https://rayuhidaka.github.io/kanji-quest-privacy/terms.html`. That URL goes into Play Console for the trader declaration (select the app → Monitor and improve → Policy and programs → App content). Update it and its effective date when the game adds paid features or changes what it says about ads, saves or rewards.

## Keep it true
Update the page (and its effective date) whenever the game adds an SDK or a feature that touches data: ad mediation networks, analytics, in-app purchases ("Remove ads"), cloud saves, an own leaderboard backend. The Play Console Data safety answers (`tools/store/play_console_answers.md` in the game repo) must match it.

`app-ads.txt` for AdMob has to be at the **root** of the developer website, so it can't live in this project site; see the game repo's Play Console notes.
