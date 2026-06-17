# 🎮 Bensu'nun Arenası — Bensu Date

Bensu'ya özel, Clash Royale temalı interaktif bir sürpriz sayfa. 5 anı kartını aç, iksir barını doldur, efsanevi sandığı aç ve soruyu sor!

## Özellikler

- **Clash Royale estetiği** — Koyu arena teması, nadirlik sistemli kartlar, mor iksir barı
- **Purple Elixir Golem teması** 💜 — Furkan'ın en sevdiği CR karakterine özel
- **5 anı kartı** — Mandalina & Kalem, Yer Fıstığı, Telefon Süsü, Clash & İksir Golemi, İlk Yemek
- **İksir barı** — Her kart açıldıkça dolan mor iksir barı
- **Efsanevi Sandık** — Tüm kartlar toplanınca açılan ödül sandığı
- **Kaçan "Hayır" butonu** — Üzerine gelince kaçar, yazısı değişir
- **Partikül efektleri** — Confetti, kalp yağmuru, patlama animasyonları
- **8-bit ses efektleri** — Web Audio API ile sentezlenmiş CR tarzı sesler

## Nasıl Çalıştırılır?

```bash
# Projeyi clone'la
git clone https://github.com/Flancy1/bensu-date.git
cd bensu-date

# Herhangi bir HTTP sunucusu ile aç
python3 -m http.server 8080
# Tarayıcında http://localhost:8080 adresine git
```

Veya direkt `index.html`'i tarayıcında aç (Google Fonts için internet gerekli).

## Teknolojiler

- Saf HTML + CSS + JavaScript (tek dosya, framework yok)
- Canvas API (partikül sistemi)
- Web Audio API (ses sentezi)
- Clash Royale görsel tasarım dili

## Lisans

MIT