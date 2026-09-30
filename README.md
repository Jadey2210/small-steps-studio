# Small Steps Studio — first-release preview

This folder contains one static hub and five standalone app paths. Each app has its own name, visual theme, icon and install manifest. They share a local profile picker and keep each app's records separate in browser storage.

## App paths

- Inkroot — `/inkroot/`: writing prompt builder, named project and idea lists, search, favourites, edit/delete, and backup/import.
- Study Gumtree — `/study-gumtree/`: assessment question breakdown, guided answer planning, unit/task notes and Australian regulatory verification reminders.
- Little Signals — `/little-signals/`: parent-entered observation capture, clarification prompts, reviewable draft wording, notes and backup controls.
- Clear Note — `/clear-note/`: fictional ECEC/community-services documentation practice with a neutral-language checklist and saved attempts.
- Case Compass — `/case-compass/`: one fictional case file for separating known details, assumptions, missing context, questions and documentation issues.

## Important limits

This is a local-first prototype. The profile name is not a secure login. There is no server account, password, encryption, cloud storage, cross-device sync, AI service, clinical evidence, official regulatory citation, or professional-risk assessment. Browser storage may be visible to other people using the same browser profile and may be removed by browser cleanup. Do not enter identifying child, family, client or safety-sensitive information. Export backups manually and store them with care.

Several requested areas remain prototype-level or are not yet implemented: the full draggable metaphor tree and graveyard resurrection workflow; course analytics, flashcards, simulations, RPL vault and regulation translator; child profiles, milestone/communication timelines, budget tools and poster studio; a substantial scenario library with detailed annotations; and a diverse multi-document case-file library. Do not treat the current versions as complete replacements for those requested tools.

## Hosting and installation

The public source repository is [Jadey2210/small-steps-studio](https://github.com/Jadey2210/small-steps-studio). GitHub Actions publishes this folder to GitHub Pages on pushes to `main`. Expected site paths are `/`, `/inkroot/`, `/study-gumtree/`, `/little-signals/`, `/clear-note/` and `/case-compass/`; Pages will be usable after the first workflow run succeeds. Local preview: `http://localhost:4174/` while the preview server is running. Once hosted over HTTPS, install from the browser: desktop Chrome/Edge install control or menu; Android Chrome **Install app** or **Add to Home screen**; iPhone/iPad Safari **Share → Add to Home Screen**. Installation and offline behaviour depend on the platform. The service worker caches the hub and visited pages; it does not sync data.
