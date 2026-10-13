<a href="https://github.com/rizdwi">
  <img src="https://raw.githubusercontent.com/rizdwi/rizdwi/main/assets/banner.svg" width="100%" alt="Rizki Dwi Sandy Profile Banner" />
</a>

<div align="center">

<p>
  <a href="https://github.com/rizdwi"><img src="https://img.shields.io/badge/GitHub-rizdwi-18181b?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <img src="https://img.shields.io/badge/Location-Indonesia-27272a?style=flat-square&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/Status-Open_for_Opportunities-10b981?style=flat-square&logo=statuspage&logoColor=white" alt="Status" />
  <a href="https://book-lapang.vercel.app"><img src="https://img.shields.io/badge/Live_App-BookLapang-0ea5e9?style=flat-square&logo=vercel&logoColor=white" alt="BookLapang" /></a>
  <a href="https://selaras-kas.vercel.app"><img src="https://img.shields.io/badge/Live_PWA-SelarasKas-10b981?style=flat-square&logo=pwa&logoColor=white" alt="SelarasKas" /></a>
</p>

<sub>Software Engineer | Full-Stack Web & Android Native. I build lightweight, resilient, and production-grade applications with zero tolerance for runtime errors.</sub>

</div>

<br/>

---

### Core Philosophy

```typescript
interface EngineeringStandard {
  architecture: "Minimal abstractions (YAGNI), maximum runtime stability";
  resilience: "Zero tolerance for unhandled exceptions and silent data corruption";
  offlineFirst: "Local SQLite/Room caching ensures full usability without internet";
  concurrency: "Pessimistic locking and atomic DB transactions prevent race conditions";
  codeDiscipline: "Lightweight dependencies, fast cold starts, clean modular codebases";
}
```

> Rekayasa perangkat lunak bukan tentang banyaknya dependensi pihak ketiga, melainkan **arsitektur paling efisien yang terbukti stabil di lingkungan produksi**. Setiap repositori memiliki fondasi teknis yang teruji.

---

### Tech Stack & Tooling

<p align="center">
  <img src="https://skillicons.dev/icons?i=php,laravel,kotlin,dart,flutter,js,tailwind,python,fastapi,sqlite,postgres,supabase,vercel,git,androidstudio,vscode&perline=8" alt="Tech Arsenal" />
</p>

| Domain | Production Tools & Technologies |
| :--- | :--- |
| **Web Platforms** | PHP 8.3, Laravel 11, Blade, Vanilla JS (Modular Architecture), Tailwind CSS, PWA (Service Workers, Web Manifest) |
| **Mobile & Android** | Kotlin, Android Jetpack, Room Database, SQLite, Material Design 3, SAXParser, ViewBinding |
| **Backend & Cloud** | PostgreSQL (Supabase Pooler), SQLite, MySQL, Vercel Serverless (`vercel-php` Single-Lambda), FastAPI |
| **Automation & Media** | Python, FFmpeg Compositing, Edge-TTS, Fal.ai Video API, SQLModel, APScheduler |
| **Engineering Practices** | YAGNI, Offline-First Architecture, Pessimistic Locking, MVVM, MVC, Repository Pattern |

---

### Featured Projects

<table>
<tr>
<td width="50%" valign="top">

#### BookLapang: Sports Venue Booking Platform
<sub>Laravel 11 · PHP 8.3 · Tailwind CSS · Alpine.js · Vercel</sub>

<p>
  <a href="https://book-lapang.vercel.app"><img src="https://img.shields.io/badge/Live_Demo-book--lapang.vercel.app-0ea5e9?style=flat-square&logo=vercel&logoColor=white" alt="Live Demo" /></a>
  <a href="https://github.com/rizdwi/BookLapang"><img src="https://img.shields.io/badge/Source-rizdwi/BookLapang-18181b?style=flat-square&logo=github&logoColor=white" alt="GitHub Source" /></a>
</p>

Solusi reservasi lapangan olahraga anti double-booking dengan arsitektur data ketat:

- Pencegahan *race condition* dengan `DB::transaction()` dan *pessimistic locking* (`lockForUpdate()`)
- *Quota guard* otomatis yang membatasi maksimal 2 reservasi aktif belum bayar per pengguna
- Integrasi simulasi pembayaran instan QRIS dan Virtual Account BCA
- Lapisan *caching* internal untuk kecepatan respons katalog jadwal

`Laravel 11` `Blade` `Tailwind` `Alpine.js` `SQLite` `Vercel`

</td>
<td width="50%" valign="top">

#### SIMWarga: Offline Population Data Manager
<sub>Kotlin · Android Native · Room DB · Standalone OpenXML</sub>

<p>
  <a href="https://github.com/rizdwi/SIMWarga"><img src="https://img.shields.io/badge/Source-rizdwi/SIMWarga-18181b?style=flat-square&logo=github&logoColor=white" alt="GitHub Source" /></a>
  <a href="https://github.com/rizdwi/SIMWarga/blob/main/SIMWarga-debug.apk"><img src="https://img.shields.io/badge/APK-6.4_MB_Standalone-10b981?style=flat-square&logo=android&logoColor=white" alt="Download APK" /></a>
</p>

Aplikasi pendataan warga RT/RW 100% *offline-first* dengan integrasi penuh format Microsoft Excel:

- Aman dari kebocoran data karena beroperasi tanpa izin internet (`INTERNET` *permission* dihapus)
- *Parser* dan generator format `.xlsx` kustom berbasis SAX & ZIP *stream* tanpa dependensi Apache POI (~6.4 MB total APK)
- Kesesuaian 18 kolom Buku Induk Pendaftaran Penduduk dengan kompatibilitas impor dan ekspor bolak-balik (*round-trip*)
- Proteksi keamanan data warga dengan PIN terenkripsi satu arah SHA-256

`Kotlin` `Android SDK` `Room DB` `OpenXML` `Material 3`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### SelarasKas: Personal Finance PWA
<sub>PHP 8.3 · Vanilla JS · Supabase Pooler · Vercel Serverless</sub>

<p>
  <a href="https://selaras-kas.vercel.app"><img src="https://img.shields.io/badge/Live_App-selaras--kas.vercel.app-10b981?style=flat-square&logo=pwa&logoColor=white" alt="Live App" /></a>
</p>

Platform pencatatan keuangan pribadi dan pemantauan target tabungan dengan performa ringan:

- PWA yang dapat dipasang di layar utama ponsel (*installable*) dengan *caching service worker* untuk akses *offline*
- Arsitektur routing *Single-Lambda* `vercel-php` yang stabil di lingkungan komputasi *serverless*
- Terhubung ke Supabase PostgreSQL melalui *Transaction Connection Pooler* untuk efisiensi koneksi tanpa batas *pool*
- Mesin analitik anggaran visual menggunakan modular *vanilla* JavaScript tanpa kerangka kerja berat

`PHP 8.3` `PWA` `Supabase` `Tailwind CSS` `Vercel`

</td>
<td width="50%" valign="top">

#### StoryTubeAI: Autonomous Media Automation Engine
<sub>FastAPI · Python 3.11 · FFmpeg · Edge-TTS · Fal.ai</sub>

<p>
  <img src="https://img.shields.io/badge/Architecture-Autonomous_Pipeline-f59e0b?style=flat-square&logo=fastapi&logoColor=white" alt="Architecture" />
</p>

Sistem *pipeline* terotomatisasi penuh untuk perancangan, sintesis, dan perakitan video edukasi:

- Orkestrasi berantai dari *prompt generation*, penilaian kecocokan adegan, hingga sinkronisasi narasi Edge-TTS
- Komposisi video *headless* berkecepatan tinggi dengan FFmpeg, efek dinamis *Ken Burns*, dan *hardcoded subtitles*
- Sistem pemulihan status kerja otomatis berbasis APScheduler dengan pembersihan berkala berkas sementara (*scratch files*)
- Manajemen terpadu publikasi terjadwal menggunakan YouTube Data API v3

`FastAPI` `Python` `FFmpeg` `Edge-TTS` `SQLModel`

</td>
</tr>
</table>

---

### GitHub Activity & Metrics

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=rizdwi&show_icons=true&theme=tokyonight&hide_border=true&bg_color=09090b&title_color=fafafa&text_color=a1a1aa&icon_color=38bdf8&count_private=true" alt="GitHub Stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rizdwi&layout=compact&theme=tokyonight&hide_border=true&bg_color=09090b&title_color=fafafa&text_color=a1a1aa&langs_count=8" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=rizdwi&theme=tokyonight&hide_border=true&background=09090b&ring=38bdf8&fire=10b981&currStreakLabel=fafafa" alt="Streak Stats" />
</p>

---

### Connect & Collaboration

<p align="center">
  <a href="https://github.com/rizdwi"><img src="https://img.shields.io/badge/GitHub-@rizdwi-18181b?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://book-lapang.vercel.app"><img src="https://img.shields.io/badge/App-BookLapang-0ea5e9?style=flat-square&logo=vercel&logoColor=white" alt="BookLapang" /></a>
  <a href="https://selaras-kas.vercel.app"><img src="https://img.shields.io/badge/PWA-SelarasKas-10b981?style=flat-square&logo=pwa&logoColor=white" alt="SelarasKas" /></a>
</p>

<div align="center">
  <sub>Terbuka untuk kolaborasi rekayasa perangkat lunak, pengembangan produk mandiri (*SaaS*), dan aplikasi *mobile* berorientasi keandalan sistem.</sub>
</div>
