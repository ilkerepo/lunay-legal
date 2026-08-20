# Lunay — hukuki sayfalar

Lunay uygulamasının **Gizlilik Politikası** ve **Kullanım Koşulları**
sayfaları. Mağaza listelemelerinin (Google Play, App Store) istediği
herkese açık adresler burada yayımlanıyor:

- Gizlilik Politikası — <https://ilkerepo.github.io/lunay-legal/>
- Kullanım Koşulları — <https://ilkerepo.github.io/lunay-legal/terms/>

## Bu depo neden ayrı

Uygulamanın kaynak deposu **private**, ve GitHub Pages private depolarda
ücretli plan istiyor. Hukuki metinler ise tanımı gereği herkese açık —
bu yüzden yalnız onlar public bir depodan yayımlanıyor. Kaynak kodun
tamamı private kalıyor.

## Düzenleme kuralı

**Buradaki HTML dosyaları elle düzenlenmez.** Kaynağı uygulama deposunda:

```
auria_tarot/web/privacy/index.html        →  index.html
auria_tarot/web/privacy/terms/index.html  →  terms/index.html
```

Orada `docs/privacy_policy.md` ve `docs/terms_of_use.md` ile birlikte
güncelleniyor ve sözleşme testleri ikisinin ayrışmasını engelliyor.
Değişiklik yaptıktan sonra dosyaları buraya kopyalayıp gönder.

Yürürlük tarihi iki kopyada da aynı olmak zorunda; uygulama deposundaki
`test/legal_identity_test.dart` bunu denetliyor.
