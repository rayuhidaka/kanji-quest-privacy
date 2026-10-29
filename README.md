# Privacy policy – Brush Quest: Kanji RPG

The public privacy policy of the Android game (game repo: KanjiRPG_Godot). `index.html` is one bilingual page (English + Japanese) meant for GitHub Pages.

## Before publishing
1. Replace `[DEVELOPER NAME]` and `[CONTACT EMAIL]` in `index.html` (4 places each, English and Japanese).
2. If the store name changes from "Brush Quest: Kanji RPG" / 「ふでクエスト 漢字RPG」, change it in the `<title>`, the first lines and the Japanese 運営者 section.

## Publish with GitHub Pages
1. Create a public repo, e.g. `kanji-quest-privacy`, and push this folder.
2. Repo → Settings → Pages → Deploy from a branch → `main` / root.
3. The page is then at `https://<user>.github.io/kanji-quest-privacy/`. That URL goes into Play Console (App content → Privacy policy) and into the game (`data/credits.json` → `privacy_url`).

## Keep it true
Update the page (and its effective date) whenever the game adds an SDK or a feature that touches data: ad mediation networks, analytics, in-app purchases ("Remove ads"), cloud saves, an own leaderboard backend. The Play Console Data safety answers (`tools/store/play_console_answers.md` in the game repo) must match it.

`app-ads.txt` for AdMob has to be at the **root** of the developer website, so it can't live in this project site; see the game repo's Play Console notes.
