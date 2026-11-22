# Online Telefon 📱

Telefonda tam ekran açılan, GTA Online tarzı bir oyun içi telefon. Rehber, arama ekranı, telesekreter ve rastgele ses çalma özelliği var.

**Canlı adres:** https://yusufkaancelik.github.io/gta-telefon/

Telefonda aç, sonra **Paylaş → Ana Ekrana Ekle** de. Uygulama gibi tam ekran açılır.

## Ses ekleme
Her kişinin bir klasörü var: `sounds/<id>/`. Dosyaları **1.mp3, 2.mp3, 3.mp3…** diye numaralandırıp at. Kod onları kendisi bulur. Birden fazla dosya varsa her aramada rastgele birini çalar ve aynı sesi art arda iki kez çalmaz.

| Mod | Ne olur |
|---|---|
| `vm` (telesekreter) | 2–3 kez çalar, sonra kişinin kendi telesekreter sesi çalar, ardından bip sesi gelir. Ses dosyası yoksa Türkçe bir "şu anda ulaşılamıyor" anonsu okunur. |
| `ans` (açar) | 1 kez çalar, açılır ve rastgele bir ses çalar. LS Customs, Mechanic, Pegasus gibi kişiler bu modda. |

Örnekler: `sounds/lester/1.mp3`, `sounds/lscustoms/1.mp3`, `sounds/lscustoms/2.mp3` …

GitHub'da yüklemek için: **Add file → Upload files**, sonra klasörü komple sürükle.

İsteğe bağlı sistem sesleri: `sounds/_system/ring.mp3` (çalma sesi) ve `sounds/_system/beep.mp3`. Bunlar yoksa sesler tarayıcıda üretilir.

Desteklenen formatlar: mp3, m4a, ogg, wav

## Avatar ekleme
`avatars/<id>.jpg` (veya .png / .webp). Avatar yoksa kişinin baş harfleri gösterilir.

## Kişi ekleme / mod değiştirme
`index.html` içindeki `CONTACTS` listesini düzenle: `["id","Görünen Ad","vm" veya "ans"]`

Kişilerin id'leri: agatha, agent14, agentulp, benny, brucie, charlie, dax, dave, downtowncab, franklin, gerald, hao, imani, lamar, lester, lscustoms, lupe, malc, madrazo, mechanic, merryweather, miguel, moodymann, mors, paige, pavel, pegasus, ron, sessanta, simeon, tony, trevor, vincent, yung

> Hayran projesidir. Oyunun ses ve görsellerini koyacaksan haklarının Rockstar Games'e ait olduğunu unutma.
