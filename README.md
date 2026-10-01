# Turkish Film Sources - Nuvio Eklenti Deposu

Bu depo, **Nuvio** uygulaması için Türkçe film, dizi ve anime sağlayıcılarını (scraper) içeren hazır bir eklenti deposudur (plugin repository).

## 🍿 İçerdiği Sağlayıcılar
* **FullHDFilmizlesene** (Film)
* **HDFilmCehennemi** (Film & Dizi)
* **FilmModu** (Film)
* **DiziBox** (Yabancı Dizi)
* **DiziFilmizle** (Film & Dizi)
* **DDizi** (Yerli & Yabancı Dizi)
* **DiziYou** (Yabancı Dizi)
* **AnimeciX** (Anime)

---

## 🚀 GitHub'a Yükleme ve Nuvio'ya Ekleme Adımları

### 1. GitHub'da Yeni Bir Repo Oluşturun
1. [github.com/new](https://github.com/new) adresine gidin.
2. Repo adına örneğin **`turkish-sources`** deyin.
3. Repoyu **Public** (Herkese Açık) seçin ve oluşturun.

### 2. Kodları GitHub Reponuza Gönderin
Bu klasörde PowerShell veya Terminal açıp şu komutları sırayla çalıştırın:
```bash
git remote add origin https://github.com/KULLANICI_ADINIZ/turkish-sources.git
git branch -M main
git push -u origin main
```

### 3. Nuvio'ya Ekleyin
Repo yüklendikten sonra:
1. Manifest linkiniz şu şekilde olacaktır:  
   `https://raw.githubusercontent.com/KULLANICI_ADINIZ/turkish-sources/main/manifest.json`
2. Nuvio uygulamasını açın.
3. **Ayarlar (Settings)** > **Plugins (Eklentiler)** > **Sağlayıcı Ekle (Add Provider)** kısmına gidin.
4. Yukarıdaki `manifest.json` bağlantınızı yapıştırıp kaydedin!
