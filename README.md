# Arabic Coffee Man - Cookie Catcher Game

A browser-based game built with HTML5 Canvas and vanilla JavaScript. This project demonstrates front-end development skills relevant to data professionals who build interactive dashboards, data visualizations, and web-based analytical tools.

## Project Overview

| Attribute | Detail |
|-----------|--------|
| **Tech Stack** | HTML5, CSS3, JavaScript (Canvas API) |
| **Dependencies** | None (zero external libraries) |
| **File Size** | Single-file architecture (~15 KB) |
| **Platform** | Any modern browser |

## How to Play

1. Open `index.html` in your browser
2. Use **Arrow Keys** or **Mouse** to move the character
3. Catch items:
   - **Cookies** = +10 points
   - **Coffee** = +25 points (bonus!)
   - **Skulls** = Lose a life (avoid!)
4. You have **3 lives** - difficulty increases over time

## Data Specialist Perspective

This project touches several concepts familiar to data professionals:

- **Canvas rendering pipeline** - similar to how visualization libraries (D3.js, Plotly) render data points to screen
- **Game loop architecture** - analogous to real-time data streaming and event-driven processing
- **Collision detection algorithms** - fundamentally the same distance calculations used in clustering (K-Means, DBSCAN)
- **State management** - mirrors how ETL pipelines track data state through transformation stages
- **Progressive difficulty scaling** - demonstrates dynamic threshold adjustment, a concept used in anomaly detection

## Git Workflow Used

```bash
# Initialize repository
git init

# Stage specific files
git add index.html README.md

# Commit with descriptive message
git commit -m "Add feature description"

# Create remote repo and push (using GitHub CLI)
gh repo create repo-name --public --source=. --push

# Push subsequent changes
git push origin master
```

## Quick Start

```bash
# Clone the repository
git clone https://github.com/AbdullahAldhayan/arabic-coffee-cookie-catcher.git

# Navigate into the project
cd arabic-coffee-cookie-catcher

# Open the game (Windows)
start index.html

# Open the game (Mac)
open index.html

# Open the game (Linux)
xdg-open index.html
```

## Author

**Abdullah Aldhayan** - Data Specialist
