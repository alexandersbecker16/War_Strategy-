# Iron Meridian

A browser strategy war game in one file (`index.html`). There's nothing to install. It runs on Windows 11 (Edge, Chrome or Firefox) and on phones and tablets (Safari or Chrome).

## How to run

- **Windows 11:** download `index.html` and double-click it. It opens in your default browser.
- **Phone or tablet:** open the hosted link, or put `index.html` on the device and open it in the browser. The map supports tap, drag and pinch-zoom.
- **Hosting it yourself (optional):** turn on GitHub Pages for this repo (Settings → Pages → deploy from branch). The game is then at `https://<user>.github.io/War_Strategy-/`.

## What the game does

- **Real world map.** The map is the actual world: coastlines from Natural Earth (public domain) in a Miller projection, from 78°N to 56°S. Every new game carves it into 20–48 random nations, each with a real city as its capital (Paris, Tokyo, Lagos, São Paulo and so on). 226 real cities appear on the map, and cities are worth several times a normal street. Small islands belong to the nearest nation. Map sizes go up to Huge (400×181 squares) for an HD view. Every square on the map is one street block with its own street and district name. Hover over a square, or tap it, to see them. Territory changes hands one street at a time.
- **Modern demographic blocs.** Each nation belongs to the bloc where its capital actually sits: Atlantic, East Asian, Eurasian Steppe, Gulf & Levant, South Asian, Latin, Sub-Saharan and Austro-Pacific. The bloc sets its growth rate, its foreign-policy temperament and its names.
- **Equal start.** Every nation starts with exactly the same population, income (counting its cities), science and combat power. Every alliance gets the same number of nations: the nation count is rounded to a multiple of the alliance count, e.g. 20 nations in 3 alliances becomes 21. So every alliance starts equal too, and alliances are grouped to hold about the same land. Nations still differ in land (geography), bloc growth rate, foreign policy and position on the map, so strategy decides the war. Wealth gaps appear as the war goes on.
- **You get one nation in one alliance** and command that whole alliance. The computer runs every other alliance. It sets budgets, gangs up on weak targets, declares war when it has the edge and offers peace when it's losing.
- **Smarter computer alliances at war.** They turn stored science into troops while at war, flat out unless clearly winning, and immediately on any front that's about to break. In head-to-head tests this beat the old AI in about 3 games out of 4. They also go after capitals within reach, finish off nations close to surrender and hit back at whoever is attacking them. Before a likely war with a stronger neighbor they move their budget to a war footing. They pile onto a strong alliance that's already fighting elsewhere and gang up on any alliance that holds more than 40% of the world. They avoid opening a second front while losing, and make peace on their quietest front when fighting several wars at once.
- **Anyone can declare war on anyone, even their own allies.** You can declare war on any alliance or on a member of your own. Computer nations can now do it too: a strong nation next to a much weaker ally may turn on it to grab its land. This is more likely for Opportunists, in Anarchy, and once an alliance has no outside enemies left. Your home nation never does this on its own, but your other members can.
- **Your nation's economy:** pick Mixed, Free market, State-planned, War economy, Knowledge economy or Resource exporter at setup, and switch in the Command tab (once every 6 months). It stacks on top of the world economic policy.
- **Weapons program:** turns stored science into troops, automatically by default. At peace your science is saved, so every troop fights better. At war it's converted at full rate unless you're clearly winning, and any member about to be overrun converts 15% at once. Rich nations get up to 3× more troops per point of science, so for them a heavy Science budget is also the fastest route to a big army. Move the Convert slider in Command to run it by hand. Computer alliances use the same rules.
- **Budget balance by population and wealth.** Military money buys and maintains troops (troops cost upkeep), science makes every troop stronger, and the economy grows the income that funds both. Troops are cheaper where income per person is low, and research has a fixed price, so rich nations progress fastest. So the best mix depends on the nation: poor, populous nations should mass troops and rich nations should buy science. *Tailor each nation's budget* (on by default) does this automatically. The Military / Economy / Science sliders always add up to 100%, with one-tap presets, and moving them switches tailoring off. Any of your nations can also get its own budget in Intel. The top of the Intel tab ranks every nation by total wealth (a year of income plus its economy's value), with its share of world wealth.
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
