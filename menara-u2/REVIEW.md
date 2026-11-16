# REVIEW — Menara U2 reel (preview, belum final render)

## Keputusan kreatif
- **Transcript**: 7 klip = B-roll tanpa dialog (Whisper small ms/en hanya kesan kipas/aircond/angin). Audio asal di-mute; teks atas skrin bawa cerita.
- **Hook**: view balkoni tingkat 29 (shot paling kuat) + "BAWAH RM300K — dapat view tingkat 29 macam ni?" dah ada pada frame 0 (thumbnail).
- **Struktur 33 s**: Hook → Lokasi (lobi) → walkthrough 5 bilik (1.6–2.2 s setiap satu) → Detail unit → Kemudahan → Sesuai untuk → Harga slam → CTA ejen.
- **Dibuang**: permulaan klip yang goyang/lalu bingkai pintu, hujung pan berulang. Klip dipakai semula hanya sebagai latar perlahan (0.5–0.65x) di bawah panel.
- **Style "Emerald & Champagne"**: emerald #0B3029, emas #E3B866, League Gothic + Montserrat.
- **Peralihan**: whip menegak, whip melintang (kiri/kanan), zoom-through, panel cover, flash pada harga, footage mengecil jadi kad pada CTA.
- **SFX** (bundled, Pixabay license): impact pada hook & harga, whoosh pendek pada setiap peralihan, pop pada pin/tile/checkbox, tick lembut pada senarai kemudahan, riser ke harga, sparkle di hujung.

## Diukur vs dilihat
- `hyperframes check`: 0 error. Snapshot review (beats, seams, phone width) dilihat.
- Bunyi diukur (titik puncak setiap SFX disusun 1 frame selepas visual), **belum didengar**.

## Amaran yang dikekalkan (sengaja)
- `duplicate_audio_track` (23): SFX bertindih sengaja (riser→impact, pop berturutan).
- `outside_safe_zone` (8): hujung kanan beberapa baris melepasi had YouTube Shorts 888 px / TikTok kanan; masih bebas dari rail ikon sebenar.
- `line_unread` lobi: 10 perkataan dalam 2.4 s — nama & lokasi juga muncul semula di CTA/harga.

## Paling lemah / kalau ada masa
- Tiada muzik latar: katalog HeyGen perlukan sign-in dan host disekat dalam environment ni. Cadangan: letak trending audio dalam TikTok/IG, atau beri fail MP3 untuk dimasukkan sebagai `<audio id="bgm">`.
- Shot bilik air paling pendek (1.6 s).

## Revisi 2 (maklum balas: buang bunyi macam ombak, kecilkan tulisan)
- Whoosh-cinematic (bunyi mengembang macam ombak) dibuang dari 5 peralihan, diganti whoosh pendek. Riser sebelum harga dikekalkan.
- Semua saiz font scene x0.8 (minimum 28 px). Scrim gelap dipendekkan & dinipiskan (~0.8 → ~0.3 di kawasan teks), panel detail/kemudahan lebih kecil (x 150–930) dan 82% legap, dim latar 0.12.
- Label kecil tag bilik kini atas latar emerald kecil supaya terbaca atas dinding terang.
- Kad gambar CTA dibesarkan (190–750 px).
- Amaran baru dikekalkan: contrast_aa (RM300K, UNTUK) kerana scrim lebih nipis atas permintaan; text-shadow membantu.
