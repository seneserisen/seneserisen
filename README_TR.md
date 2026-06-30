<h1 align="center">Merhaba, ben Sadik Enes Erisen</h1>

<p align="center">
  <b>Elektrik-Elektronik Mühendisi · FAU Otonomi Teknolojileri Yüksek Lisans Öğrencisi</b>
</p>

<p align="center">
  <a href="README.md">English</a> · <b>Türkçe</b>
</p>

---

Friedrich-Alexander-Universität Erlangen-Nürnberg'de (FAU) **Otonomi Teknolojileri yüksek lisans öğrencisiyim**. Atılım Üniversitesi **Elektrik-Elektronik Mühendisliği lisans mezunuyum** ve Bavyera, Almanya'da yaşıyorum. Robotik, gömülü sistemler, kontrol, endüstriyel veri analizi ve otonom sistemler alanlarında simülasyon odaklı projeler geliştiriyorum.

## Öne Çıkan Mühendislik Projeleri

### [Endüstriyel Kalite Anomali İzleme Sistemi](https://github.com/seneserisen/industrial-quality-anomaly-monitor)

Sentetik üretim verisi oluşturan, sağlam istatistiksel yöntemler ve Isolation Forest ile anomali tespiti yapan, mühendislik KPI'ları ve görsel raporlar üreten tekrar üretilebilir bir Python projesidir.

**Öne çıkan özellikler:**

- Makine ve üretim hattı bazlı referans dağılımları
- Robust Z-score ve Isolation Forest yöntemleri
- Komut satırı iş akışları
- Birim, entegrasyon ve uçtan uca testler
- Docker ve GitHub Actions desteği
- Ayrıştırılması özellikle kolaylaştırılmış sentetik veri kümesinde yaklaşık 0,992 F1 skoru

Bu sonuç gerçek fabrika performansı iddiası değildir; proje, yöntemlerin ve doğrulama yaklaşımının gösterilmesi amacıyla hazırlanmıştır.

### [Otomatik Kontrol Laboratuvarı Projeleri](https://github.com/seneserisen/automatic-control-lab-projects)

Doğrusal olmayan modelleme, durum uzayı kontrolü, LQR, gözleyiciler, aktüatör doyumu, anti-windup, sayısal doğrulama ve taşınabilir C99 uygulamalarını kapsayan beş kontrol sistemi çalışmasıdır.

**Yayımlanan simülasyon sonuçları arasında:**

- Döner kol takip RMSE değerinde yaklaşık %70 azalma
- Aktif süspansiyon gövde ivmesi RMS değerinde yaklaşık %35 azalma
- Manyetik levitasyon konum tahmini RMSE değerinin 0,001 mm altında olması
- İki tanklı sistemde anti-windup ile daha hızlı toparlanma

Sonuçlar yalnızca dokümante edilmiş simülasyon ve test koşulları için geçerlidir.

### [FaultNav ROS 2 — Deterministik Hareket ve Odometri](https://github.com/seneserisen/ros2-autonomous-mobile-robot)

Kesin diferansiyel sürüş modeli, tekrar üretilebilir hareket deneyleri, kurulabilir bir mühendislik komut satırı aracı ve ROS 2 odometri düğümünü birleştiren Python odaklı robotik projesidir.

<p align="center">
  <a href="https://github.com/seneserisen/ros2-autonomous-mobile-robot">
    <img width="760" src="https://raw.githubusercontent.com/seneserisen/ros2-autonomous-mobile-robot/main/examples/figure_eight_trajectory.svg" alt="FaultNav deterministik sekiz şekilli hareket yörüngesi" />
  </a>
</p>

**Doğrulanmış deterministik sonuç:** `0,2 s` integrasyon adımıyla `25,1327 s` süren ve `12,5664 m` yol kat eden sekiz şekilli hareket, başlangıç konumuna yaklaşık `1,812 × 10⁻¹⁴ m` sayısal kapanma hatasıyla geri döndü.

**Mühendislik kanıtı:** tip güvenli senaryo modelleri, kesin komut bölümü sınırları, CSV/JSON/SVG raporları, `cmd_vel` aboneliği, odometri ve TF yayını, eski komutlara karşı otomatik durdurma, otomatik testler ve Python 3.10–3.12 üzerinde başarılı CI doğrulaması.

**Doğrulama sınırı:** bu sonuç, dokümante edilmiş analitik modelin sayısal tutarlılığını gösterir. Fizik simülatörü ve fiziksel robot doğrulaması sonraki aşamalardır; sonuç gerçek konumlama doğruluğu iddiası değildir.

[![FaultNav Python doğrulaması](https://github.com/seneserisen/ros2-autonomous-mobile-robot/actions/workflows/python-core.yml/badge.svg)](https://github.com/seneserisen/ros2-autonomous-mobile-robot/actions/workflows/python-core.yml)

**Teknolojiler:** Python · ROS 2 · Diferansiyel Sürüş Kinematiği · Odometri · TF2 · pytest · Ruff · GitHub Actions

---

## Hakkımda

- Python, MATLAB, C ve C++ ile mühendislik yazılımı geliştiriyorum
- Kontrol teorisi, istatistiksel izleme, makine öğrenmesi ve doğrulama yöntemlerini mühendislik problemlerine uyguluyorum
- Otomatik test, Docker, CMake, GitHub Actions ve Linux ile tekrar üretilebilir iş akışları kuruyorum
- Almanya'da robotik, gömülü sistemler, otomasyon, kontrol ve endüstriyel yapay zekâ alanlarındaki Werkstudent pozisyonlarına açığım

## Seçili Deneyim

**Schaeffler — Elektronik Bileşen Üretimi Stajyeri, Advanced Production Technology (2025)**  
E-mobilite üretim ve laboratuvar çalışmalarında proses ölçümü, numune hazırlama, birleştirme süreçleri, lazer sistemleri, 3D baskı ve optik metroloji alanlarında görev aldım.

---

## Teknik Yetkinlikler

| Alan | Teknolojiler |
|---|---|
| **Programlama ve Veri** | Python, C, C++, SQL, NumPy, pandas, Matplotlib, Jupyter Notebook |
| **Yapay Zekâ, Makine Öğrenmesi ve Analitik** | PyTorch, Power BI, Power Automate, Minitab, Microsoft Excel |
| **Robotik, Kontrol ve Simülasyon** | ROS 2, MATLAB/Simulink, Gazebo, COMSOL Multiphysics, CST Studio Suite |
| **Gömülü Sistemler, Elektronik ve CAD** | LTspice, Proteus, KiCad, PTC Creo, AutoCAD, Revit, ETAP, Caneco BT |
| **Mühendislik İş Akışı** | Linux, Git, Docker, GitHub Actions, CMake, REST API'leri, AWS, SAP |

---

## Diller

- **Türkçe:** Ana dil
- **İngilizce:** C1 — IELTS Academic 8.0
- **Almanca:** A2.2 tamamlandı, B1 eğitimi devam ediyor
- **Korece:** A1
- **Japonca:** A1 — JLPT N5

---

## Profesyonel Hedef

Özellikle aşağıdaki alanlarda ölçülebilir ve doğrulanabilir mühendislik projeleri geliştirmeye devam ediyorum:

- Robotik ve otonom sistemler
- Gömülü yazılım ve elektronik sistemler
- Kontrol sistemleri ve simülasyon
- Endüstriyel veri analizi ve yapay zekâ
- Test otomasyonu ve mühendislik doğrulaması

---

<p align="center">
  <b>Mühendislik sistemleri ölçülebilir, test edilebilir ve tekrar üretilebilir olmalıdır.</b>
</p>
