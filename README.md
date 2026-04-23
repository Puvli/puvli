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

## Skills

| Area | Technologies |
|------|-------------|
| Frontend | HTML, CSS, JavaScript, React, Redux, mobX, TypeScript, Vue, Angular |
| Auth & BaaS | Firebase Authentication |
| Tooling | Webpack, Vite, Docker, Git, GitHub Actions |
| APIs | REST, WebSocket, CoinGecko API |
| Other | HTML5 Canvas, Recharts, Game Development, SEO |

## Contact

- **Email:** pavel-zajtsev@yandex.ru
- **GitHub:** [Puvli](https://github.com/Puvli)

Thanks for visiting!
