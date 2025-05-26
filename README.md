```markdown
# 🏈 Football Team Cards App

A simple interactive web app to display football (soccer) players as cards. Users can filter players by position using a dropdown menu. Built using HTML, CSS, and JavaScript.

## 🚀 Features

- View team details: team name, year, and head coach
- Display player cards with name and position
- Highlight the team captain
- Filter players by:
  - All Players
  - Forward
  - Midfielder
  - Defender
  - Goalkeeper

## 📁 Project Structure

``

football-team-cards/
├── index.html          # Main HTML layout
├── styles.css          # Styling for the app
├── script.js           # JavaScript logic
└── README.md           # Project documentation

``

## 🧠 User Stories

✅ A `footballTeam` object is defined with:
- `team` (string)
- `year` (number)
- `headCoach` (string)
- `players` (array of objects)

✅ Each player object includes:
- `name` (string)
- `position` (one of "forward", "midfielder", "defender", "goalkeeper")
- `isCaptain` (boolean)

✅ One player is marked as captain.

✅ Team info is rendered inside HTML elements with IDs:
- `#team`
- `#year`
- `#head-coach`

✅ Players are rendered as cards in `#player-cards` with:
- `<div class="player-card">`
- `<h2>` with player name (and "(Captain)" if applicable)
- `<p>` with player position

✅ Dropdown menu filters players by position.

## 🛠️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/football-team-cards.git
``

2. Open the project folder:

   ```bash
   cd football-team-cards
   ``

3. Open `index.html` in your browser.

> No dependencies or build steps required.

## 📸 Preview

![Football Team Cards Screenshot](preview.png)

## 🧪 Tested User Cases

* ✅ Renders all players by default
* ✅ Filters by "forward", "midfielder", "defender", "goalkeeper"
* ✅ Captain is marked correctly
* ✅ DOM updates with dropdown selection

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

### 👨‍💻 Author

**Jordan Leturgez**

* Indiana
* [LinkedIn]([https://linkedin.com](https://www.linkedin.com/in/jordan-leturgez-832511101/))
* [GitHub]([https://github.com/your-username](https://github.com/JCaesar45))

