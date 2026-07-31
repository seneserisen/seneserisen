<h1 align="center">Enes Erisen</h1>

<p align="center">
  <strong>Otonomi Teknolojileri Yüksek Lisansı · Robotik, Sensör Füzyonu ve Kontrol</strong>
</p>

<p align="center">
  ROS 2 · Kamera/LiDAR/Radar Verisi · Durum Kestirimi · Mühendislik Yazılımı
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=20&amp;pause=1000&amp;color=2F81F7&amp;center=true&amp;vCenter=true&amp;width=820&amp;lines=Robotik+%C2%B7+Otonom+Sistemler+%C2%B7+Sens%C3%B6r+F%C3%BCzyonu;ROS+2+%C2%B7+Kontrol+%C2%B7+G%C3%B6m%C3%BCl%C3%BC+Sistemler;%C3%96l%C3%A7%C3%BClebilir+ve+Tekrar+%C3%9Cretilebilir+M%C3%BChendislik+Yaz%C4%B1l%C4%B1m%C4%B1" alt="Robotik, otonomi ve mühendislik odağı" />
</p>

---

FAU'da Otonomi Teknolojileri yüksek lisans öğrencisiyim ve Atılım Üniversitesi Elektrik-Elektronik Mühendisliği lisans mezunuyum. Ana portföyüm robotik, otonom sistemler, sensör verisi, kontrol, gömülü sistem temelleri ve tekrar üretilebilir mühendislik yazılımına odaklanıyor.

Projelerde varsayımların, hata durumlarının ve doğrulama sınırlarının açık kalmasına önem veriyorum. Aşağıdaki çalışmaların çoğu deterministik simülasyon, sentetik veri veya açık veri kümelerine dayanır; fiziksel sistem kurulumu ya da üretim ortamı deneyimi iddiası değildir.

## Güncel çalışmalar

- **Autonomous Sensor Fusion Lab** — doğrulanmış nuScenes kamera, LiDAR ve radar veri temelini; LiDAR başlangıç yöntemleri, radar eşleştirme ve takip çalışmalarına doğru geliştiriyorum. Veri/kalibrasyon altyapısı uygulanmış durumda; algılama ve takip henüz uygulanmadı.
- **FaultNav ROS 2** — deterministik mobil robot ve sensör arızası simülasyonunu ROS'tan bağımsız EKF, ölçüm güncellemeleri ve innovation izleme yönünde geliştiriyorum. Kestirici şu anda plan aşamasında.

## Seçili mühendislik projeleri

| Proje | Uygulanan çalışmalar | Durum ve sınırlar |
| --- | --- | --- |
| [Autonomous Sensor Fusion Lab](https://github.com/seneserisen/autonomous-sensor-fusion-lab) | Deterministik nuScenes tablo işleme, zaman damgası kontrolleri, sensör/araç/global koordinat dönüşümleri, kamera üzerinde LiDAR/radar izdüşümü ve kuşbakışı görselleştirme. | **Aktif, v0.1 temeli.** Gerçek nuScenes mini çalıştırması bekliyor; nesne algılama, takip veya fiziksel sensör doğrulaması iddia edilmiyor. |
| [FaultNav ROS 2](https://github.com/seneserisen/ros2-autonomous-mobile-robot) | Diferansiyel sürüş modeli, enkoder ve IMU simülasyonu, arıza enjeksiyonu, enkoder odometrisi, ROS 2 odometri/TF, raporlar ve testler. | **Aktif.** Kontrollü yazılım simülasyonu; EKF, fizik simülasyonu, SLAM, Nav2 ve donanım çalışmaları gelecek aşamalardır. |
| [Automatic Control Laboratory](https://github.com/seneserisen/automatic-control-lab-projects) | Beş kontrol çalışması, LQR, gözleyiciler, doyum ve anti-windup, bağımsız Python referansları ve taşınabilir C99 uygulamaları. | **Sürdürülüyor.** MATLAB, Python ve C yazılım doğrulaması; donanım veya üretim kontrolcüsü iddiası yoktur. |
| [Industrial Quality Anomaly Monitor](https://github.com/seneserisen/industrial-quality-anomaly-monitor) | Sentetik üretim verisi, global ve makine bazlı robust yöntemler, Isolation Forest, aynı veri üzerinde karşılaştırma, Docker ve testler. | **Aktif.** Sentetik karşılaştırma kanıtı; gerçek fabrika performansı değildir. |
| **Power Electronics Manufacturing** | Kesme eğrisi ön işleme, özellik çıkarımı, toplu analiz, aykırı değer incelemesi, proses yeterlilik kontrolleri ve Weibull analizi. | **Sürdürülüyor, özel depo.** Genel/sentetik veri; gizli ya da üretim doğrulama verisi içermez. |

## Geliştirilmesi planlanan temeller

- **Embedded BMS and CAN Simulator** — yalnızca teknik kapsam ve kilometre taşı planı mevcut. C++ batarya modeli, koruma durum makinesi ve sanal CAN akışı henüz uygulanmadı.
- **Radar / ISAR Classification Pipeline** — yalnızca teknik kapsam ve kilometre taşı planı mevcut. Veri işleme, sınıflandırma temelleri ve değerlendirme henüz uygulanmadı.

## Teknik kanıt

| Alan | Gösterilen araç ve yöntemler |
| --- | --- |
| **Robotik ve otonomi** | Python, ROS 2 arayüzleri, diferansiyel sürüş, sensör/arıza simülasyonu, odometri, TF ve deterministik senaryolar |
| **Otonom sürüş verisi** | nuScenes devkit, kamera/LiDAR/radar kalibrasyonu, koordinat dönüşümleri, zaman damgası kontrolleri ve izdüşüm |
| **Kontrol ve gömülü temeller** | MATLAB, durum uzayı yöntemleri, LQR, gözleyiciler, sayısal integrasyon, anti-windup, C99 ve CMake/CTest |
| **Üretim analitiği** | NumPy, pandas, scikit-learn, robust istatistikler, Isolation Forest, eğri analizi ve Weibull modelleme |
| **Mühendislik iş akışı** | pytest, Ruff, GitHub Actions, Docker, komut satırı araçları ve tekrar üretilebilir raporlar |

## Çalışma yaklaşımım

- Gerçek durumu, ölçümleri, kestirimleri ve değerlendirme verisini birbirinden ayırmak.
- Birimleri, koordinat sistemlerini, zaman damgalarını ve varsayımları açıkça belgelemek.
- Sonuç yayımlamadan önce deterministik senaryolar ve otomatik testler kullanmak.
- Hatalı veya reddedilen veriyi sessizce silmek yerine görünür tutmak.
- Yazılım kanıtı ile gerçek dünya doğrulamasını birbirine karıştırmamak.

## Katkı etkinliği

<p align="center">
  <img src="https://raw.githubusercontent.com/seneserisen/seneserisen/main/profile-3d-contrib/profile-night-rainbow.svg" alt="3B katkı takvimi" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/seneserisen/seneserisen/main/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/seneserisen/seneserisen/main/output/github-contribution-grid-snake.svg" />
    <img src="https://raw.githubusercontent.com/seneserisen/seneserisen/main/output/github-contribution-grid-snake.svg" alt="Hareketli katkı yılanı" />
  </picture>
</p>

---

<p align="center">
  <strong>Mühendislik kanıtı ölçülebilir, test edilebilir ve tekrar üretilebilir olmalıdır.</strong><br />
  <a href="https://github.com/seneserisen">github.com/seneserisen</a>
</p>
