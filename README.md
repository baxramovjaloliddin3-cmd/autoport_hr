# autoport — HR & Boshqaruv tizimi

Statik saytlar to'plami. GitHub Pages'da bepul hostlanadi.

## Tarkib
- `index.html` — bosh sahifa (hamma bo'limga havola)
- `hr/` — HR tizimi (kirish kodi: **autoport2026**)
- `portal/` — Adaptatsiya portali (Firebase — config to'ldirish kerak)
- `ariza/` — nomzod arizasi formasi
- `darslik/` — xodim darsligi va test
- `apps-script.txt` — Google Sheets collector (Apps Script)

## Sozlash (yuklashdan oldin yoki GitHub'da tahrirlab)
1. **portal/index.html** — boshidagi `firebaseConfig` ni Firebase Console qiymatlari bilan to'ldiring. (Ixtiyoriy: `TG_BOT_TOKEN`.)
2. **ariza/index.html** va **darslik/index.html** — `WEBHOOK_URL` ga Google Apps Script (Sheets) manzilini qo'ying.
3. **hr/** — kirish kodi ichida `autoport2026` (o'zgartirish ilova ichida ham mumkin).

## GitHub Pages
Repo → Settings → Pages → Deploy from a branch → `main` / `root` → Save.
Manzil: `https://<username>.github.io/<repo>/`
