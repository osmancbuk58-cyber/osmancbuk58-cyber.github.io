# Cep · Pediatri Portal

10 araç hub sayfası. Tek ikon ana ekranda — `osmancbuk58-cyber.github.io/` adresi.

## İçerik

**Hesaplama & Doz** (3 araç)
- Sıvı-Cep · DKA-Cep · YB-İnfüzyon

**Yorum** (3 araç)
- Kan Gazı · EKG · Tübül

**Acil Refleks** (2 araç)
- Acil-Cep · Solunum-Cep

**Karar Destek** (2 araç)
- Skor-Cep · Antropometri-Cep

## Özellikler

- **Arama:** Türkçe karakter normalize (ı→i, ş→s gibi). Araç adı + tanım + anahtar kelime içinde arama
- **Renk kodlu kartlar:** kategoriye göre sol kenar rengi
- **Versiyon göstergesi** her kartta
- Kartlara tıklanınca araç yeni sekmede açılır

## ÖZEL DEPLOY — User Pages

Bu portal **özel bir repo adı** gerektiriyor. Diğer araçlar gibi normal repo değil.

### Adımlar:

1. GitHub'da yeni repo aç → ad **kesinlikle**: `osmancbuk58-cyber.github.io` (kullanıcı adın + `.github.io`)
2. Public seç, README/gitignore ekleme
3. Bu klasördeki 4 dosyayı (index.html, manifest.json, README.md, .gitignore) yükle → Commit
4. Settings → Pages → Source: Deploy from branch → main → `/ (root)` → Save
5. 1-2 dakika sonra **doğrudan** `https://osmancbuk58-cyber.github.io/` adresinde aktif olur (alt klasör yok!)

### Telefon

Safari/Chrome ile aç → Paylaş → "Ana Ekrana Ekle"
İkon "Cep" diye görünür. Tek ikon, içeride 10 araç.

## Mevcut araçları silmek istersen

İstersen telefondan tek tek araçların PWA kısayollarını silebilirsin, sadece "Cep" portalı kalır. Veya hepsini koruyabilirsin, sık kullandığını ana ekrana, diğerlerini portala bırakabilirsin.

Repolar aynen kalıyor — silmiyoruz, sadece portal üzerinden erişim açılıyor.
