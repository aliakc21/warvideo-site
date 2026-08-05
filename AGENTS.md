# AGENTS.md — Warvideo Site (CANLI)

**Bu depo canlı web sitesidir: https://warvideo.app**
Depo: `github.com/aliakc21/warvideo-site` (public) · GitHub Pages · yayın dalı **`main`** · `CNAME` burada.

## ⚠️ En önemli kural
`main`'e push = **anında canlıya çıkar.** Kullanıcı onayı olmadan içerik yayınlama.

## ⚠️ Karıştırma tuzağı (bir kez yaşandı)
`../warvideo-mac/website/` klasöründe **sitenin eski bir kopyası** duruyor ama
**oradan yayın yapılmıyor** (o depoda Pages yok — API 404 döner).
Site değişikliği **yalnızca burada** yapılır. Yanlış depoyu düzenlersen değişiklik
canlıya hiç çıkmaz ve fark etmesi zordur.

## Yapı
```
index.html · privacy.html · support.html · 404.html · styles.css
appcast.xml (Sparkle güncelleme akışı) · CNAME · assets/ · download/ · samples/ · addon/
```
Sayfalar aynı sınıfları paylaşır: `site-header` `legal-page` `legal-hero` `legal-content` `site-footer`.
Yeni sayfa eklerken bu yapıyı ve `styles.css`'i kullan.

## Her oturumda
1. **Başlarken:** `git pull --no-rebase` → `AGENTS.md` + `DURUM.md` oku.
2. **Bitirirken:** `DURUM.md` güncelle → add → commit → pull → push.
   Push'tan sonra yayını doğrula: `gh api repos/aliakc21/warvideo-site/pages/builds`
   (durum `built` olmalı) ve sayfayı canlı adresten kontrol et.

## Yasaklar
- Onay olmadan dosya silmek.
- Sır commit etmek (bu depo **public** — hiçbir anahtar/token girmemeli).
- 100 MB üstü tek dosya (örn. örnek video) — `samples/` içine büyük dosya koyma.

## Ortak log
`AI-Ortak-Log/MASTER_LOG.md` sonuna: `[YYYY-MM-DD HH:MM] [CLAUDE] [02_Warvideo_APP] özet`
