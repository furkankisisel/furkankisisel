<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=02569B&height=200&section=header&text=Furkan%20Çalık&fontSize=50&fontAlignY=35&desc=Mobile%20Software%20Engineer&descSize=20&descAlignY=55&animation=fadeIn" width="100%" />

  <p align="center">
    <a href="https://linkedin.com/in/furkan-çalık" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:furkancalk325@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
  </p>

  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=2563EB&center=true&vCenter=true&width=600&lines=Building+Scalable+Mobile+Architectures;Native+Android+(Kotlin+%2B+Compose);Cross-Platform+Flutter+Mastery;Offline-First+%26+E2EE+Secure+Systems;AI-Powered+Mobile+Experiences;Medical+Hardware+Integration" alt="Typing SVG" />
  </a>
</div>

---

### 👨‍💻 Mühendislik Felsefem

Ankara Üniversitesi'nde Bilgisayar Mühendisliği eğitimime devam ederken; modern yazılım ekosisteminde kod yazmanın ötesinde, donanım düzeyinde güvenlik, çevrimdışı çalışabilirlik (offline-first) ve performans odaklı mimariler inşa etmeye odaklanıyorum. Native Android, Flutter ve JavaFX ile geliştirdiğim sistemlerde Clean Architecture ve MVC prensiplerini tavizsiz uyguluyor; WebRTC, Multimodal LLM ve medikal donanım haberleşmesi gibi ileri seviye teknolojileri production-grade standartlarda entegre ediyorum.

<div align="center">
  <img src="https://skillicons.dev/icons?i=kotlin,flutter,dart,androidstudio,java,python,firebase,supabase,postgres,sqlite,git,linux,postman,docker" alt="Tech Stack" />
</div>

---

### 🚀 Öne Çıkan Mühendislik Projeleri

#### 🔐 [Misal — E2EE Real-Time Messaging & WebRTC Calling](https://github.com/furkankisisel/misal)
Modern Android Development (MAD) pratikleriyle sıfırdan geliştirilmiş, gizlilik odaklı anlık mesajlaşma ve VoIP arama platformu[cite: 4].
> **Mühendislik Başarıları:**
> - **Donanım Destekli Şifreleme:** `AndroidKeyStore` entegrasyonu ile asimetrik (RSA-OAEP 2048-bit) ve simetrik (AES-GCM 256-bit) hibrit uçtan uca şifreleme (E2EE) mimarisi kurgulandı[cite: 4].
> - **WebRTC P2P İletişim:** Cloud Firestore destekli SDP sinyalleşmesi ve ICE adayı senkronizasyonu ile düşük gecikmeli ses/video VoIP altyapısı entegre edildi[cite: 4].
> - **Arka Plan Süreçleri:** Uygulama kapalıyken bile çağrıları yakalayan yüksek öncelikli FCM ve Foreground Service (`shortService`) mimarisi tasarlandı[cite: 4].
> - **Tech Stack:** Kotlin 2.0, Jetpack Compose, Room, Dagger Hilt, MVVM, Clean Architecture[cite: 4].

#### 🎧 [Clinical Audiometer & Diagnostic System](https://github.com/furkankisisel/audiometer-clinical-system)
Tıbbi standartlara (ISO 8253-1 ve IEC 60645-1) uygun, donanım simülasyonlu klinik işitme testi cihazı ve JavaFX tabanlı masaüstü teşhis yazılımı[cite: 5].
> **Mühendislik Başarıları:**
> - **Donanım-Yazılım Entegrasyonu:** `jSerialComm` kullanılarak, Proteus VSM üzerinden gelen asenkron hasta donanım sinyallerini UI thread'ini bloklamadan işleyen kesinti (interrupt) tabanlı seri köprü kuruldu[cite: 5].
> - **Gerçek Zamanlı Render Motoru:** Klinik odyogramları (sağ/sol kulak test sonuçları) tıbbi standartlara göre sıfır gecikmeyle çizen yüksek performanslı JavaFX `Canvas` motoru kodlandı[cite: 5].
> - **Mimari ve Güvenilirlik:** Sıkı bir Layered MVC mimarisi üzerine inşa edilen sistemin, Hughson-Westlake algoritma geçişleri ve veri parse işlemleri JUnit 5 ile test edilerek yüksek güvenilirliğe ulaştırıldı[cite: 5].
> - **Tech Stack:** Java 21, JavaFX, MVC, jSerialComm, JUnit 5, Proteus VSM[cite: 5].

#### 🧬 [Mira — Circadian Life & Habit Intelligence](https://github.com/furkankisisel/mira)
Kullanıcının biyolojik saatiyle (sirkadiyen ritim) senkronize çalışan, çevrimdışı (offline-first) yaşam yönetimi ve yapay zeka koçluk ekosistemi[cite: 3].
> **Mühendislik Başarıları:**
> - **Biyoritim Hesaplama Motoru:** Sabit bildirimler yerine uyku/uyanıklık döngüsüne göre optimum `Focus`, `Energy` ve `Reflection` pencerelerini dinamik hesaplayan matematiksel algoritma tasarlandı[cite: 3].
> - **Anti-Cheat Doğrulama:** İstemci tarafı sistem saati manipülasyonlarını engelleyen ve serileri (streak) kriptografik damgalarla koruyan oyunlaştırma (gamification) mekanikleri uygulandı[cite: 3].
> - **Derin LLM Entegrasyonu:** Groq Llama 3.3 entegrasyonu ile dinamik onboarding ve doğal dilde habit koçluğu sağlandı[cite: 3].
> - **Tech Stack:** Flutter 3.24+, Feature-First Modularity, flutter_background_service, In-App Purchase[cite: 3].

#### 👁️ [Eloa — Multimodal AI Morphological Analysis](https://github.com/furkankisisel/eloa)
Geleneksel İlmi Sima ve morfoloji analizlerini Google Gemini 2.5 Flash görüntü işleme yetenekleriyle harmanlayan yeni nesil analiz uygulaması[cite: 2].
> **Mühendislik Başarıları:**
> - **Görüntü İşleme ve Kamera Katmanı:** Kullanıcı hatalarını sıfıra indirmek için canlı kamera akışı üzerine saydam el geometrisi overlay'leri (kılavuz) yerleştirildi[cite: 2].
> - **Defansif Prompt Mimarisi:** Multimodal yapay zeka çıktılarının uygulama içinde çökme yaratmaması için yapılandırılmış JSON deserialization pipeline'ı kuruldu[cite: 2].
> - **Monetizasyon:** `in_app_purchase` üzerinden Apple StoreKit ve Google Play Billing entegrasyonlarıyla güvenli mikro ödeme sistemi kodlandı[cite: 2].
> - **Tech Stack:** Flutter, Google Gemini 2.5 Flash API, Groq Llama 3.3, Firebase Auth[cite: 2].

#### 🧭 [Prayly — Offline-First Spiritual Companion](https://github.com/furkankisisel/prayly)
Nostaljik retro pixel-art estetiğini, sensör doğruluğu ve modern yazılım mimarisiyle birleştiren offline-first günlük asistanı[cite: 1].
> **Mühendislik Başarıları:**
> - **Sensör Füzyonu:** Cihazın manyetometre ve ivmeölçer verileri alınarak, iğne titremelerini engelleyen özel bir dampening (sönümleme) filtresiyle hassas pusula mekaniği yazıldı[cite: 1].
> - **Ağ Esnekliği (Resilience):** Aladhan API üzerinden çekilen veriler anında SQLite üzerinde önbelleğe alınarak sıfır ağ bağlantısında bile %100 işlevsellik sağlandı[cite: 1].
> - **Sıfır Hata Prensibi:** GitHub Actions ile CI/CD süreçleri kurularak her PR'da otomatik statik kod analizi ve unit testler koşturuldu[cite: 1].
> - **Tech Stack:** Flutter, sqflite, flutter_compass, timezone, i18n (7 dil)[cite: 1].

---

<div align="center">
  <h3>📊 GitHub İstatistikleri</h3>
  <br>
  <img src="https://github-readme-stats.vercel.app/api?username=furkankisisel&show_icons=true&theme=transparent&hide_border=true&title_color=2563EB&icon_color=2563EB&text_color=A6ADBB" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=furkankisisel&theme=transparent&hide_border=true&title_color=2563EB&ring_color=2563EB&fire_color=2563EB&text_color=A6ADBB" alt="GitHub Streak" width="48%" />
</div>

<br>

<div align="center">
  <i>"Karmaşık sistemleri basit, güvenli ve performanslı arayüzlerin arkasına gizlemeyi seviyorum."</i>
</div>
