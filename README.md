# FIFA 23 Ratings vs World Cup 2022 Match Outcomes

A data visualization project analyzing the correlation between FIFA 23 player ratings and the actual outcomes of the FIFA World Cup 2022 matches. Built using **D3.js** for interactive visuals and **PapaParse** for CSV data handling.

## Project Overview

This project displays a **scatter plot** comparing:
- Average overall ratings of the top 11 players of each national team (from FIFA 23)
- Their potential ratings
- Performance stats (wins, losses, draws) during the World Cup 2022

Each data point represents a national team, plotted based on their average overall and potential ratings, with tooltips showing match results.

## Dataset Sources

1. `Fifa 23 Players Data.csv`: Contains player names, nationalities, overall ratings, and potential.
2. `Fifa_world_cup_matches.csv`: Contains match results and participating teams in the World Cup 2022.

## Technologies Used

- **HTML5 & CSS3** – Layout and styling
- **D3.js (v7)** – Data-driven visualizations
- **PapaParse** – Client-side CSV parsing
- **JavaScript (ES6)** – Logic and interactivity

## Team Roles

| Member   | Role                            |
|----------|---------------------------------|
| **[@username1](https://github.com/hamna-shs)**   | UI/UX Styling (CSS)             |
| **[@okjazim](https://github.com/okjazim)**   | Data Handling & Logic (JS + Parsing) |
| **[@Lovenit36](https://github.com/Lovenit36)** | D3.js Visualizations           |

## Features

- Smooth animated hover effects
- Responsive design for various screen sizes
- Tooltips with team performance breakdown
- Interactive scatter plot
- Clean and modern UI

## Screenshot

- In Progress

## Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/okjazim/Fifa-Data-Demo.git
   cd Fifa-Data-Demo
   ```
2. Add the datasets:
   
   Place `Fifa 23 Players Data.csv` and `Fifa_world_cup_matches.csv` in the root directory.
   
3. Run locally:
   
   Open `index.html` in any browser.

> **Note**: This project requires local CSV file support. Some browsers might block file access due to security settings.  
> Use a local server like **Live Server** in VSCode or run this command in your terminal:

```bash
python -m http.server
```

## Future Enhancements
- Add legends and filters (e.g., by continent or group stage)
- Include more player stats (e.g., age, position)
- Mobile UI enhancements
- Export chart as image

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
