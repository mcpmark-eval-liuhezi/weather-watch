# Astrophotography Workshop — Site Weather Report

**Shoot night:** Saturday, 2026-10-24
**Analysis run:** Wednesday, 2026-10-21 (12:49–13:02 Asia/Shanghai — both sites share this timezone)
**Sites compared:** Beijing, Beijing (39.93°N, 116.39°E) vs Guiyang, Guizhou (26.58°N, 106.72°E)
**Data source:** WeatherAPI via MCP tools

## ⚠️ Data coverage note

The 7-day forecast endpoint returns daily summaries plus hourly data. For **both** cities the
response was truncated by the API's response-size limit inside Day 1's hourly array, so the
daily blocks for 2026-10-22 → 2026-10-27 (including Saturday the 24th) **could not be
retrieved**. Alternative endpoints could not fill the gap (the future-weather endpoint only
accepts dates ≥14 days out; history covers past dates only).

What **is** complete and verified:
- Current conditions and the first forecast day (Wed 2026-10-21) for both cities
- All active weather alerts for both cities
- Full astronomy data for Saturday evening 2026-10-24 at both cities
- Full historical data for the same calendar date one year earlier (2025-10-24) at both cities

The recommendation therefore leans on the current synoptic pattern, the retrieved forecast
day, alert status, Saturday astronomy, and last year's same-date climatology. A final forecast
check closer to Saturday is advised before departure.

---

## 1. Beijing

### Forecast (retrievable portion — 7-day request, Day 1 returned)

| Date | Condition | High | Low | Max wind | Rain chance | Precip | UV |
|---|---|---|---|---|---|---|---|
| Wed 2026-10-21 (today) | Sunny | 16.6 °C | 9.1 °C | 22 km/h | 0 % | 0.0 mm | 3 |
| Thu–Tue (10-22 → 10-27) | *not returned by API (truncated) — see note* | | | | | | |

**Current conditions (Wed 13:00):** Sunny, 15.2 °C, NW wind 20.9 km/h gusting 34.3 km/h,
humidity 14 %, cloud 0 %, visibility 10 km, rain chance 0 %.

### Active weather alerts

- **Blue (Level IV) gale warning — Haidian District Met Station** (severity: Minor):
  force-3 NW winds, gusts force 6–7, locally force 8 in the hills/shallow mountains.
  Effective 2026-10-20 17:29 → **expires 2026-10-23 17:29** (the day *before* the shoot).
- **Blue (Level IV) gale warning — Shijingshan District Met Station** (severity: Minor):
  same profile. Effective 2026-10-20 18:05 → **expires 2026-10-23 18:05**.

Both alerts expire Friday, i.e. before Saturday night.

### Saturday 2026-10-24 evening astronomy

| Item | Value |
|---|---|
| Sunset | **05:22 PM** |
| Sunrise (Sun) | 06:34 AM |
| Moonrise | 04:08 PM |
| Moonset | 04:20 AM (Sunday) |
| Moon phase | **Waxing Gibbous** |
| Moon illumination | **92 %** |

### Same date last year — 2025-10-24 (Beijing)

- Partly cloudy; high 15.2 °C / low 9.1 °C; **no precipitation (0.0 mm, 0 % rain chance)**
- Max wind 11.2 km/h; avg humidity 53 %; visibility 10 km; UV 2
- Night hours 00:00–05:00: clear to partly cloudy, 9.5–11.2 °C, light SSW breeze (≤5 km/h)
- Moon: Waxing Crescent, **13 % illumination**; moonrise 09:35 AM, moonset 06:40 PM — dark skies from evening onward

---

## 2. Guiyang

### Forecast (retrievable portion — 7-day request, Day 1 returned)

| Date | Condition | High | Low | Max wind | Rain chance | Precip | UV |
|---|---|---|---|---|---|---|---|
| Wed 2026-10-21 (today) | Light drizzle | 15.6 °C | 11.8 °C | 16.2 km/h | 92 % | 12.0 mm | 0.8 |
| Thu–Tue (10-22 → 10-27) | *not returned by API (truncated) — see note* | | | | | | |

**Current conditions (Wed 12:45–13:00):** Light rain / patchy rain nearby, 12.6 → 12.3 °C,
NE–ENE wind 11.5–13.7 km/h, humidity 88–90 %, cloud 100 %, rain chance 36–78 %,
1.93 mm accumulated.

### Active weather alerts

- **None.**

### Saturday 2026-10-24 evening astronomy

| Item | Value |
|---|---|
| Sunset | **06:16 PM** |
| Sunrise (Sun) | 06:57 AM |
| Moonrise | 04:56 PM |
| Moonset | 04:55 AM (Sunday) |
| Moon phase | **Waxing Gibbous** |
| Moon illumination | **92 %** |

### Same date last year — 2025-10-24 (Guiyang)

- Cloudy; high 16.1 °C / low 9.2 °C; 0.2 mm precipitation; **daily rain chance 100 %**
- Max wind 13.7 km/h; avg humidity 75 %; visibility 10 km; UV 4.7
- Night hours 00:00–05:00: partly cloudy to cloudy, 9.4–9.9 °C, ENE ~13 km/h, no rain in those hours
- Moon: Waxing Crescent, **13 % illumination**; moonrise 09:35 AM, moonset 08:02 PM

---

## 3. Recommendation: **BEIJING**

**Beijing is the better bet for Saturday night, 2026-10-24.**

1. **Rain probability / synoptic pattern.** Beijing sits in a dry continental air mass —
   0 % rain chance, 0 mm precipitation, 18 % humidity, 0 % cloud in the retrieved forecast
   day. Guiyang is locked in a drizzle regime — 92 % daily rain chance, ~12 mm expected,
   100 % cloud, 88–90 % humidity. Last year's same calendar date mirrors the split exactly:
   Beijing dry and partly cloudy (0 mm, 0 % rain), Guiyang overcast with rain flagged
   (100 % daily rain chance, 0.2 mm). For a go/no-go call, both the current pattern and the
   same-date climatology point to Beijing.

2. **Overall conditions.** Beijing's very dry, clear air (dew point ~12 °C below air
   temperature) means excellent transparency and low dew risk on optics. Guiyang's
   near-saturated air (dew point within ~2 °C of air temperature) is a dew magnet, and the
   Yunnan–Guizhou plateau cloud deck frequently fails to clear after dark in late October.

3. **Wind.** The only caution flag for Beijing — two blue-level (IV / minor) gale warnings
   for force-6–8 gusts — but both expire on 2026-10-23, a day before the shoot. Guiyang's
   winds are light (~12–14 km/h), which doesn't offset its cloud and rain problem. At
   Beijing, bring wind-braced mounts and expect residual gustiness to taper as the cold-air
   outbreak settles.

4. **Moonlight (decisive equalizer, not differentiator).** The moon is identical at both
   sites: **92 % waxing gibbous**, up from ~4–5 PM until ~4:20–4:55 AM — i.e. up all night.
   Faint deep-sky targets are off the table *regardless of site*; plan lunar, planetary, or
   bright-object work. Given that, the site with the clearer, drier, more transparent air
   wins, and that is Beijing.

5. **Night length.** Beijing's sunset (17:22) precedes Guiyang's (18:16) by 54 minutes, and
   sunrise follows 23 minutes later — roughly 31 more minutes of night at the northern site,
   with earlier astronomical darkness.

**Operational note:** Saturday's specific daily high/low/rain-chance numbers could not be
retrieved (API response truncation — see coverage note). This call is based on the retrieved
current conditions and Day-1 forecast, alert status, complete Saturday astronomy, and the
complete same-date history for last year. Re-check the Saturday forecast on Friday before
final travel plans.
