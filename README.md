# NBA Web Project

A responsive, multi-page website dedicated to the NBA — featuring all 30 teams, a Hall of Fame gallery, and team-specific pages with player rosters, trophies, and social media links.

Built as a university project for a Web Development module.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

---

## Check it Live

https://aggelosthan.github.io/nba-site/

## Features

- **Homepage** — Hero section with background video, NBA overview, and a grid of all 30 team logos linking to individual team pages
- **30 Team Pages** — Each team has its own page with:
  - Custom colors, fonts, and wallpaper
  - Team history and info
  - Trophy count
  - Player roster cards with portraits
  - Social media links (Facebook, X/Twitter, Instagram, YouTube, TikTok)
- **Hall of Fame** — Image slider showcasing legendary NBA moments and players
- **Responsive Design** — Fully responsive across desktop, tablet, and mobile with a hamburger menu navigation
- **CSS-only Hamburger Menu** — No JavaScript required for mobile navigation

## Tech Stack

- HTML5
- CSS3 (Flexbox, Media Queries, CSS `clamp()`, custom fonts)
- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) (Roboto Slab)

## Project Structure

```
NBA Web Project/
├── index.html                 # Homepage
├── html/
│   └── hall-of-fame.html      # Hall of Fame gallery
├── teams-webpages/            # 30 individual team pages
│   ├── celtics.html
│   ├── lakers.html
│   ├── warriors.html
│   └── ...
├── css/
│   ├── style.css              # Global styles
│   ├── homepage.css            # Homepage-specific styles
│   ├── navbar.css              # Navigation & footer
│   ├── queries.css             # Homepage media queries
│   ├── hall-of-fame.css        # Hall of Fame page
│   ├── about-us.css            # About Us page
│   └── team-css/
│       ├── teams.css           # Shared team page template
│       ├── teams-queries.css   # Team pages media queries
│       ├── celtics.css         # Team-specific colors & assets
│       ├── lakers.css
│       └── ...
├── images/                    # Team images, logos, backgrounds
├── players-portraits/         # Player headshot images
└── fonts/                     # Custom team fonts
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/aggelosthan/nba-site.git
   ```
2. Open `NBA Web Project/index.html` in your browser.

No build tools or dependencies required — it's pure HTML & CSS.


## Authors

- **Angelos Thanasai** — Project Lead
- **Loukas Kougiatsos**
- **Grigoris Karakitsos**
- **Mihail Popesku**

## Disclaimer

All NBA team logos, player images, and related assets are the property of the NBA and their respective owners. They are used here strictly for educational purposes as part of a university project. We do not claim ownership of any licensed content.
