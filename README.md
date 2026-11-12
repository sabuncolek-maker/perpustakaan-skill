# Perpustakaan Skill — Indra Erlangga

Kumpulan skill siap pakai berbahasa Indonesia dalam format `SKILL.md`, format yang dipakai fitur skill di Claude, Gemini, dan ChatGPT.

Situsnya statis polos (`index.html` + `skills.js`) — tanpa build, tanpa server. File .zip tiap skill dibuat langsung di browser pengunjung saat tombol download diklik.

## Isi

- Desain Presisi Parametrik — Indra Erlangga
- Remotion Motion Graphics — Komunitas
- Kurasi Perpustakaan Suara — Indra Erlangga
- Cek Ekor TTS — Indra Erlangga
- AI Cat Prompt Generator — Nalarka (Komunitas)
- Motion Graphics Explainer — Nalarka (Komunitas)
- Seedance 2.5 Prompt Generator — Nalarka (Komunitas)

## Cara pasang skill

1. Download file .zip skill yang diinginkan (jangan diekstrak).
2. Di claude.ai, buka Settings → Capabilities.
3. Pastikan "Code execution and file creation" aktif.
4. Di bagian Skills, pilih Upload skill, lalu pilih file .zip-nya.
5. Buka chat baru dan minta seperti biasa.

Cara tempel (AI apa saja): buka skill di situs, klik "Baca isi skill", salin semua teksnya, tempel di awal chat baru, lalu tulis permintaanmu di bawahnya.

## Menjalankan situs

Deploy folder ini ke static host apa pun (Vercel, Netlify, GitHub Pages). Di Vercel: New Project → Import repository ini → Deploy, tanpa pengaturan build apa pun.
