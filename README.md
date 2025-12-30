# ʻŌlelo Hawaiʻi Daily Practice App

**Ma ka hana ka ʻike** - *In doing, one learns*

A cultural learning tool that teaches Hawaiian values through daily practice, not just translation. This app presents Hawaiian concepts with their deeper cultural context and practical applications for everyday life.

## 🌺 Features

- **Value of the Day**: Random Hawaiian value displayed daily with full cultural context
- **Progress Tracking**: Tracks days practiced and values explored using localStorage
- **Cultural Depth**: Each value includes pronunciation, cultural context, practical applications, and related concepts
- **Hawaiian Proverbs**: ʻŌlelo noʻeau (traditional sayings) provide additional wisdom
- **Responsive Design**: Works seamlessly on mobile, tablet, and desktop
- **Offline-First**: All data stored locally, no API dependencies

## 📚 Content

22 Hawaiian values across 5 categories:

- **Values (8)**: Aloha, Pono, Kuleana, Mālama, Mahalo, Kōkua, Lōkahi, Hoʻoponopono
- **Family (5)**: ʻOhana, Kūpuna, Keiki, Makua, Hānai
- **Nature (5)**: ʻĀina, Kai, Mauna, Wai, Moana
- **Cultural Practices (3)**: Hula, Oli, Hana Noʻeau
- **Cosmology (1)**: Kumulipo

## 🎨 Design

**Color Palette** - Taro & Ocean theme:
- Taro Purple: `#7B5B8A`
- Soft Cream: `#FAF3E0`
- Deep Ocean Blue: `#1A5F7A`
- Seafoam Teal: `#5FB3B3`
- Charcoal: `#2D2D2D`

**Typography**:
- Headings: Merriweather (serif)
- Body: Open Sans (sans-serif)

## 🚀 Deployment

### Netlify Deployment (Recommended)

1. **Initialize Git Repository**:
```bash
git init
git add .
git commit -m "Initial commit: ʻŌlelo Hawaiʻi Daily Practice App"
```

2. **Create GitHub Repository** (optional but recommended):
```bash
gh repo create olelo-hawaii-app --public --source=. --remote=origin --push
```

3. **Deploy to Netlify**:
   - Go to [Netlify](https://app.netlify.com)
   - Click "Add new site" → "Import an existing project"
   - Connect your GitHub repository
   - Build settings:
     - Build command: (leave empty)
     - Publish directory: `.` (root)
   - Click "Deploy site"

### Alternative: Netlify Drop

1. Drag and drop the entire project folder into [Netlify Drop](https://app.netlify.com/drop)
2. Your site will be live instantly

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS (via CDN)
- **Storage**: LocalStorage API for progress tracking
- **Hosting**: Netlify
- **Data**: Local JSON file (22 Hawaiian values)

## 📱 Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Learning Approach

This app takes a **culturally grounded approach** to language learning:

1. **Context over Translation**: Each value is presented with cultural significance, not just dictionary definitions
2. **Practical Application**: Users learn how to practice each value in daily life
3. **Interconnections**: Related concepts show how Hawaiian values form an integrated worldview
4. **Daily Practice**: One value per day encourages deep reflection over rushed memorization

## 📖 Data Structure

Each Hawaiian value includes:
- `hawaiian`: The Hawaiian term
- `pronunciation`: Phonetic guide
- `english`: English translation
- `cultural_context`: Deep cultural meaning
- `practical_application`: How to practice this value today
- `related_concepts`: Connected Hawaiian values
- `olelo_noeau`: Traditional Hawaiian proverb (when applicable)

## 🙏 Cultural Notes

This app was created with respect for Hawaiian culture and language. It focuses on:
- Practical, everyday applications of values
- Cultural context that avoids spiritual appropriation
- Accurate pronunciation guides
- Interconnected worldview of Hawaiian values

## 👨‍💻 Developer

**Derek** - Portfolio Project 4/4

This project demonstrates:
- Vanilla JavaScript proficiency
- Cultural competency and research
- Data modeling and relationships
- UI/UX design with accessibility
- LocalStorage API implementation
- Responsive design principles

## 📝 License

Educational use. Please respect Hawaiian culture and language when using or adapting this content.

---

**E ola mau ka ʻōlelo Hawaiʻi** - *May the Hawaiian language live on*
