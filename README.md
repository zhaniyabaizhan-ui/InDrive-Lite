# inDrive Lite (Demo)

A simplified demo of the **inDrive** app focused on the EXPO district in Astana.  
This project showcases both **Passenger** and **Driver** perspectives in a 3km sandbox environment.

---

## Features

### Passenger Mode
- A→B trip planning with interactive map.
- Option to add **POI stops**: ATM, Bakery, Pharmacy, Flowers.
- Route optimization with ETA comparison.
- Simulated geotracker (blue dot for current location).
- Clean inDrive-style interface (white-green).

### Driver Mode
- **Demand heatmap**: yellow - orange clusters.
- **Events layer**: concerts, matches, exhibitions with details.
- **Ripening zones**: areas expected to have outgoing demand in N minutes.
- Side panel with **Top 3 demand zones now** and ETA from driver.

---

## Sandbox
- Focused on the **Astana EXPO District** (radius 3km).
- Mock POIs (rating 4.2–4.9).
- Events and ripening zones.

---

## Screenshots
Passenger mode:

![Passenger Demo](/passenger.mode.png)

Driver mode:

![Driver Demo](/driver.mode.png)

---

## Tech / Data
- Mock data for POIs, events, and demand zones.
- Map rendering with **Leaflet/OSM**.
- Files organized into:  
  - `/Pages` (PassengerMode, DriverMode, RoleSelection)  
  - `/Components` (map, ui)  
  - `/Entities`, `/POI`, `/DemandZone`.

---

## Team Notes
- This is a clickable demo prototype, not a full production app.
- All data is anonymized and synthetic.

---

## Contact
For demo and feedback:  
Maintainer – zhaniyabaizhan-ui  

