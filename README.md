# Supply Chain Games

Two free classroom games for supply chain and operations management. Students play in teams, each on their own phone or laptop, in a classroom or an online class. Nothing to install.

**Play:** https://ashir-mansuri.github.io/supply-chain-games/

## The games

**Supplier Showdown** (about 30 minutes of play). Teams buy four parts for an electric scooter maker from suppliers in China, Vietnam, India and Germany. Over eight months they face fires, floods, tariffs and chip shortages. Online, each member manages some of the parts, and orders go out when everyone taps Ready. Topics: supplier selection, total cost of ownership, dual sourcing, buffer stock and supply risk.

**Warehouse Rush** (about 20 minutes of play). Teams pick customer orders on a warehouse map, use ABC analysis to move fast sellers next to dispatch, then try batch picking. Online, members take turns as the picker and everyone sees the picker move live. Topics: Pareto principle, slotting, pick routes and picking productivity.

The **teacher dashboard** (`teacher.html`) creates a class with a code and a PIN for each team, and shows every team's progress and score live.

The **teacher's guide** (`teacher-guide.html`) has the online setup steps, 60-minute lesson plans, the rules behind each game, debrief answer points and follow-up assignments.

## Files

| File | What it is |
| --- | --- |
| `index.html` | Home page |
| `supplier-showdown.html` | Supplier Showdown game |
| `warehouse-rush.html` | Warehouse Rush game |
| `teacher.html` | Teacher dashboard |
| `teacher-guide.html` | Teacher's guide |
| `firebase-config.js` | Online play settings (paste your Firebase config here) |

There are no folders to upload.

## Publishing on GitHub Pages

1. Upload the files above and this README to the root of the repository.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose **main** and **/ (root)**, then **Save**.
4. After a minute or two, the site is live at `https://<your-username>.github.io/supply-chain-games/`.

## Switching on online team play

Online play uses a free Google Firebase Realtime Database. The steps are in the teacher's guide, under **Online team play > One-time setup**. Without it, both games still work in "practise on one device" mode.

All companies, products, prices and events in the games are made up for teaching.
