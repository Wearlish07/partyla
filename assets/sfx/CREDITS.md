# Ses kayıtları

Oyundaki efekt sesleri gerçek kayıtlardan kesilip kısaltıldı (mono MP3). Dosya adı `<ses>-<varyant>.mp3`.

| Dosyalar | Kaynak | Lisans |
|---|---|---|
| `shot-*` (tabanca, altıpatlar, tüfek, çifte, makineli) | "The Free Firearm Sound Library", Still North Media (mirror: github.com/buddingmonkey/FreeFirearmsSFXLibrary) | CC0 |
| `step-*`, `land`, `punch`, `punch-hard`, `glass`, `whoosh`, `splat`, `dry`, `latch`, `metal`, `shell`, `cloth`, `bark`, `scrape`, `notify`, `ui`, `win`, `fanfare`, `lose`, `splash`, bir `thud` ve bir `coins` | "Oculus Audio Pack 01" by Oculus VR, LLC (https://developers.meta.com/vr/downloads/package/oculus-audio-pack-1/), licensed under CC BY 4.0. Files renamed to the UCS naming convention; OGG previews transcoded from the original WAVs. Oyun için kesildi ve MP3'e çevrildi. | CC BY 4.0 |
| `flesh`, `clank`, `glass-hit`, `thud`, `cock`, `coins`, `boom` | Kenney (kenney.nl): Impact Sounds, RPG Audio, Sci-Fi Sounds | CC0 |
| `../audio/amb-*` (ortam döngüleri) | "Oculus Audio Pack 01" by Oculus VR, LLC, CC BY 4.0 (yukarıdaki gibi). Döngü olacak şekilde kesildi. | CC BY 4.0 |

Mekan yankısı (reverb) dosya değil, kodla üretilir (`js/sfx.js`).

## Müzik

| Dosya | Kaynak |
|---|---|
| `../audio/music-bar.mp3` (bar piyanosu), `../audio/music-tension.mp3` (son anların gerilim müziği) | Oyun için bestelendi; piyano sesleri "Meta Piano", Meta Open Sound (github.com/facebookincubator/Meta-open-sound), CC0. Gerilim müziğindeki alçak darbe kodla üretildi. |
| `../audio/menu-waltz.mp3` | Kendi bestemiz (FluidR3 GM, CC-BY 3.0) |
