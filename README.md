
# BrewIt

## Overview

**BrewIt** is a modern, interactive web app that helps you explore, learn, and experiment with a huge variety of coffee recipes from across the globe.  
Filter by style (hot, iced, remix), search by name, sort by calories or type, instantly see estimated nutrition and caffeine, and get step-by-step instructions in both expert and beginner-friendly language.

---

## Features

- 🗃️ **Recipe Database**: Over 170 thoughtfully selected international coffees and creative remixes.  
- 🔥 **Favorites Support**: Uses local storage; filter by hot, iced, and remix types.  
- 🔍 **Live Search & Sort**: Locate and arrange recipes quickly by type, name, or calories.  
- 👨‍🍳 **Detailed Instructions**: Both plain language and barista-jargon guides.  
- 🍶 **Personalization**: Modify the type, amount, sugar, ice, and toppings of the milk.  
- 📊 **Instant Nutrition & Caffeine Info**: Real-time calculations based on your choices.  
- 💖 **Bookmarks**: Save your favorite brews and revisit them anytime.  
- 🎨 **Responsive UI**: Includes modern styling and Dark Mode support.  
- 🚀 **Remix & Quiz Mode**: Generate random combinations or play with coffee trivia.  
- 🥇 **Static Site**: 100% static, works locally or via GitHub Pages, no backend needed.  

---

## Project Structure

```
BrewIt/
│── BrewIt.html
│── public/
│   └── images/
│── src/
│   ├── data/
│   │   └── recipes.json
│   ├── script/
│   │   └── script.js
│   └── styles/
│       └── styles.css
│── README/
│   └── README.md
```

---

## Getting Started

### 1. Open Directly

Just open `BrewIt.html` in your browser.

### 2. Run Local Server (Recommended)

```bash
# For Python 3
npx http-server .
```

Then visit:  
`http://localhost:8000/BrewIt.html`

---

## Usage

- **Explore Recipes**: Cards show the title, quick ingredients, and preview steps.  
- **Filter**: Use Hot, Iced, Remix, or All tabs/buttons.  
- **Search**: Use the top search bar with live filtering.  
- **Sort**: Choose from Name, Calories, or Type in the dropdown.  
- **Details**: Click a card to open a modal. Switch between "easy" and "jargon" views.  
- **Customize**: Modify milk, sugar, foam, etc., and see updated nutrition info.  
- **Favorite**: Click ❤️ to mark favorites (saved in your browser).  
- **Extras**: Enjoy quizzes or remixes from the interactive UI.

---

## Data and Customization

- **Recipes**: Located in `src/data/recipes.json`.  
  - Expand by adding entries in the existing format.  
- **Images**: Update image paths in JSON and place images in `public/images/`.  
- **Style**: Edit `styles.css` to customize dark/light mode or branding.

---

## Technologies Used

- **HTML5**, **CSS3** (Responsive grid, dark mode)  
- **JavaScript** (ES6+)  
- **JSON** for dynamic data  
- ✅ No frameworks, no build steps, no backend  
- ✔️ Tested in Chrome, Firefox, Safari, Edge (recent versions)

---

## Known Issues

- Image paths must match your deployment/subfolder structure.  
- Adjust base path or relocate assets for GitHub Pages.  
- Use a local server for development — some browsers block `file:///` AJAX.  
- Nutrition estimates are based on USDA averages.  
- Quiz/Remix mode is basic and can be expanded for more interactive features.

---

## Contact Information

- **Nallam Sruja** — [nallamsruja@gmail.com](mailto:nallamsruja@gmail.com)  
- **G Sai Naman** — [sainamangangiredla@gmail.com](mailto:sainamangangiredla@gmail.com)
