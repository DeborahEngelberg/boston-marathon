# Boston Marathon Operations Manual

A comprehensive guide for Boston Marathon runners and spectators, built as a single-page React application.

## Features

**Runner Mode (9 sections):**
- Course analysis with mile-by-mile elevation and terrain data
- Qualification standards and cutoff analysis
- Race day logistics (bus, village, corral, gear check with community intel)
- Fuel & hydration strategy by goal pace
- Weather intelligence and clothing layers
- Training framework
- Failure mode analysis (5 common patterns with physiological explanations)
- Interactive course map (Leaflet)
- Sources & citations

**Spectator Mode (9 sections):**
- Decision tree with Hopkinton trap warning and failure patterns
- 6 spot cards with transit, positioning, crowd behavior, and exit strategies
- 7 complete itineraries with pace math (including 4-stop expert route)
- Interactive course map with spectator/gel toggles
- Transit operations (MBTA closures, Commuter Rail, Green Line branches, fares)
- Post-finish reunion plan (fencing reality, Family Meeting Area, backup strategies)
- Gear & rules (B.A.A. prohibited items, what to carry, ADA viewing)
- Community tips from LetsRun, Reddit, and local forums
- 20+ sourced citations

## Tech Stack

- React 18 (CDN)
- Recharts (elevation chart)
- Leaflet (interactive course map)
- Babel standalone (in-browser JSX)
- Zero build step required
- No API keys or server dependencies

## Deploy to GitHub Pages

1. Create a new GitHub repository
2. Push this directory:
   ```bash
   git init
   git add .
   git commit -m "Boston Marathon Operations Manual"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```
3. Go to **Settings → Pages → Source: Deploy from a branch → Branch: main, / (root)**
4. Site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO/`

## Data Sources

Official: B.A.A. (baa.org), MBTA (mbta.com/Marathon), B.A.A. Participant Guide  
Community: LetsRun forums, Reddit (r/bostonmarathon, r/boston), Fodor's Travel, race reports  
All community intelligence is labeled as such throughout the guide.

## License

Content is for personal/informational use. Not affiliated with the B.A.A.
