# Freight Corridor Planner

Interactive planning tool for international freight. Choose the exporter's city and the importer's city (roles can be swapped), describe the cargo, and compare sea, air, rail and road options on total landed cost, door-to-door time and risk.

**Live tool:** https://riskwork.github.io/freight-corridor-planner/

## What it does
- **Container and load planner**: define materials (size, weight, stacking, value per unit). The planner loads them into 20ft, 40ft and 40ft high-cube containers, a 40ft + 20ft mix, or a shared container (LCL), prices each on the selected route and picks the cheapest. A to-scale side view and floor plan show how the goods sit inside.
- **Route comparison**: sea (including Red Sea / Cape and Panama alternatives), air, rail (Middle Corridor; Northern route flagged for sanctions) and road, ranked by total landed cost = cash cost + cost of time + cost of risk.
- **Risk indicators**: chokepoint status (Bab el-Mandeb, Suez, Hormuz, Malacca, Panama, Gibraltar, Cape), road borders, transshipments, sanctions exposure.
- **Animated corridor map** and a step-by-step journey strip.
- Every term has an "i" explanation; assumptions are editable.

## Sources and limits
Sea rates calibrated to the Drewry World Container Index (1 Oct 2026); chokepoint status as of 11 Oct 2026; road distances from Google Maps. Planning estimates only, not freight quotes. Customs duties and taxes are not included.

Single self-contained HTML file; no data is collected or sent anywhere.
