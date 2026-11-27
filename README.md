# Iron Meridian

A browser strategy war game in one file (`index.html`). There's nothing to install. It runs on Windows 11 (Edge, Chrome or Firefox) and on phones and tablets (Safari or Chrome).

## How to run

- **Windows 11:** download `index.html` and double-click it. It opens in your default browser.
- **Phone or tablet:** open the hosted link, or put `index.html` on the device and open it in the browser. The map supports tap, drag and pinch-zoom.
- **Hosting it yourself (optional):** turn on GitHub Pages for this repo (Settings → Pages → deploy from branch). The game is then at `https://<user>.github.io/War_Strategy-/`.

## What the game does

- **Real world map.** The map is the actual world: coastlines from Natural Earth (public domain) in a Miller projection, from 78°N to 56°S. Every new game carves it into 20–48 random nations, each with a real city as its capital (Paris, Tokyo, Lagos, São Paulo and so on). 226 real cities appear on the map, and cities are worth several times a normal street. Small islands belong to the nearest nation. Map sizes go up to Huge (400×181 squares) for an HD view. Every square on the map is one street block with its own street and district name. Hover over a square, or tap it, to see them. Territory changes hands one street at a time.
- **Modern demographic blocs.** Each nation takes its strengths from the bloc where its capital actually sits: Atlantic, East Asian, Eurasian Steppe, Gulf & Levant, South Asian, Latin, Sub-Saharan and Austro-Pacific. The bloc sets its military, economic and scientific strength, its population and its foreign-policy temperament.
- **Equal alliances.** Nations are grouped into 2–6 regional alliances. Every alliance starts with exactly the same strength index (40% military, 35% economy, 25% science). Battlefield power is also equalized, so no alliance starts ahead.
- **You get one nation in one alliance** and command that whole alliance. The computer runs every other alliance. It sets budgets, gangs up on weak targets, declares war when it has the edge and offers peace when it's losing.
- **Your nation's economy:** pick Mixed, Free market, State-planned, War economy, Knowledge economy or Resource exporter at setup, and switch in the Command tab (once every 6 months). It stacks on top of the world economic policy.
- **Weapons program:** a Convert slider in Command spends up to 4% of your stored science each month to raise troops immediately. You trade future technology (combat multiplier and income bonus) for soldiers now, so science, economy and military all have to be balanced. Computer alliances use it when they are losing.
- **World settings you choose:**
  - **Economy:** Free-trade, Mixed, Protectionism or War economy.
  - **Military doctrine:** Blitzkrieg, Conventional, Fortress or High-tech.
  - **Foreign policy:** Total war, Realpolitik, Cold war or Anarchy.
- **Betrayal.** Any nation can backstab its alliance. The remaining members then split according to each one's own foreign policy:
  - Loyalists stay.
  - Pragmatists join whichever side is stronger.
  - Opportunists tend to follow the traitor.
  - Isolationists may go neutral.

  You can betray your own alliance from the World tab.
- **Goal.** Conquer the world (or 75% / 60% of it, if you pick that setting). The game has a hard time limit of 20–90 minutes. When time runs out, the alliance holding the most land wins.
- **Autosave.** The game saves to the browser after every game month and whenever you refresh or close the page. When you reopen it, it picks up where you left off. Saves stay on the device and browser where you played and don't sync between devices.

## Ways to make it faster

1. Small map, 20–28 nations, 2–3 alliances.
2. Blitzkrieg doctrine with Total war: fronts move 60% faster and there's no peaceful build-up.
3. Victory at 75% or 60% instead of 100%. The last stretch is mostly mopping up.
4. Surrender at "40% left", so beaten nations give up sooner.
5. Play at 4× or 8× and pause (space bar) only to give orders. Keys 1–4 set the speed.
6. Leave auto-command on and only direct the main attack. Turn on autopilot to fast-forward.
7. Turn off "pause on major events" so pop-ups don't interrupt play. Events still go to the Log.
8. Put 60–70% of the budget into Military once you're at war, and send several members against one weak neighbor at a time.
