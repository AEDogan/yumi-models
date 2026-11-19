# Anime paketi — karakter dosyaları ve lisansları

Son güncelleme: 19 Kasım 2026. Bu dosya `anime` paketinin parçasıdır (`_ortak/`, pakete olduğu gibi girer).

Bu karakterler üçüncü taraf eserleridir, Yumi tarafından çizilmemiştir. Yumi'deki adları (Akira, Haru…) yalnız
uygulama içi addır; özgün başlık ve yazar aşağıda. Yumi kodunun lisansı bu dosyaların koşullarının yerine geçmez.
Lisans bilgisi her VRM dosyasının kendi içindeki kayıttan (`meta`) okunmuştur.

- Kaynak deposundan gelenlerin (madjin) adresi, SHA-256 değeri ve özgün kaydı: `kaynaklar.json`
- VRoid Hub / dışarıdan gelenlerin SHA-256 değeri: `guven.json`
- Her karakterin kısa lisans notu: `<Karakter>/karakter.json` → `kaynak.lisans`

## Paketteki karakterler

| Yumi adı | Özgün başlık | Yazar | Kaynak | Lisans | Ticari | Yeniden dağıtım |
|---|---|---|---|---|---|---|
| Akira | Sendagaya Shibu | — | madjin/vrm-samples | CC0 | Serbest | Serbest |
| Shiori | Sendagaya Shino | — | madjin/vrm-samples | CC0 | Serbest | Serbest |
| Ren | HairSample_Male | — | madjin/vrm-samples | CC0 | Serbest | Serbest |
| Vita | Vita | — | madjin/vrm-samples | CC0 | Serbest | Serbest |
| Vivi | Vivi | — | madjin/vrm-samples | CC0 | Serbest | Serbest |
| Yumi | AvatarSample_A | VRoid (pixiv) | madjin/vrm-samples | pixiv örnek model koşulları | Koşullara bağlı | Örnek dosya tek başına satılamaz |
| Haru | AvatarSample_B | VRoid (pixiv) | madjin/vrm-samples | pixiv örnek model koşulları | Koşullara bağlı | Örnek dosya tek başına satılamaz |
| Sora | AvatarSample_C | VRoid (pixiv) | madjin/vrm-samples | pixiv örnek model koşulları | Koşullara bağlı | Örnek dosya tek başına satılamaz |
| Kaito | SakuradaFumiriya_52bs | hinzka | VRoid Hub | VRoid Hub lisansı (1) | Serbest | Serbest, atıf gerekmez |
| Eddy | Test | Animeit | VRoid Hub | VRoid Hub lisansı (2) | Serbest | Serbest, **atıf gerekli** |

## Atıflar (zorunlu)

- Eddy modeli: "Test" — Animeit (VRoid Hub). Lisans atıf istiyor (`credit=necessary`); bu satır ve
  `Eddy/karakter.json` → `kaynak.atif` bu atıftır, paketle birlikte dağıtılır.

Atıf istemeyenler (CC0, Kaito) ve pixiv örnek modelleri (Yumi/Haru/Sora; ücretsiz dağıtımda serbest, örnek dosya tek başına
satılamaz) için de kaynak ve lisans bilgisi bu dosyada ve `karakter.json` kayıtlarında tutulur.

pixiv örnek model koşulları (AvatarSample A/B/C, CC0 değildir):
- https://vroid.pixiv.help/hc/en-us/articles/4402614652569
- https://vroid.pixiv.help/hc/en-us/articles/4402394424089

VRoid Hub lisans bağlantıları (dosya içi kayıttan, aynen):
1. Kaito: https://hub.vroid.com/license?allowed_to_use_user=everyone&characterization_allowed_user=everyone&corporate_commercial_use=allow&credit=unnecessary&modification=allow&personal_commercial_use=profit&redistribution=allow&sexual_expression=allow&version=1&violent_expression=allow
2. Eddy: https://hub.vroid.com/license?allowed_to_use_user=everyone&characterization_allowed_user=everyone&corporate_commercial_use=allow&credit=necessary&modification=allow&personal_commercial_use=profit&redistribution=allow&sexual_expression=allow&version=1&violent_expression=allow

Kaynak depo: https://github.com/madjin/vrm-samples, sabit sürüm `e16eb187100149a315ad92c3c9968f1d5baa6c7d`.

## Paketten çıkarılanlar

- Darkness Shibu, HairSample_Female, Victoria Rubin — kayıtları `kaynaklar.json` → `kaldirilan`.
- Orion, cryptovoxels, female vroid, masc vroid — eski listede vardı, pakette yok.
- Seed-san — ek mekanik kollar masaüstü duruş kabulünü geçmedi.
- meebit_09842 — kaynağı yeniden dağıtımı yasaklıyor.
