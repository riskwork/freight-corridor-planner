# Freight Corridor Planner

Interactive planning tool for international freight. Choose the exporter's city and the importer's city (roles can be swapped), describe the cargo, and compare sea, air, rail and road options on total landed cost, door-to-door time and risk.

**Live tool:** https://riskwork.github.io/freight-corridor-planner/

## What it does
- **Container and load planner**: define materials (size, weight, stacking, value per unit). The planner loads them into 20ft, 40ft and 40ft high-cube containers, a 40ft + 20ft mix, or a shared container (LCL), prices each on the selected route and picks the cheapest. A to-scale side view and floor plan show how the goods sit inside.
- **Route comparison**: sea (including Red Sea / Cape and Panama alternatives), air, rail (Middle Corridor; Northern route flagged for sanctions) and road, ranked by total landed cost = cash cost + cost of time + cost of risk.
- **User-defined corridor risk**: set each chokepoint (Bab el-Mandeb, Red Sea, Suez, Hormuz, Malacca, Panama, Gibraltar, Cape) and Middle East airspace to Open, Watch, High risk or Closed, and edit the chance of disruption, delay, war-risk surcharge, insurance add-on and diversion cost. Closing a chokepoint reroutes ships. Presets (baseline, calm, Red Sea escalation, Gulf escalation) and shareable scenario links.
- **Risk indicators**: risk score per route from chokepoints, road borders, transshipments and sanctions exposure.
- **Animated corridor map** and a step-by-step journey strip.
- Every term has an "i" explanation; assumptions are editable.

## Sources and limits
Sea rates calibrated to the Drewry World Container Index (1 Oct 2026); baseline chokepoint status as of 11 Oct 2026 (users can override it); road distances from Google Maps. Planning estimates only, not freight quotes. Customs duties and taxes are not included.

Single self-contained HTML file; no data is collected or sent anywhere.
