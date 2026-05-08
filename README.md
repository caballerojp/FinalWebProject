# 🌲 Baguio Guides – Your Chill Travel Buddy

**made with ☕ and no sleep**

So basically this is a website I made for people who wanna explore Baguio City without getting lost or bored. It's got everything — maps, weather, reviews, and a bunch of cool spots you should totally visit.

---

##  What's Inside

- [What Is This Even](#-what-is-this-even)
- [Cool Stuff It Can Do](#-cool-stuff-it-can-do)
- [How The Files Are Organized](#-how-the-files-are-organized)
- [How To Run It](#-how-to-run-it)
- [Accessibility](#-accessibility)
- [Stuff I Used](#-stuff-i-used)
- [Credits](#-credits)

---

##  What Is This Even

Basically a travel guide site for Baguio City (y'know, the "City of Pines" where it's actually cold in the Philippines lol). I wanted to make something that helps people find cool places to visit without digging through a million Google searches.

Perfect for:
- Tourists who have no idea where to go
- Locals who want to rediscover their city
- Anyone planning a Baguio trip

---

##  Cool Stuff It Can Do

### Home Page (`index.html`)
- **17 attraction cards** with pics and quick descriptions
- **Click a card** and BOOM — a popup appears with all the details (directions, tips, opening hours, everything)
- **Live weather** that actually updates (pulls from the internet, not just random numbers)
- **Real clock** ticking every second so you know what time it is in Baguio
- **Random spot suggestion** if you're feeling indecisive
- Works on phones too (responsive layout and all that)

### Map Page (`map.html`)
- **Google Map** smack in the middle of the page
- Click any spot from the list and the map flies to it
- The button you clicked lights up so you don't forget
- You can zoom, scroll, do whatever with the map
- Links from the home page modals go straight to the right spot on the map (so you don't have to search again)

### Reviews Page (`review.html`)
- Simple form — put your name, pick a place, write your thoughts
- New reviews show up at the top (freshest first)
- Won't let you submit empty stuff (validation says nope)
- Nice little popup saying "yay, submitted!" so you know it worked
- Escapes HTML so nobody can do sketchy things in the reviews

### Works Everywhere
- Keyboard-friendly — you can tab through everything
- Screen readers can read it properly
- Yellow outlines show where you are when tabbing
- Skip-to-content button (nice for people who don't wanna tab through the whole nav)
- Looks decent on mobile, tablet, and desktop

---

## 📁 How The Files Are Organized
 baguio-guides/
├── index.html ← main page with all the attraction cards
├── map.html ← map page with Google Maps and spot list
├── review.html ← reviews page with form and review cards
├── style.css ← all the styling (one file for everything)
├── Logo.png ← the little logo in the nav bar
├── background.jpg ← hero section background image
├── *.jpg / *.jpeg ← images for each attraction and modal
└── README.md ← this file you're reading 



---

##  How To Run It

Super easy:

1. Download or clone this whole thing
2. Open `index.html` in your browser
3. That's it. No server needed. No npm install. No stress.

Just make sure you have internet for the weather and map to work.

---

##  Accessibility

I actually tried to make this usable for people with different needs:

- **Semantic HTML** — proper headings, landmarks, labels
- **ARIA labels** where needed (screen readers can understand)
- **Keyboard navigation** — can use the whole site without a mouse
- **Focus indicators** — bright yellow outline so you know where you are
- **Skip link** — jump right to the good stuff
- **Color contrast** — text is actually readable (not light gray on white like some sites smh)
- **Responsive** — doesn't break on different screen sizes

---

## 🛠 Stuff I Used

- **HTML5** — structure
- **CSS3** — making it pretty (gradients, shadows, animations, flexbox, grid)
- **Vanilla JavaScript** — all the interactivity (no frameworks, just raw JS)
- **Open-Meteo API** — free weather data (no API key needed, bless them)
- **Google Maps Embed** — for the interactive map
- **No frameworks, no libraries** — just plain code (ok maybe I'm a little proud of that)

---

##  Credits

- **Weather data** — [Open-Meteo](https://open-meteo.com/) (free weather API, absolute legend)
- **Map** — Google Maps
- **Photos** — taken from various sources (all of Baguio City attractions)
- **Inspiration** — Baguio City itself. Seriously, go visit if you haven't.
- **Me** — a tired but happy developer who just wanted to build something useful


##  License

This project is licensed under the Accessibility License — basically means anyone can use it, learn from it, or build on top of it. Just don't claim you made it from scratch lol.

Go touch some grass (or pine trees 🌲).


**Made with love, caffeine, and the cold Baguio breeze 🍃**
