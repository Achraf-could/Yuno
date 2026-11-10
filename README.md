# 🚀 Space Survival 3D | النجاة في الكون

A 3D space survival game that runs in the browser. It is a single HTML file, with no build step and no install. Fly a rocket through a huge universe of galaxies, suns and planets, fight bots or friends, and jump into the 4th dimension.

لعبة نجاة في الفضاء ثلاثية الأبعاد تشتغل في المتصفح من ملف HTML واحد، بدون تثبيت. تطير بصاروخك في كون واسع فيه مجرات وشموس وكواكب، وتقاتل البوتات أو أصحابك، وتدخل البعد الرابع.

---

## ▶️ Play / العب

Open `index.html` in any modern browser, on phone or desktop. Landscape mode is recommended on mobile.

To host it for free, use **GitHub Pages**:

1. Create a repository and upload `index.html` (rename `game.html` if needed) and this `README.md`.
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, then pick `main` and `/ (root)`.
4. Your game will be live at `https://<your-username>.github.io/<repo-name>/`.

> The game loads Three.js (r128) from the cdnjs CDN, so it needs an internet connection the first time.

---

## ✨ Features / المميزات

- **3D graphics:** a low-poly look with flat-shaded rockets, asteroids, suns and planets.
- **Space style interface:** a dark cosmic theme with neon cyan and purple glow, round close buttons and a futuristic font.
- **Single player:** 5 stages with growing difficulty (1 to 5 bots). Destroy all the bots to win a stage. Progress is saved in the browser.
- **Multiplayer rooms (local):** 3 rooms (Alpha, Beta, Gamma) with different arena sizes. Up to 4 players on the same device, each with their own rocket color (10 colors). Humans and bots can be mixed. The last one standing wins.
- **A vast universe:** 4 spiral galaxies, 3 suns that burn when you get too close, and 8 planets. Each planet has its own orbit, rotation, gravity and a moon, and some have rings.
- **Landing:** land on any planet to repair and refill boost, then take off again.
- **Boost:** a speed boost with an energy bar.
- **Target lock:** enemy markers with distance, edge arrows for off-screen enemies, a lock-on button with auto-aim, and an aiming reticle.
- **4D dimension:** enter the galaxy portal (from stage 3) and you can phase between two layers. You only hit things in your own layer.
- **Languages:** English, Français, العربية (with RTL support).
- **Audio and visual effects:** generated sound effects and music (Web Audio API), explosions, screen shake and flashes.
- **Settings:** language, field of view (POV), music volume and sound effects volume.

---

## 🎮 Controls / التحكم

| Player | Turn | Thrust | Fire | Boost | 4D phase |
|---|---|---|---|---|---|
| 1 | `A` / `D` | `W` | `Space` | `E` | `Left Shift` |
| 2 | `←` / `→` | `↑` | `Enter` | `.` | `Right Shift` |
| 3 | `J` / `L` | `I` | `U` | `P` | `O` |
| 4 | `F` / `H` | `T` | `R` | `V` | `Y` |

In single player you can also use the arrow keys, and the rocket cruises forward automatically.

Extra keys in single player: `Q` locks the next enemy and `L` lands or takes off. `Esc` returns to the menu.

**Touch (mobile):** drag on the left side of the screen to steer. The buttons on the right are 🔥 fire, 🚀 boost, 🎯 lock target, 🛬 land, and 4D (shown after you enter the portal).

---

## ⚠️ Notes / ملاحظات

- Multiplayer rooms are **local only** (same device). Online play would need a peer-to-peer layer such as WebRTC (PeerJS) or a backend like Firebase, because GitHub Pages only serves static files.
- The Exit button cannot close the browser tab, because browsers do not allow it. It shows a goodbye screen instead.
- Stage progress is saved with `localStorage`.

---

## 🛠️ Tech / التقنية

- Plain HTML, CSS and JavaScript in a single file
- [Three.js](https://threejs.org/) r128 for 3D rendering
- Web Audio API for sound
- 2D canvas overlay for enemy markers and the reticle

---

## 📄 License / الرخصة

Choose the license you prefer, for example MIT, and add a `LICENSE` file.
