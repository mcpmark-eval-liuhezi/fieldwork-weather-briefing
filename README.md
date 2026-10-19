# Fieldwork Weather Briefing — BUPT (Beijing) vs GZU (Guiyang)

Two-day outdoor orientation session for new grad students.

- **Proposed session dates: Saturday 24 – Sunday 25 October 2026** (weekend, ~5 days out, inside the two-week planning window)
- **Decision to make:** which campus hosts the session — **BUPT, Beijing** or **GZU, Guiyang**

---

## 1. Data provenance

All data pulled on **Monday, 19 October 2026, between 18:13 and 18:34 China Standard Time (UTC+8, Asia/Shanghai)**.

| Data | Source |
|---|---|
| Current conditions, forecasts, astronomy, history, alerts | WeatherAPI (`weather-data` tools) |
| 14-day day-by-day daily outlook (both cities) | Open-Meteo public API (daily max/min temp, precipitation sum, max precip probability, max wind) |
| Typical climate / climatology | Sources actually opened during web research — see §7 for links |

Web-search note: the first several DuckDuckGo web searches for Guiyang/Beijing autumn climate **returned empty results** (no matches, likely bot detection). Later searches returned results, and four pages were actually opened and read: Wikipedia's Guiyang and Beijing articles and climatestotravel.com's Beijing and Guiyang climate pages. No numbers in §7 come from a page that was not opened.

---

## 2. Locations and coordinates (as resolved by the weather service)

| City | Resolved coordinates | Elevation (model grid) | Timezone |
|---|---|---|---|
| Beijing (BUPT) | **lat 39.9289, lon 116.3883** | ~51 m (Open-Meteo grid) | Asia/Shanghai (UTC+8) |
| Guiyang (GZU) | **lat 26.5833, lon 106.7167** | ~1,081 m (Open-Meteo grid) | Asia/Shanghai (UTC+8) |

---

## 3. Current conditions (side-by-side, pulled 19 Oct 2026, ~18:15 local)

| | **Beijing (BUPT)** | **Guiyang (GZU)** |
|---|---|---|
| Condition | Smoky haze | Partly cloudy |
| Temperature | 18.2 °C (feels like 14.4 °C) | 22.4 °C (feels like 20.9 °C) |
| Wind | 10.8 km/h from S, gusting 22 km/h | 21.6 km/h from SSE, gusting 40 km/h |
| Humidity | 33 % | 75 % |
| Precipitation | 0 mm (2 % chance) | 0 mm (13 % chance) |
| Visibility | 5.5 km | 10 km |
| Air quality (PM2.5) | **119 µg/m³ — US EPA index 4 (unhealthy for sensitive groups)** | **15.9 µg/m³ — US EPA index 2 (moderate)** |
| Last updated | 18:00 local | 18:15 local |

**Active alerts at time of pull (both expire 20 Oct, i.e. before the proposed dates):**
- Beijing: blue (IV/minor) rainstorm warning for **Tongzhou District** only, effective 19 Oct 11:13, expires 20 Oct 11:13.
- Guiyang: blue (IV/minor) gale warning for **Yunyan District** (force 6+ winds, gusts force 7+), effective 19 Oct 11:34, expires 20 Oct 11:34.

---

## 4. Day-by-day outlook, 19 Oct – 1 Nov 2026 (14 days)

### Beijing (BUPT)

| Date | Max / Min (°C) | Precip (mm) | Rain chance | Max wind (km/h) | Summary (WMO code) |
|---|---|---|---|---|---|
| Mon 19 Oct | 18.1 / 6.4 | 0.0 | 0 % | 8.1 | Partly cloudy |
| Tue 20 Oct | 12.8 / 6.9 | 2.7 | 67 % | 13.5 | Drizzle |
| Wed 21 Oct | 15.1 / 4.3 | 0.0 | 0 % | 14.1 | Clear |
| Thu 22 Oct | 15.0 / 2.8 | 0.0 | 0 % | 12.6 | Clear |
| Fri 23 Oct | 14.8 / 5.4 | 0.0 | 2 % | 5.9 | Clear |
| **Sat 24 Oct** | **17.7 / 7.1** | **0.1** | **24 %** | 6.7 | **Overcast** |
| **Sun 25 Oct** | **13.4 / 11.3** | **3.8** | **34 %** | 9.6 | **Drizzle** |
| Mon 26 Oct | 14.3 / 8.9 | 0.0 | 18 % | 8.3 | Overcast |
| Tue 27 Oct | 14.1 / 5.0 | 0.0 | 2 % | 13.0 | Clear |
| Wed 28 Oct | 14.0 / 2.4 | 0.0 | 1 % | 6.1 | Clear |
| Thu 29 Oct | 13.4 / 3.7 | 0.0 | 0 % | 6.8 | Overcast |
| Fri 30 Oct | 14.6 / 4.1 | 0.0 | 3 % | 13.4 | Partly cloudy |
| Sat 31 Oct | 8.3 / 4.2 | 0.0 | 4 % | 5.1 | Overcast |
| Sun 1 Nov | 13.1 / 2.5 | 0.4 | 4 % | 7.3 | Light drizzle |

### Guiyang (GZU)

| Date | Max / Min (°C) | Precip (mm) | Rain chance | Max wind (km/h) | Summary (WMO code) |
|---|---|---|---|---|---|
| Mon 19 Oct | 26.8 / 18.9 | 1.4 | 28 % | 23.8 | Light drizzle |
| Tue 20 Oct | 22.8 / 15.9 | 5.0 | 94 % | 19.6 | Rain showers |
| Wed 21 Oct | 15.8 / 12.6 | 18.4 | 100 % | 15.9 | Moderate rain showers |
| Thu 22 Oct | 22.0 / 12.8 | 6.4 | 43 % | 19.5 | Heavy drizzle |
| Fri 23 Oct | 19.4 / 13.0 | 4.7 | 70 % | 13.3 | Light rain |
| **Sat 24 Oct** | **24.3 / 14.0** | **0.6** | **32 %** | 10.2 | **Light drizzle** |
| **Sun 25 Oct** | **24.5 / 14.0** | **0.0** | **19 %** | 10.7 | **Overcast** |
| Mon 26 Oct | 22.5 / 14.1 | 0.0 | 18 % | 12.1 | Overcast |
| Tue 27 Oct | 20.2 / 15.5 | 0.6 | 24 % | 9.9 | Light drizzle |
| Wed 28 Oct | 20.6 / 15.8 | 0.0 | 22 % | 20.6 | Overcast |
| Thu 29 Oct | 23.1 / 17.7 | 1.0 | 37 % | 22.7 | Light drizzle |
| Fri 30 Oct | 25.2 / 18.6 | 2.6 | 38 % | 17.0 | Light drizzle |
| Sat 31 Oct | 25.4 / 18.2 | 1.2 | 55 % | 17.2 | Light drizzle |
| Sun 1 Nov | 20.8 / 13.2 | 4.2 | 54 % | 16.8 | Drizzle |

**Reading the two windows side-by-side for 24–25 Oct:** the two cities are roughly comparable on those two specific days — Beijing 17.7/7.1 °C and 13.4/11.3 °C with 0.1 mm (24 %) and 3.8 mm (34 %); Guiyang 24.3/14.0 °C and 24.5/14.0 °C with 0.6 mm (32 %) and 0.0 mm (19 %). Guiyang is warmer; rain risk is a near tie. Note, however, the surrounding pattern: Guiyang's whole 14-day outlook shows drizzle on nearly every day, while Beijing shows a completely dry stretch 26–30 Oct (0.0 mm, ≤ 3 % every day).

*(Day-1 figures from WeatherAPI differ slightly between models — e.g. WeatherAPI had Beijing at 19.8/11.9 °C with "smoky haze" and Guiyang at 24.6/19.3 °C with a 54 % rain chance for 19 Oct — which is normal model spread at day-1 and does not change the comparison above.)*

---

## 5. Sunrise / sunset for the proposed dates (24–25 Oct 2026)

| | Sunrise | Sunset | Daylight | Moon |
|---|---|---|---|---|
| **Beijing, Sat 24 Oct** | 06:34 | 17:22 | ~10 h 48 m | Waxing gibbous, 92 % |
| **Beijing, Sun 25 Oct** | 06:35 | 17:21 | ~10 h 46 m | Waxing gibbous, 97 % |
| **Guiyang, Sat 24 Oct** | 06:57 | 18:16 | ~11 h 19 m | Waxing gibbous, 92 % |
| **Guiyang, Sun 25 Oct** | 06:58 | 18:16 | ~11 h 18 m | Waxing gibbous, 97 % |

Both cities get 10 h 45 m – 11 h 20 m of usable daylight — plenty for two full field days. Beijing starts ~23 min earlier; Guiyang runs ~55 min later in the evening.

---

## 6. Same dates last year — what actually happened on 24–25 Oct 2025

| | Beijing, 24 Oct 2025 | Beijing, 25 Oct 2025 | Guiyang, 24 Oct 2025 | Guiyang, 25 Oct 2025 |
|---|---|---|---|---|
| Max / Min (°C) | 15.2 / 9.1 | 16.4 / 10.1 | 16.1 / 9.2 | **10.6 / 9.7** |
| Avg temp (°C) | 12.1 | 13.2 | 11.6 | **10.0** |
| Precipitation | 0.0 mm | 0.0 mm | 0.2 mm | 0.2 mm |
| Condition | Partly cloudy | Partly cloudy | Cloudy | Patchy rain possible |
| Humidity | 53 % | 53 % | 75 % | **86 %** |
| Max wind | 11.2 km/h | 6.5 km/h | 13.7 km/h | 10.8 km/h |
| UV | 2 | 1.9 | 4.7 | 1.1 |

**Takeaway:** on these exact dates last year, Beijing was **dry, mild and partly cloudy both days (0.0 mm, highs 15–16 °C)** — textbook fieldwork weather. Guiyang was **damp, grey and much colder, with drizzle and 75–86 % humidity both days and an average temperature of just 10.0 °C on the 25th**. One year is not a climate either, but it is consistent with the October climatology below.

---

## 7. Typical late-October climate — notes from sources actually opened

### Guiyang (GZU)

From Wikipedia's Guiyang article (climate table, China Meteorological Administration 1991–2020 normals) — https://en.wikipedia.org/wiki/Guiyang :
- Guiyang has a four-season, monsoon-influenced **humid subtropical climate (Köppen Cwa)** on the Yunnan–Guizhou Plateau at ~1,100–1,275 m elevation.
- **October normals: mean daily max 19.6 °C, daily mean 15.6 °C, daily min 13.0 °C; precipitation 90.8 mm spread over ~15.8 precipitation days; relative humidity 82 %; only 72.6 h of monthly sunshine (23 % of possible).**
- "Rain is common throughout the year"; with ~1,020 h of sunshine annually, it is "one of China's least sunny major cities."

From climatestotravel.com's Guiyang climate page — https://www.climatestotravel.com/climate/china/guiyang :
- October: average min/max **12.4 / 19.7 °C**, ~**90 mm of rain over ~14 days**, ~**3 h sunshine per day**.
- The rains are abundant May–September; "the sun is rarely seen, in fact southwest China is the least sunny area of the country."
- Bluntly: "It is difficult to find the best time to visit Guiyang… **sometimes it can get a bit cold even in April and October**."
- Typhoon remnants can occasionally reach the area as late as early November (rare at Guiyang's inland location).

### Beijing (BUPT)

From Wikipedia's Beijing article (Climate section, 1991–2020 normals) — https://en.wikipedia.org/wiki/Beijing :
- **Humid continental climate (Köppen Dwa), bordering cold semi-arid (BSk)**; autumn is "a season of transition and minimal precipitation."
- **October normals: mean daily max 19.3 °C, daily mean 13.8 °C, daily min 8.8 °C.**
- Annual precipitation is only ~528 mm, "with close to three-quarters of that total falling from June to August" — i.e. October is deep in the dry season.
- ~2,490 h of bright sunshine per year; air pollution/smog is a known recurring problem, especially with stagnant winter conditions.

From climatestotravel.com's Beijing climate page — https://www.climatestotravel.com/climate/china/beijing :
- October: average min/max **7 / 19.4 °C**, only **25 mm of rain over ~5 days**, ~**6.5 h sunshine per day**.
- "In autumn… both temperature and rainfall gradually decrease. **In October, rainfall becomes quite rare.** …in October, nights begin to be very cool."
- "The best times to visit Beijing are spring and autumn, and in particular… **from mid-September to mid-October**" — i.e. we are at the tail of the best window, but still inside the dry, sunny autumn regime.

### The one-line climatology comparison

October in **Beijing** ≈ 25 mm of rain over ~5 days, 6.5 h of daily sunshine, cool nights. October in **Guiyang** ≈ 90 mm of rain over ~14–16 days, 82 % humidity, 3 h of daily sunshine. Any given October day in Guiyang carries roughly a coin-flip chance of rain; in Beijing it's roughly 1 day in 6.

---

## 8. Recommendation

### Run the orientation at **BUPT, Beijing**, on **Saturday 24 – Sunday 25 October 2026**.

Why, quoting the numbers:

1. **Climatology (the most robust signal):** Beijing's October is dry (≈25 mm over ~5 rain days, 6.5 h sunshine/day) while Guiyang's October is wet and grey (≈90 mm over ~14–16 rain days, 82 % humidity, 3 h sunshine/day — "one of China's least sunny major cities"). For an outdoor, two-consecutive-day event, Beijing's base rate of a washout is far lower.
2. **Same dates last year:** Beijing was dry and mild both days (0.0 mm, highs 15.2/16.4 °C, partly cloudy, 53 % humidity); Guiyang was damp and cold (0.2 mm drizzle both days, 86 % humidity, 10.0 °C average on the 25th). The 2026 forecast's warm-and-mild Guiyang is possible, but last year's outcome is the more typical one.
3. **The forecast on the chosen days is close to a tie, so it shouldn't override the climate:** Beijing 24–25 Oct shows 0.1 mm (24 %) and 3.8 mm (34 %) with highs 17.7/13.4 °C; Guiyang shows 0.6 mm (32 %) and 0.0 mm (19 %) with highs 24.3/24.5 °C. If anything tips this toward Guiyang, it's warmth — not dryness.
4. **A strong fallback window exists at BUPT:** if 24–25 Oct turns wet in Beijing, the outlook is bone-dry there 26–30 Oct (0.0 mm, ≤ 3 % rain chance every day). Guiyang's driest stretch is only 24–28 Oct, and even then it's overcast/drizzly nearly every other day of the 14-day window.
5. **Practical daylight:** Beijing 06:34–17:22 and 06:35–17:21 on the two days (~10 h 47 m); Guiyang 06:57–18:16 and 06:58–18:16 (~11 h 19 m). Both work; Guiyang gives a bit more evening light.

### ⚠️ The one serious caveat — Beijing air quality

At the time of this pull, Beijing's PM2.5 was **119 µg/m³ (US EPA index 4 — "unhealthy for sensitive groups")** under smoky haze, versus Guiyang's **15.9 µg/m³ (index 2)**. Autumn/winter haze is a recurring Beijing pattern. If the AQI forecast for 24–25 Oct stays in that range, the healthier outdoor venue is Guiyang — and its 25–26 Oct outlook (0.0 mm, 19 %/18 % rain) is the cleanest two-day slot in its window. **Check the AQI and rain forecast again ~48 h before the session (see the "Open questions" issue) and be ready to flip to GZU if Beijing's air is bad but Guiyang's rain risk stays low.**

---

## 9. Caveats

- Forecasts 5+ days out have limited skill; treat the 24–25 Oct numbers as provisional and re-check closer to the date.
- "Coordinates" are the grid points the weather services resolve for each city name, not the exact campus locations.
- Two climate sources were used per city (Wikipedia/CMA normals and climatestotravel.com); their October figures agree closely.
