<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0e1a,100:18181b&height=150&section=header&text=&fontSize=30&fontColor=FAFAFA&animation=fadeIn&descAlignY=75" />

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&duration=3000&pause=800&color=FAFAFA&center=true&vCenter=true&width=700&height=45&lines=Rizky+Dwi+%E2%80%94+Software+Engineer;Building+Production-Grade+Products;Flutter+%7C+Laravel+%7C+Android+%7C+PWA+%7C+AI+Automation)](https://git.io/typing-svg)

<p>
  <a href="https://github.com/rizdwi"><img src="https://img.shields.io/badge/GitHub-rizdwi-18181B?style=for-the-badge&logo=github&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Location-Indonesia-27272A?style=for-the-badge&logo=googlemaps&logoColor=white" />
  <img src="https://img.shields.io/badge/Focus-Production_SaaS_%26_Mobile-FAFAFA?style=for-the-badge&labelColor=FAFAFA&color=FAFAFA&logoColor=09090B" />
  <img src="https://img.shields.io/badge/Available_for_Collab-0a0e1a?style=for-the-badge&logo=handshake&logoColor=white" />
</p>

<sub>Software Engineer · AI Automation · Mobile & Web — I ship lightweight, zero-bug, offline-capable products that users actually keep.</sub>

</div>

<br/>

---

### About Me

```ts
const rizky = {
  role: "Software Engineer — Full-Stack & Mobile",
  philosophy: "Lightweight · Robust · Zero tolerance for errors",
  currentlyBuilding: [
    "GeoWake — Geofence Transit Alarm (Flutter)",
    "SelarasKas — Personal Finance PWA"
  ],
  strengths: [
    "Offline-first architecture",
    "Battery-efficient background tasks",
    "Clean GlassMonochrome UI",
    "PWA & Serverless deploy"
  ],
  mantra: "Ship fast. Keep it light. Handle every edge case."
}
```

> Rekayasa bukan soal fitur terbanyak — tapi **arsitektur paling ringan yang tetap tahan banting di produksi**. Setiap repo di bawah ini punya alasan teknis yang bisa dipertanggungjawabkan.

---

### Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=dart,flutter,kotlin,php,laravel,js,html,css,tailwind,python,supabase,vercel,git,androidstudio,vscode&perline=8" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-GlassMonochrome-02569B?style=flat-square&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Kotlin-Offline--First-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/Laravel-11.x-FF2D20?style=flat-square&logo=laravel&logoColor=white" />
  <img src="https://img.shields.io/badge/PHP-8.3-777BB4?style=flat-square&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/PWA-Standalone-5A0FC8?style=flat-square&logo=pwa&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-Pooler-3ECF8E?style=flat-square&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-Serverless-000000?style=flat-square&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-3.x-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white" />
</p>

| Layer | Tools I actually ship with |
| :--- | :--- |
| **Mobile** | Flutter (Dart), Kotlin (Android Native) · `geolocator` · `flutter_foreground_task` · `flutter_map` · `audioplayers` |
| **Web / PWA** | PHP 8.3 · Laravel 11 · Blade · Vanilla JS (modular `js/`) · Tailwind · Service Worker · Web Manifest |
| **Backend & Data** | Supabase PostgreSQL (Pooler) · SQLite (offline) · Room · SharedPreferences · `vercel-php` Single-Lambda |
| **Automation & AI** | FastAPI · Edge-TTS · FFmpeg · Fal.ai / Seedance · Hermes LLM orchestration |
| **Principles** | YAGNI · Offline-first · Adaptive polling · Pessimistic locking · Ponytail ladder |

---

### Featured Projects — Production, Not Portfolio Filler

<table>
<tr>
<td width="50%" valign="top">

#### GeoWake — Transit Geofence Alarm
<sub>Flutter · GlassMonochrome · Offline Haversine</sub>

> Bangun tepat di halte. Alarm berbasis jarak yang **100% offline** — tanpa API berbayar.

- Adaptive GPS polling (5s → 5min) hemat baterai
- Haversine math murni di CPU, anti false-trigger (debounce 2x)
- Foreground Service + `USAGE_ALARM` tembus Silent/DND
- `flutter_map` + Nominatim — zero Google Maps cost

`Flutter` `Dart` `geolocator` `flutter_map` `audioplayers`

[Source Code](https://github.com/rizdwi/GeoWake) · `GlassMonochrome` · `offline-first`

</td>
<td width="50%" valign="top">

#### SelarasKas — Personal Finance PWA
<sub>PHP · PWA · Supabase · Vercel</sub>

> Kelola pemasukan, pengeluaran & target tabungan — installable, ringan, elegan.

[![Live](https://img.shields.io/badge/Live-selaras--kas.vercel.app-0a0e1a?style=flat-square&logo=vercel&logoColor=white)](https://selaras-kas.vercel.app)

- PWA installable (Manifest + SW) + offline shell
- Analytics & budgeting engine (vanilla modular JS)
- Supabase Pooler — aman untuk serverless
- Single-Lambda `vercel-php` routing (bukan rewrite rapuh)

`PHP` `PWA` `Supabase` `Vercel` `Tailwind`

[Live Demo](https://selaras-kas.vercel.app) · [Source](https://github.com/rizdwi/SelarasKas) · `fintech`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### BookLapang — Sports Venue Booking Engine
<sub>Laravel 11 · PHP 8.3 · Tailwind · Alpine.js</sub>

[![Live](https://img.shields.io/badge/Live-book--lapang.vercel.app-0d9488?style=flat-square&logo=vercel&logoColor=white)](https://book-lapang.vercel.app)

> Solusi anti double-booking untuk penyewaan lapangan olahraga.

- `DB::transaction + lockForUpdate()` — cegah race condition
- Quota guard: max 2 unpaid booking aktif
- QRIS & VA BCA + dashboard omset
- Cache layer untuk katalog instan

`Laravel` `Blade` `Tailwind` `Alpine.js` `Vercel`

[Live Demo](https://book-lapang.vercel.app) · [Source](https://github.com/rizdwi/BookLapang)

</td>
<td width="50%" valign="top">

#### SIMWarga — Offline KK/NIK Manager
<sub>Kotlin · Android Native · Excel Round-Trip</sub>

> Pendataan warga RT/RW 100% offline — tanpa `INTERNET` permission.

- Import/export `.xlsx` true round-trip (18 kolom Buku Induk)
- Zero-dependency OpenXML parser (~6.4 MB APK)
- `@Relation` Cascade + validasi 16-digit NIK
- PIN SHA-256, reactive `Flow`/`StateFlow`

`Kotlin` `Room` `SAXParser` `Excel`

[Source Code](https://github.com/rizdwi/SIMWarga) · `offline-first` · `6.4 MB`

</td>
</tr>
</table>

---

### GitHub Analytics

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=rizdwi&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0a0e1a&title_color=FAFAFA&text_color=A1A1AA&icon_color=FAFAFA&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rizdwi&layout=compact&theme=tokyonight&hide_border=true&bg_color=0a0e1a&title_color=FAFAFA&text_color=A1A1AA&langs_count=8" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=rizdwi&theme=tokyonight&hide_border=true&background=0a0e1a&ring=FAFAFA&fire=FF1744&currStreakLabel=FAFAFA" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=rizdwi&theme=tokyonight" />
</p>

---

### Let's Connect

<p align="center">
  <a href="https://github.com/rizdwi"><img src="https://img.shields.io/badge/Explore_My_Repos-18181B?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://selaras-kas.vercel.app"><img src="https://img.shields.io/badge/Try_SelarasKas-0a0e1a?style=for-the-badge&logo=pwa&logoColor=white" /></a>
  <a href="https://book-lapang.vercel.app"><img src="https://img.shields.io/badge/Try_BookLapang-0d9488?style=for-the-badge&logo=vercel&logoColor=white" /></a>
</p>

<div align="center">
  <sub>Open to collaborations — especially lightweight SaaS & mobile products with real users.<br/>If you value <b>robust &gt; rushed</b>, we'll get along.</sub>
  <br/><br/>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:18181b,100:0a0e1a&height=100&section=footer&text=&fontSize=30&fontColor=FAFAFA&animation=fadeIn" width="100%"/>
</div>
