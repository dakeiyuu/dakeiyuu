<div align="center">

<!-- BANNER -->
<img src="https://capsule-render.vercel.app/api?type=venom&color=0:1a0a2e,50:2d1b4e,100:1a0a2e&height=280&section=header&text=Tsukiji%20Maps&fontSize=65&fontColor=ffffff&fontAlignY=45&desc=Find%20your%20perfect%20business%20location&descAlignY=62&descSize=17&animation=fadeIn" />

<!-- BADGES -->
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org)
[![Google Maps](https://img.shields.io/badge/Google%20Maps-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white)](https://developers.google.com/maps)
[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com)
[![License](https://img.shields.io/badge/License-Apache%202.0-F5732A?style=for-the-badge)](LICENSE)

<!-- DECORACION -->
✦ &nbsp; ✧ &nbsp;&nbsp;&nbsp; ✦ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ✧ &nbsp;&nbsp;&nbsp; ✦ &nbsp;&nbsp; ✧ &nbsp;&nbsp;&nbsp;&nbsp; ✦ &nbsp;&nbsp;&nbsp; ✧ &nbsp;&nbsp; ✦

</div>

---

### &nbsp; What is Tsukiji?

Tsukiji Maps is an Android app that helps entrepreneurs and investors find the best spots to open a business. It uses live heatmaps to visualize commercial density, analyzes competition in any visible area, and returns ranked location suggestions with opportunity scores.

---

### &nbsp; Features

<div align="center">

| &nbsp; | Feature | Description |
|---|---|---|
| ◯ | **Live Heatmap** | Business density rendered dynamically per zoom level |
| ◯ | **Location Scoring** | 200 candidates evaluated, top 5 returned |
| ◯ | **Category Filters** | Restaurants · Retail · Services · Entertainment |
| ◯ | **Save Locations** | Bookmark spots with score and timestamp |
| ◯ | **Property Board** | List spaces for rent or sale with photos |

</div>

---

### &nbsp; Tech Stack

<div align="center">

✦ &nbsp; Languages &nbsp; ✦

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![XML](https://img.shields.io/badge/XML-FF6B35?style=flat-square&logo=xml&logoColor=white)

✧ &nbsp; Libraries &nbsp; ✧

![Google Maps SDK](https://img.shields.io/badge/Maps%20SDK-4285F4?style=flat-square&logo=googlemaps&logoColor=white)
![Maps Utils](https://img.shields.io/badge/Maps%20Utils-34A853?style=flat-square&logo=googlemaps&logoColor=white)
![Coroutines](https://img.shields.io/badge/Coroutines-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Material 3](https://img.shields.io/badge/Material%203-757575?style=flat-square&logo=materialdesign&logoColor=white)

✦ &nbsp; Tools &nbsp; ✦

![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=flat-square&logo=androidstudio&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)

</div>

---

### &nbsp; Getting Started

**1. Clone**
```bash
git clone https://github.com/your-org/tsukiji-maps.git
```

**2. Add your API key** — crea `secrets.properties` en la raíz:
```properties
MAPS_API_KEY=YOUR_KEY_HERE
```

**3. Run**
```bash
./gradlew :app:installDebug
```

---

### &nbsp; Scoring Algorithm

```
    ✦ 200 random candidates within visible bounds
              ↓
    ◯  competitor distance      → rewarded
    ◯  foot traffic proximity   → rewarded
    ◯  business density         → bonus
    ◯  same-category saturation → penalty
              ↓
    ✧ Top 5 non-overlapping results on map
```

<div align="center">

| Score | Signal |
|---|---|
| > 70 | ✦ Excellent opportunity |
| 50 – 70 | ✧ Good balance |
| 30 – 50 | ◯ Emerging zone |
| < 30 | High competition |

</div>

---

<div align="center">

✧ &nbsp;&nbsp;&nbsp; ✦ &nbsp;&nbsp; ✧ &nbsp;&nbsp;&nbsp;&nbsp; ✦ &nbsp;&nbsp;&nbsp; ✧ &nbsp;&nbsp; ✦ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ✧ &nbsp;&nbsp;&nbsp; ✦ &nbsp;&nbsp; ✧

*Built on [android-maps-ktx](https://github.com/googlemaps/android-maps-ktx) · Apache 2.0*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a0a2e,100:2d1b4e&height=100&section=footer" />

</div>
