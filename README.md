# Maplogger BETA

Maplogger is a personal passion project of mine, designed to serve as an interactive companion app that guides gamers and completionists alike

**Features:**
- Render a high quality fantasy map
- 2 views: advanced and compact
- Place markers around the map
- Log info about the markers to a 'Notes' tab
- All logging will be saved
- Added POIs (Bosses)

**Currently supported games:**
- Elden Ring

**How it works (for the nerds):**
- React.JS + Vite for the frontend development and testing
- Express.JS + JSON files for backend
- Tiles generated using MapTiler Engine 12.2
- Map rendered using OpenLayers (yes i hate myself)
- Icons taken from FontAwesome

**Bonus Info:**
- I've made a few devtools and stored them under /src/frontend/Map and /src/backend folders as devtool.txt
- This will allow you (and subsequently me ofc) to add in new features down the road
- Currently, the devtools will allow you to log different points on the map as coordinates and parse them to a JSON
