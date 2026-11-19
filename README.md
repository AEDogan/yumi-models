# Yumi Models — karakter paketleri

> **Bu modeller [Yumi](https://github.com/AEDogan/Yumi_v1.0) için yapılmıştır.** Paketler yalnız Yumi masaüstü sesli
> asistanında çalışır; önce Yumi'yi kurun: **[github.com/AEDogan/Yumi_v1.0](https://github.com/AEDogan/Yumi_v1.0)**

[Yumi](https://github.com/AEDogan/Yumi_v1.0) masaüstü sesli asistanı için hazır karakter paketleri (`.yumipaket`).
Her paket karakterin 3D modelini (VRM), kendine ait ince ayarlı sesini (XTTS) ve lisans kayıtlarını birlikte getirir.
Yumi paketsiz de çalışır (varsayılan Yumi sesiyle); paket ekleyince karakterler masaüstünde dolaşır, konuşur, oturur.

> **English:** Ready-to-install character packs for the Yumi desktop voice assistant: VRM avatars with their own
> fine-tuned XTTS voices. Download from **Releases**, then in Yumi: *Model → + Paket ekle* (Add package).

## Paketler

| Paket | İçerik | Boyut | İndir |
|---|---|---|---|
| **Anime seti** `anime-1.1.0` | 10 karakter, her biri kendi sesiyle | ~17,2 GB (9 parça) | [Releases → anime-1.1.0](../../releases/tag/anime-1.1.0) |

### Anime setindeki karakterler

| Karakter | Ses | Model lisansı |
|---|---|---|
| Yumi | Yumi sesi (kadın) | pixiv örnek model koşulları |
| Haru | Haru sesi (kadın) | pixiv örnek model koşulları |
| Sora | Sora sesi (erkek) | pixiv örnek model koşulları |
| Vita | Vita sesi (kadın) | CC0 |
| Vivi | Vivi sesi (kadın) | CC0 |
| Ren | Ren sesi (erkek) | CC0 |
| Akira | Akira sesi | CC0 |
| Shiori | Akira sesi | CC0 |
| Kaito | Kaito sesi (erkek) | VRoid Hub lisansı (serbest) |
| Eddy | Eddy sesi (erkek) | VRoid Hub lisansı (atıf gerekli — aşağıda) |

## Kurulum

1. **Anime seti:** Releases sayfasından `anime-1.1.0.yumipaket.001` … `.009`, `anime-1.1.0.yumipaket.sha256.txt` ve
   `BIRLESTIR.cmd` dosyalarını **aynı klasöre** indirin. `BIRLESTIR.cmd`'yi çalıştırın; parçalar birleşir ve sha256 ile
   doğrulanır (`TAMAM` yazısını görünce parçaları silebilirsiniz). GitHub tek dosyada 2 GB sınırı koyduğu için set parçalı.
2. Yumi'de **Model → + Paket ekle** ile paketi seçin (ya da dosyayı pencereye sürükleyip bırakın). Ekleme arka planda
   sürer; Yumi bu sırada çalışmaya devam eder. Kurulumda her dosyanın sha256'sı denetlenir.

Gereken: Yumi v1.0, Windows 10/11 x64. Anime sesleri için ekran kartı önerilir (işlemciyle de çalışır, daha yavaş).

## Lisanslar ve atıflar

- Karakter modellerinin her birinin lisansı kendi VRM dosyasının içindeki kayıttan okunmuştur; ayrıntı ve bağlantılar
  paketin içinde `_ortak/LICENSES.md` ve her karakterin `karakter.json` → `kaynak.lisans` alanında.
- **Atıf:** Eddy modeli: "Test" — Animeit (VRoid Hub).
- CC0 modeller: [madjin/vrm-samples](https://github.com/madjin/vrm-samples). pixiv örnek modelleri (AvatarSample A/B/C)
  CC0 değildir; [pixiv koşulları](https://vroid.pixiv.help/hc/en-us/articles/4402614652569) geçerlidir (örnek dosya tek başına satılamaz).
- Sesler XTTS v2 üzerine ince ayarlıdır; XTTS v2 modeli [Coqui Public Model License](https://coqui.ai/cpml) ile gelir
  (yalnız ticari olmayan kullanım). Bu paketler ücretsizdir ve ticari kullanım için değildir.

Paketler kişisel, ücretsiz kullanım içindir; satılamaz.
