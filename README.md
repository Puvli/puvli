# Hi, I'm Pavel Zaitsev 👋

Welcome to my project portfolio! I'm a frontend developer specializing in modern, interactive web applications. Here you'll find projects that showcase my skills and passion for building things on the web.

## About Me

I'm a frontend developer with commercial experience building high-traffic web applications. My core stack is **TypeScript, React, and Redux**. I've worked on products ranging from SPAs with authentication and API integration to HTML5 games and algorithm visualizations.

## Projects

### 1. [CryptoTracker](https://puvli.github.io/crypto-tracker/)

A single-page app for tracking cryptocurrency prices in real time. Features Firebase authentication (email/password + Google OAuth), interactive price charts across multiple timeframes, and a favorites system. Built with a glassmorphism UI and animated gradients. Auto-deployed to GitHub Pages via GitHub Actions.

**Key features:**
- Live prices for the top 50 cryptocurrencies by market cap
- Sparkline charts (7-day) + detailed charts (24h / 7d / 30d / 1y) powered by Recharts
- Authentication via Firebase Auth (email/password + Google OAuth)
- Favorites — works both with and without auth (falls back to localStorage)
- Search and filter coins by name or symbol
- Dark glassmorphism UI with animated gradients

**Tech:** React 18, TypeScript, Vite, React Router 6, Recharts, Firebase Authentication, CoinGecko API, GitHub Actions, GitHub Pages, Docker

---

### 2. [Space Defender — HTML5 Game](https://puvli.github.io/space-defender/)

A space shooter built with vanilla JavaScript and the HTML5 Canvas API. No frameworks or game engines — all mechanics are written from scratch: game loop on `requestAnimationFrame`, AABB collision detection, particle system, parallax scrolling, and touch controls for mobile.

**Key features:**
- Canvas 2D rendering at 60 FPS via `requestAnimationFrame`
- Particle system for explosion effects
- Two enemy types with sinusoidal movement and AI-driven shooting at randomized intervals
- Three-layer parallax starfield background
- Mobile controls — virtual joystick (left side) + fire zone (right side)
- Score system with high score saved to localStorage
- Progressive difficulty scaling

**Controls:** Desktop: WASD / arrow keys to move, Space to shoot | Mobile: touch

**Tech:** JavaScript (ES Modules), HTML5 Canvas 2D API, Vite, GitHub Pages, GitHub Actions (CI/CD)

---

### 3. [Mesto](https://github.com/Puvli/mesto)

An interactive web app where users can share photos and like each other's posts. Demonstrates object-oriented JavaScript and REST API integration.

**Key features:**
- Add and delete photos
- Like / unlike posts
- User registration and authentication
- Profile editing

**Tech:** HTML, CSS, JavaScript, Webpack

---

### 4. [React Stellar Burger](https://github.com/Puvli/react-stellar-burger)

A web app for assembling custom burgers from various ingredients. Users pick ingredients, build a burger, and see the total order cost. Built to practice React, Redux, and client-side routing.

**Key features:**
- Interactive burger builder with drag-and-drop
- Order cost calculation
- Server communication via REST API

**Tech:** HTML, CSS, React, Redux, React Router, React DnD, TypeScript

---

### 5. [Algososh](https://github.com/Puvli/algososh)

An algorithm and data structure visualization tool. Demonstrates sorting and search algorithms, as well as stacks, queues, and linked lists — all animated step by step.

**Key features:**
- Step-by-step algorithm visualization
- Interactive data structure demonstrations

**Tech:** HTML, CSS, React, TypeScript

---

## Skills

| Area | Technologies |
|------|-------------|
| Frontend | HTML, CSS, JavaScript, React, Redux, TypeScript |
| Auth & BaaS | Firebase Authentication |
| Tooling | Webpack, Vite, Docker, Git, GitHub Actions |
| APIs | REST, WebSocket, CoinGecko API |
| Other | HTML5 Canvas, Recharts, Game Development |

## Contact

- **Email:** pavel-zajtsev@yandex.ru
- **GitHub:** [Puvli](https://github.com/Puvli)
- **Telegram:** [@Puvli44](https://t.me/Puvli44)

Thanks for visiting!
