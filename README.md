# Geostrophic Wind Ruler · MB Sailing

🧭 Calm weather routing.  
✈️ Aviation discipline, applied offshore.  
🌬️ Practical meteorology, when the sea doesn't care about models.

---

## 🇩🇪 DE · Zweck & Einsatzbereich
Dieses Werkzeug wurde für die praktische Anwendung beim **Wetterrouting im Segelsport** entwickelt.  
Es ermöglicht eine schnelle, visuelle Abschätzung wesentlicher meteorologischer Größen direkt aus **Isobarenabständen**:

- Druckgradient (Pa/m)  
- geostrophischer Wind (m/s, km/h, kt, Beaufort)  
- geschätzter Bodenwind (Faktor ~60 % Land / ~70 % See)

Es dient der **Orientierung**, Schulung & taktischen Unterstützung.  
Es ersetzt **keine** amtlichen Wetterinformationen oder nautische Verantwortung an Bord.

---

## 🇬🇧 EN · Purpose & Concept
Developed for **offshore weather routing** and tactical decision support.  
This tool estimates wind from **isobar spacing** on a chart:

- Load a weather map (PNG/JPG)
- Calibrate via known latitude spacing (Δφ)
- Measure isobar distance (Δp)
- Compute:
  - pressure gradient (Pa/m),
  - geostrophic wind,
  - surface wind estimate (land/sea factor)

It is intended for orientation and learning purposes —  
**not** a replacement for official forecasts, warnings or navigational authority.

---

## 🎯 What you can use it for
- Passage planning (qualitative)
- „Is the gradient building?“ → situational awareness
- Regatta & offshore tactics
- Training / education (meteorology & navigation)
- Yacht delivery support (offline-friendly)

**Best practice:**

| Recommended for | Avoid for |
|-----------------|------------|
| synoptic scale ≥ 200 km | local thermal / katabatic flows |
| open sea pressure fields | Bora / Tramontana corner effects |
| trend analysis | föhnige Lee-Effekte / Kanalisation |

---

## 🌬️ How to use (Workflow)
1. **Karte laden** (GRIB Snapshot / Faxchart / MSLP Analysis)
2. **Δφ (°)** eingeben → zwei Punkte mit bekanntem Breitenabstand wählen
3. **Δp (hPa)** eingeben → zwei Punkte auf benachbarten Isobaren wählen
4. Ergebnis interpretieren:
   - Druckgradient → Pa/m
   - v<sub>g</sub> → geostrophischer Wind
   - 60–70 % v<sub>g</sub> → Bodenwind-Schätzung

🔗 Live Version:  
https://mb-sailing.com/gradient-tool.html

---

## 📱 Device Compatibility (v1.0)
| Device / Browser       | Status | Hinweise |
|-------------------------|--------|----------|
| Desktop / Laptop        | ✔️ stabil, scharf | empfohlen |
| iPad (Safari/Chrome)    | ✔️ nutzbar | Pan/Zoom per Buttons |
| Android (Chrome)        | ✔️ nutzbar | leichte Unschärfe möglich |
| iPhone                  | ⚠️ experimentell | abhängig von Bildgröße |
| HiDPI / Retina Displays | ⚠️ reduziert | Schärfe zugunsten Stabilität |
| Pinch-Zoom (Gesten)     | ❌ noch nicht | geplant v2 |

**Leitsatz für v1:**  
> *Predictability beats precision — always offshore.*

---

## 🧩 Roadmap
| Ziel | Status |
|------|--------|
| stabile Bedienung auf Mobilgeräten | ✔️ erreicht |
| Pan/Zoom per Buttons               | ✔️ |
| Fullscreen-Mode (Mobile)           | 🟡 geplant |
| HiDPI / Retina Canvas              | 🟡 geplant |
| Touch-Gesten (Pan & Pinch)         | 🟡 geplant |
| Beispielkarten / Templates         | 🔜 Idee |
| Mehrsprachige UI (EN/DE)           | optional |

---

## ⚖️ Liability & Responsibility
Dieses Tool vereinfacht meteorologische Zusammenhänge.  
Es ersetzt **keine** offiziellen Quellen, Warnungen oder nautische Entscheidungen.  
Verantwortung für Navigation und Betrieb verbleibt **immer an Bord.**

**Users remain fully responsible for vessel operation at all times.**

---

## 📜 License
**Creative Commons BY-NC 4.0 – Attribution · NonCommercial**  
https://creativecommons.org/licenses/by-nc/4.0/

- Attribution required  
- No commercial use or redistribution without permission  
- Forks & adaptations allowed under same license

© 2017–2025 **Matthias Baier · MB Sailing – All Oceans**  
📧 alloceans@mb-sailing.com  
🌍 https://mb-sailing.com

---

## 💬 Feedback / Contributions
Questions, observations, improvements — willkommen.

👉 Create an **Issue** to report behaviour or propose enhancements.  
👉 Forks welcome — but please respect the license.

---

