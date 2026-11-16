# Menara U2 — Property Reel (SPEC)

GOAL:    Penonton berhenti scroll pada view tingkat 29, faham unit ni lengkap & murah (RM295K), dan WhatsApp Khairul Aswad.
OUTPUT:  HyperFrames, 1080 x 1920 (9:16), 30 fps
TIME:    33.0 s x 30 = 990 frames. Tiada muzik dalam projek (lihat nota bunyi).

## Transcript
Semua 7 klip ialah B-roll walkthrough tanpa dialog. ASR (Whisper small, ms + en) hanya kesan bunyi ambien
(kipas, aircond, angin) — tiada perkataan. Jadi teks atas skrin bawa cerita; audio asal footage di-mute.

| Klip | Fail asal | Isi | Bahagian dipakai |
| --- | --- | --- | --- |
| c1 | VID_112907 | Lobi kaca Menara U2 | 0.6–2.6 (lobi), 2.6–5.2 slow 0.65x (kemudahan) |
| c2 | VID_114717 | Bilik master | 1.4–3.4 (bilik 1), 3.3–5.0 slow 0.6x (sesuai untuk) |
| c3 | VID_114725 | Bilik air | 1.8–3.4 (buang 1.8 s awal: bingkai pintu goyang) |
| c4 | VID_114733 | Ruang tamu + TV | 0.8–3.0 (ruang tamu), 2.85–4.85 slow 0.5x (detail unit) |
| c5 | VID_114745 | View balkoni tingkat 29 | 3.3–6.3 (HOOK), 0.4–4.6 slow 0.55x (harga + CTA) |
| c6 | VID_114757 | Ruang makan + dapur | 0.3–2.3 |
| c7 | VID_114810 | Bilik 2 (katil dua tingkat) | 0.6–2.4 |

Dibuang: permulaan setiap klip yang goyang/masuk pintu, hujung pan yang berulang, ~10 s footage mati.

## LOOK — "Emerald & Champagne"
- Ink #FFFFFF, accent champagne gold #E3B866 (hanya pada harga, nombor & satu perkataan per skrin), panel emerald #0B3029 @ 92%.
- Display: League Gothic (tajuk/nombor, 150–300 px), body: Montserrat 700/900 (36–96 px).
- Scrim emerald gelap dari bawah (0 → 85%) supaya teks boleh dibaca atas footage terang.
- Teks semua dalam band 168–1330 px (UI TikTok/Reels), margin kiri 72 px.

## MOTION
- Masuk: expo.out 0.3–0.45 s; keluar: power2.in 0.15–0.2 s blur-out. Stagger perkataan 70 ms, item senarai 90 ms.
- Peralihan footage (root timeline, wrapper .cam): whip menegak, whip melintang, zoom-through, panel cover, flash, kad mengecil.

## SHOTS
| Masa | Footage | Overlay | SFX |
| --- | --- | --- | --- |
| 0.0–3.0 | c5 view | HOOK "BAWAH RM300K" (frame 0 dah ada) + "dapat view tingkat 29 macam ni?" | impact 0.0 |
| 3.0–5.0 | c1 lobi | Pin + MENARA U2 / Seksyen 13, Shah Alam / Dekat MSU & AEON Mall | whoosh, pop |
| 5.0–7.2 | c4 ruang tamu | RUANG TAMU · 450 sq ft · Basic Fully Furnished | whoosh |
| 7.2–9.2 | c6 makan | RUANG MAKAN & DAPUR · Siap perabot asas | whoosh |
| 9.2–11.2 | c2 bilik 1 | BILIK TIDUR 1 · Master, ada aircond | zoom whoosh |
| 11.2–13.0 | c7 bilik 2 | BILIK TIDUR 2 · Muat 2 orang | whoosh |
| 13.0–14.6 | c3 bilik air | BILIK AIR · Shower kaca | zoom whoosh |
| 14.6–18.6 | c4 slow | Panel DETAIL UNIT 6 tile (29 / 450 / 2 / 1 / 1 / RM225) + Leasehold | cinematic whoosh, pops |
| 18.6–22.6 | c1 slow | Panel KEMUDAHAN 7 item + ikon | whoosh, soft ticks |
| 22.6–25.4 | c2 slow | SESUAI UNTUK x3 | whoosh, pops, riser |
| 25.4–28.4 | c5 slow | HARGA RM295,000 slam + flash | impact |
| 28.4–33.0 | c5 dalam kad | CTA Khairul Aswad / 012-402 3764 / Bro Hartanah | cinematic whoosh, pop, sparkle |

BANNED: void gelap kosong, glow/neon, gradient ungu/biru, emoji sebagai ikon, tajuk yang terus bergerak lepas mendarat, semua elemen fade+slide-up.
QA: frame 0 (hook terbaca), 3.4, 6.0, 10.0, 16.5, 21.0, 24.0, 26.5, 31.5.
