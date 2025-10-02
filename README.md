# Coming Soon — angelesyaşam

Bu depo, geçici “Yakında” sayfasını barındırır.

## Yayınlama — GitHub Pages
1. Bu dosyaları bir GitHub reposuna yükle (örn: `angelesyasam-coming-soon`).
2. **Settings → Pages** bölümüne gir.
3. **Source**: `Deploy from a branch`, **Branch**: `main` ve `/ (root)` seç.
4. Kaydet; GitHub Pages adresin `https://<kullanici>.github.io/<repo>/` şeklinde oluşur.

## Özel Alan Adı Bağlama (Cloudflare)
- Cloudflare DNS’te `www` için bir **CNAME** kaydı ekle → hedef: `<kullanici>.github.io` (turuncu bulut açık).
- İstersen apex (`xn--angelesyaam-zgc.com`) için Cloudflare **CNAME flattening** veya bir “A” kaydı (dummy/Pages IP) kullan.
- **SSL/TLS Mode**: geçici olarak `Flexible`. Sunucunu kurduğunda `Full (Strict)` yap.
- **Always Use HTTPS** ve **Automatic HTTPS Rewrites** seçeneklerini `On` yap.

## Düzenleme
- Metin ve renkler `index.html` ve `styles.css`'te.
- Logo `logo.svg` dosyası.
