# SAMUDER – Static Site + Decap (Netlify) CMS

## Kurulum
1) Bu klasörü GitHub'a gönderin (branch: `main`).
2) Netlify → **New site from Git** → repo'yu bağlayın → deploy edin.
3) Netlify → **Identity**: Enable edin → Registration: Invite only.
4) Netlify → **Identity → Invite users**: e-posta adresinizi davet edin.
5) Netlify → **Identity → Services → Git Gateway**: Enable edin.
6) Gelen davet e-postasındaki linke tıklayıp şifre oluşturun.
7) Artık `https://site-adresiniz/admin` üzerinden giriş yapabilirsiniz.

## Kontrol listesi
- `https://site-adresiniz/admin/config.yml` dosyası **200** dönmeli.
- `https://site-adresiniz/content/news.json` **200** dönmeli.
- Kimlik doğrulama açılmazsa sayfada **Netlify Identity** popup'ı görünmeli.

## İçerik
- Haberler ve Etkinlikler 10'arlı sayfalanır. YENİ ekledikleriniz en üstte görünür.
- Galeride görsel tıklanınca büyür ve **İndir** butonu çıkar.
- Bağış bölümünde **IBAN kopyala** çalışır.
