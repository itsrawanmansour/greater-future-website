# 🌴Towards a Greater Future
A static multi-page website built with HTML5 and CSS3, showcasing Saudi Arabia's Vision 2030 milestones and major national projects — from NEOM and the Red Sea Project to hosting the World Cup 2034. Built as a Web Development course project.

🔗 **Live Demo:** [itsrawanmansour.github.io/greater-future-website](https://itsrawanmansour.github.io/greater-future-website/)

## Overview
The site is a themed, multi-page tour through Saudi Arabia's Vision 2030 achievements and giga-projects. It includes:

* **Home** — landing page introducing the site
* **Saudi Vision 2030** — overview of the national vision
* **Big Projects** — hub page linking to individual giga-projects
* **NEOM** — the futuristic city project
* **Expo 2030** — Saudi Arabia's Expo bid/hosting
* **World Cup 2034** — hosting the FIFA World Cup
* **Achievements** — national accomplishments and milestones
* **Events Participation** — participation in major events
* **Success Stories** — narrative/story content
* **Submission Confirmation** — a form submission confirmation page
* **Kingdom in the Lead** — a video feature page

## Tech Stack

* **HTML5** — page structure and content across 11 pages
* **CSS3** — shared stylesheet (`Project.css`) plus page-level inline styles for layout, navigation, and hover effects
* **Media** — image galleries per project (JPG/PNG) and an embedded video (`KingdomInTheLead.mp4`)

## Project Structure

```
greater-future-website/
├── index.html                     # Redirects to pages/Home.html
├── pages/
│   ├── Home.html
│   ├── SaudiVision.html
│   ├── BigProjects.html
│   ├── Neom.html
│   ├── Expo2030.html
│   ├── WorldCup2034.html
│   ├── Achievements.html
│   ├── EventsParticipation.html
│   ├── Stories.html
│   ├── Submission.html
│   └── KingdomInTheLead.html
└── assets/
    ├── css/
    │   └── Project.css
    ├── images/                    # NEOM, Expo, Red Sea, Qiddiya, Stadium, etc.
    └── video/
        └── KingdomInTheLead.mp4
```

## How to Use

1. Clone the repository.
2. Open `index.html` in any web browser — it redirects straight to the home page. (Or open `pages/Home.html` directly.)
3. Navigate the site using the top navigation menu, which links to all pages.

## Note
The original files had a few image references with inconsistent capitalization (e.g., `SaudiGirl.jpg` referenced but the file was `SaudiGirl.JPG`), which would fail on case-sensitive hosting like GitHub Pages. These were corrected during reorganization so all pages load correctly on any platform.

## Author
Rawan Mansour

This was a team project.
