# Здача WS7

## Дані

- Роль: dev
- Команда: school-purchasing
- GitHub-логін: kdeineko-tech
- Ваше репо: https://github.com/kdeineko-tech/school-purchasing
- SHA: 17af4d59c55a44d25b740d630d75bf449d2bc483
- Репо вимог PM: https://github.com/ValiaBihun/2026-quitcode-dream-team
- Прод-URL: https://school-purchasing-lemon.vercel.app

## PM

—

## Розробник

- Рядок «Вимоги:» з `docs/conformance.md` на SHA: Вимоги: https://github.com/ValiaBihun/2026-quitcode-dream-team · джерело: issues · знімок 2026-10-26
- PR «Оновлення вимог» зі зрізом 2 (A): https://github.com/kdeineko-tech/school-purchasing/pull/14
- PR «Оновлення вимог» після уточнень PM (A): https://github.com/kdeineko-tech/school-purchasing/pull/35 (знімок 2026-10-26; також https://github.com/kdeineko-tech/school-purchasing/pull/21 — знімок 2026-10-25 після відповідей на Q5–Q8)
- Питання в репо PM (A; щонайменше 2, з них щонайменше 1 — власне issue): https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/57, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/58, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/59, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/60, https://github.com/ValiaBihun/2026-quitcode-dream-team/issues/62
- PR «Специфікація» з `add-<зріз2>` (A): https://github.com/kdeineko-tech/school-purchasing/pull/16 (уточнення після PM: https://github.com/kdeineko-tech/school-purchasing/pull/22, https://github.com/kdeineko-tech/school-purchasing/pull/36)
- Дизайн-система — PR (B): https://github.com/kdeineko-tech/school-purchasing/pull/32 (розташування: https://github.com/kdeineko-tech/school-purchasing/pull/34)
- Дизайн-система — `DESIGN.md` і джерело (B): https://github.com/kdeineko-tech/school-purchasing/blob/17af4d59c55a44d25b740d630d75bf449d2bc483/DESIGN.md · джерело: артефакт Claude Design (Design System) https://claude.ai/artifact/HHx1LvhQe5MeYqef7joXb3
- Дизайн-система — прогін `architecture` на `main` (B): https://github.com/kdeineko-tech/school-purchasing/actions/runs/40349875071
- Знімки «до/після» (B): https://github.com/kdeineko-tech/school-purchasing/blob/17af4d59c55a44d25b740d630d75bf449d2bc483/docs/img/ws7-before-login-light.png, https://github.com/kdeineko-tech/school-purchasing/blob/17af4d59c55a44d25b740d630d75bf449d2bc483/docs/img/ws7-after-login-light.png, https://github.com/kdeineko-tech/school-purchasing/blob/17af4d59c55a44d25b740d630d75bf449d2bc483/docs/img/ws7-before-home-light.png, https://github.com/kdeineko-tech/school-purchasing/blob/17af4d59c55a44d25b740d630d75bf449d2bc483/docs/img/ws7-after-home-light.png (темна тема — ті самі імена з `-dark`)
- Зміна `impl-<зріз2>` (C): https://github.com/kdeineko-tech/school-purchasing/tree/17af4d59c55a44d25b740d630d75bf449d2bc483/openspec/changes/archive/2026-10-26-impl-add-purchase-flow
- PR-и задач «Реалізація» (C; щонайменше 2): https://github.com/kdeineko-tech/school-purchasing/pull/20, https://github.com/kdeineko-tech/school-purchasing/pull/23, https://github.com/kdeineko-tech/school-purchasing/pull/28, https://github.com/kdeineko-tech/school-purchasing/pull/29, https://github.com/kdeineko-tech/school-purchasing/pull/31, https://github.com/kdeineko-tech/school-purchasing/pull/38 (AC-APR-08…10 після відповіді PM)
- Мутаційна перевірка — червоні прогони (C; щонайменше 2): https://github.com/kdeineko-tech/school-purchasing/actions/runs/40241046810 (AC-APR-03, AC-APR-04), https://github.com/kdeineko-tech/school-purchasing/actions/runs/40241337030 (AC-APR-05, AC-FRM-13)
- ADR (D): https://github.com/kdeineko-tech/school-purchasing/blob/17af4d59c55a44d25b740d630d75bf449d2bc483/docs/decisions/0004-role-in-profiles-table.md
- Архітектурне правило, крім `check:design` (D): jobs «Вхід і роль перевіряє сервер» (`scripts/check-auth-rules.mjs`) і «Секретний ключ лише на сервері» (`scripts/check-server-boundary.mjs`) у `.github/workflows/architecture.yml`; доказ, що ловить порушення, — PR https://github.com/kdeineko-tech/school-purchasing/pull/27 з виводом і тести `tests/scripts/check-auth-rules.test.ts`
- Акаунти для PM (E): pm-requester@example.test (requester, Primary School), pm-approver@example.test (approver, Primary School), pm-admin@example.test (admin)
- Скріни за ролями (E): https://github.com/kdeineko-tech/school-purchasing/blob/17af4d59c55a44d25b740d630d75bf449d2bc483/docs/img/ws7-role-requester-home.png, https://github.com/kdeineko-tech/school-purchasing/blob/17af4d59c55a44d25b740d630d75bf449d2bc483/docs/img/ws7-role-requester-new-purchase.png, https://github.com/kdeineko-tech/school-purchasing/blob/17af4d59c55a44d25b740d630d75bf449d2bc483/docs/img/ws7-role-requester-approvals-denied.png, https://github.com/kdeineko-tech/school-purchasing/blob/17af4d59c55a44d25b740d630d75bf449d2bc483/docs/img/ws7-role-approver-approvals.png, https://github.com/kdeineko-tech/school-purchasing/blob/17af4d59c55a44d25b740d630d75bf449d2bc483/docs/img/ws7-role-approver-purchase.png, https://github.com/kdeineko-tech/school-purchasing/blob/17af4d59c55a44d25b740d630d75bf449d2bc483/docs/img/ws7-role-approver-settings-denied.png, https://github.com/kdeineko-tech/school-purchasing/blob/17af4d59c55a44d25b740d630d75bf449d2bc483/docs/img/ws7-role-admin-home.png, https://github.com/kdeineko-tech/school-purchasing/blob/17af4d59c55a44d25b740d630d75bf449d2bc483/docs/img/ws7-role-admin-settings.png, https://github.com/kdeineko-tech/school-purchasing/blob/17af4d59c55a44d25b740d630d75bf449d2bc483/docs/img/ws7-role-guest-approvals-login.png (PR https://github.com/kdeineko-tech/school-purchasing/pull/40)
- AC зрізу 2 (E): AC-FRM-01 … AC-FRM-15 (реалізовано), AC-APR-01 … AC-APR-10 (реалізовано), AC-LANG-01 … AC-LANG-06, AC-LANG-08 (реалізовано); AC-LANG-07 прибрано рішенням PM (ValiaBihun/2026-quitcode-dream-team#57)
- Відхилення від PM (E): не надходило

## Бонус

—
