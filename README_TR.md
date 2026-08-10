<h1 align="center">Enes Erisen</h1>

<p align="center">
  <strong>Otonomi Teknolojileri Yüksek Lisansı · Robotik, Sensör Füzyonu ve Kontrol</strong>
</p>

<p align="center">
  ROS 2 · Kamera/LiDAR/Radar Verisi · Durum Kestirimi · Mühendislik Yazılımı
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&amp;logo=c&amp;logoColor=black" alt="C" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&amp;logo=cplusplus&amp;logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/MATLAB-EF6C00?style=flat-square" alt="MATLAB" />
  <img src="https://img.shields.io/badge/ROS_2-22314E?style=flat-square&amp;logo=ros&amp;logoColor=white" alt="ROS 2" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&amp;logo=linux&amp;logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&amp;logo=cmake&amp;logoColor=white" alt="CMake" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&amp;logo=docker&amp;logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&amp;logo=githubactions&amp;logoColor=white" alt="GitHub Actions" />
</p>

---

FAU'da Otonomi Teknolojileri yüksek lisans öğrencisiyim ve Atılım Üniversitesi Elektrik-Elektronik Mühendisliği lisans mezunuyum. Ana portföyüm robotik, otonom sistemler, sensör verisi, kontrol, gömülü sistemler ve tekrar üretilebilir mühendislik yazılımına odaklanıyor.

Robotik, otonomi ve Robot Deployment Engineer pozisyonlarını hedefliyorum. Aşağıdaki kanıtlar deterministik simülasyon, sentetik veri ve açık veri kümelerine dayanıyor; planlanan çalışmalar ve doğrulama sınırları açıkça belirtiliyor.

**Şu anda geliştirdiklerim:** [Autonomous Sensor Fusion Lab](https://github.com/seneserisen/autonomous-sensor-fusion-lab) ve [FaultNav ROS 2](https://github.com/seneserisen/ros2-autonomous-mobile-robot).

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

---

<p align="center">
  <strong>Mühendislik kanıtı ölçülebilir, test edilebilir ve tekrar üretilebilir olmalıdır.</strong><br />
  <a href="https://github.com/seneserisen">github.com/seneserisen</a>
</p>
