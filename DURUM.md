# DURUM — Warvideo Site

> Son güncelleme: 2026-07-27

## Proje nedir
**Canlı web sitesi:** https://warvideo.app — GitHub Pages, depo `aliakc21/warvideo-site` (public),
yayın dalı `main`. Warvideo'nun tanıtım + yasal sayfaları.

## Şu anki durum
- `index.html` (tanıtım), `privacy.html`, `support.html`, `404.html`, `appcast.xml` (Sparkle).
- **27 Tem:** `privacy.html` + `support.html` **Windows / Microsoft Store'u da kapsayacak**
  şekilde güncellendi ve yayınlandı. Gerekliydi: eski metin yalnızca "Mac app" ve "Apple
  subscriptions" diyordu; Windows uygulaması Microsoft Store'a gönderilirken bu platform
  uyuşmazlığı sertifikasyonda **red sebebi** olabilirdi.
  Eklenenler: her iki platform + mağaza, combat-log'un yerelde okunduğu maddesi, opt-in paylaşım
  (Discord) maddesi, Windows izinleri, Microsoft Store abonelik iptali, companion addon SSS'i.

## Sıradaki adım
- Windows sürümü Store'da yayına girince `index.html`'e **Windows indirme/rozet** bölümü eklenecek
  (şu an site yalnızca Mac App Store'u gösteriyor).

## Bilinen tuzak
`../warvideo-mac/website/` altında sitenin **yayınlanmayan eski bir kopyası** var. Site
değişikliği **yalnızca bu depoda** yapılır — ayrıntı: AGENTS.md.
