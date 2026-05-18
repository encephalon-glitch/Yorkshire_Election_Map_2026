**Yorkshire and the Humber — Local Election Map 2026**

An interactive ward-level political map of the 2026 local election results for Yorkshire and the Humber, built in Python and hosted via GitHub Pages.

**What it shows**

Ward boundaries coloured by winning party across three councils — Sheffield, Barnsley and Wakefield. Each ward is hoverable, revealing a bar chart breakdown of the top three candidates and their vote counts. Split-seat wards are flagged with contextual notes.

A separate Council composition layer displays pie charts showing the full seat composition of each council, not just the 2026 winners. This gives a more honest picture of who actually controls each authority.

**Features**

- Ward level results coloured by winning party
- Hover tooltips with candidate bar charts
- Toggleable council layers — Barnsley, Sheffield, Wakefield
- Council composition pie charts with smooth opacity fade on ward layers
- Independent council boundary overlay
- Toggleable bottom legend
- Fully attributed data sourcing

**Councils included**

- Sheffield Metropolitan Borough Council
- Barnsley Metropolitan Borough Council
- Wakefield Metropolitan Borough Council

Doncaster and Rotherham did not hold elections in 2026. Bradford, Kirklees and Calderdale had boundary changes — their 2026 GeoJSON is pending ONS publication.

**Data sources**

Official results sourced directly from Sheffield, Barnsley and Wakefield Metropolitan Borough Council websites. Ward boundary GeoJSON sourced from ONS Open Geography Portal (2022 boundaries).

**Built with**

Python 

**Dependencies**
geopandas
folium
mapclassify
pandas
branca
jinja2
requests
beautifulsoup4

**Authors**

Built by encephalon_zest · Co-authored with Claude (Anthropic) · 2026
