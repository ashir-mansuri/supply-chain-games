# Supply Chain Games

Three free classroom games for supply chain and operations management. Students play in teams, each on their own phone or laptop, in a classroom or an online class. They can also play solo. Nothing to install.

**Play:** https://ashir-mansuri.github.io/supply-chain-games/

| Game | Play time | What students learn |
| --- | --- | --- |
| **Supplier Showdown** | About 30 minutes | Supplier selection, total cost of ownership, dual sourcing, buffer stock, supply risk |
| **Warehouse Rush** | About 20 minutes | Pareto principle, ABC analysis, slotting, pick routes, batch picking, picking productivity |
| **Coffee Chain** | About 25 minutes | Bullwhip effect, lead times, information sharing, stock versus backlog costs (modelled on the beer game) |

---

## How to play

### Step 1: Get into a game

There are two ways to play. Choose one on the game's start page.

#### Option A: Online with your team (each player on their own device)

Use this when your teacher has created a class. You need the **class code** and your **team PIN** from your teacher.

1. Open the game link your teacher shares (Supplier Showdown, Warehouse Rush or Coffee Chain).
2. In the **Join your team** box, type the class code and tap **Find my class**.
3. Choose your team from the list, type the 4-digit team PIN and your first name, then tap **Join team**.
4. Your teammates do the same on their own phones or laptops. The dark **Online now** bar at the top shows who has joined.
5. If you refresh or close the page, open the game again and tap **Continue with [your team]**.

Tips:
- Don't use a private or incognito window. The game remembers your team in the browser so you can rejoin.
- In an online class on Google Meet or Zoom, sit in your team's breakout room so you can talk while you play.

#### Option B: Practise on one device (team round one screen, or solo)

No class code or setup needed.

1. In the **Practise on one device** box, type a team name. To play alone, type your own name.
2. Keep the game code shown, or type the code your teacher gives you. The same code gives the same events, so results can be compared.
3. Tap **Start practice game**.
4. Supplier Showdown and Coffee Chain save your progress on the device. If you leave, tap **Continue** on the start page to carry on.

In Coffee Chain this box is called **Play solo or on one device**. There you choose to play one stage against the computer, or all four stages on one screen.

---

### Supplier Showdown

**Your job:** You run purchasing at Sabar Scooters, an electric scooter maker in Sanand. Every scooter needs four parts: a **battery pack**, a **hub motor**, a **controller chip** and a **tyre set**. Each part can come from four suppliers: **Shenzhen** (China), **Hanoi** (Vietnam), **Pune** (India) and **Stuttgart** (Germany). The game runs for 8 months, April to November.

**Goal:** Finish November with the highest total profit.

**Where you start:** The previous manager bought everything from Shenzhen because it was cheapest.

#### Each month

1. **Read the plan screen.**
   - *Dealers expect to order:* the forecast number of scooters. Actual orders can be a few percent higher or lower.
   - *News desk:* warnings about this month, problems still going on, price or duty changes, and late shipments arriving.
   - *In stock:* how many of each part are left in your store.

2. **Split each part's order between suppliers.**
   - Each supplier row shows the **quoted price**, the **landed cost** (price plus import duty and freight), the **lead time**, the **defect rate** and the **risk**.
   - Tap **+** or **−** to move the share by 10% at a time. Each part must total **100%**.
   - Pune can make at most **60%** of your battery packs and **40%** of your chips.
   - A supplier marked **New supplier** costs **₹5 lakh** to approve and ships only **half** your order in its first month.
   - The line under each part shows how many you will order: forecast + buffer − stock.

3. **Choose your buffer stock:** None, 1 week, 2 weeks or 4 weeks of forecast demand. Buffer stock protects you from shortages but costs 2% of its value every month.

4. **Check the bar at the bottom.** It shows your parts cost per scooter (quoted and landed) and any new-supplier fees this month.

5. **Place your orders.**
   - *Practice:* tap **Place orders for [month]**.
   - *Online:* each member manages some of the parts. Your parts say **You manage this**; a teammate's say **[name] manages this**. Set your parts, then tap **I'm ready**. To change something after that, tap **Change my choices**. Anyone can change the buffer stock, but that asks everyone to tap Ready again. The month plays when every member online is ready.

6. **Read the news card.** Something happens every month: a fire, a flood, a strike, a tariff, a chip shortage, a quality problem, the festive rush, or a quiet month. Tap **See [month] results**.

7. **Read your results.**
   - Dealers ordered, scooters built, lost sales and profit for the month.
   - The parts table shows, for each part: ordered, arrived, late (arriving next month), not shipped, faulty and left in store.
   - A scooter needs all four parts, so **the scarcest part limits how many you build**. The part that ran out is marked in red.
   - The profit and loss table shows where the money went.

8. Tap **Plan [next month]** and repeat.

#### At the end

After November, tap **See the final report**. It shows:
- Total profit, orders delivered, parts cost per scooter, suppliers per part, and shipping carbon per scooter.
- A chart of your profit month by month against three strategies the computer played with the same news: **Cheapest only**, **Local first**, and **Two suppliers + buffer**.
- The news for each month and your hardest month.
- Questions to talk over with your team and class.

#### Tips
- Compare **landed cost**, not just quoted price.
- Read the news desk every month. Some problems come with a warning.
- A new supplier needs a month to reach full deliveries. Think ahead.

---

### Warehouse Rush

**Your job:** You pick customer orders at a fulfilment centre near Ahmedabad during the festive sale.

**Goal:** Pick the same six customer orders faster in each round. Your score is **lines picked per hour**.

#### Reading the map
- Four aisles, **A** to **D**. **Dispatch** is at the bottom; every trip starts and ends there.
- Each shelf shows a product's SKU number. A slot name like **B3L** means aisle B, bay 3 counting from the dispatch end, left side.
- **Yellow** shelves are on your pick list. **Green** shelves are picked.
- The **dark circle with a yellow ring** is the picker. The **blue line** is the path walked.
- The picker can only walk along aisles and the cross-aisles at the front and back.

#### How time is counted
- Each trip takes **20 seconds** to set up.
- Each line picked takes **10 seconds**.
- Walking speed is **1.2 metres per second**.

#### Round 1: Day one (products scattered at random)
1. Tap **Start round 1**.
2. Read the pick list on the right: SKU, product name and slot.
3. Tap the yellow shelves **in the order you want to visit them**. The picker walks your route.
4. After the last shelf, the picker returns to dispatch. The **Trip done** panel shows the metres you walked, the shortest possible route, your route efficiency and the picker time. Tap **Show the shortest route** to see the best route drawn in red dashes.
5. Tap **Next order**. There are 6 orders in the round.
6. The round results show lines per hour, metres walked, picker time and route efficiency.

**Online:** team members take turns as the picker, one trip each.
- **Your turn to pick** means you tap the shelves.
- **[name] is picking this trip** means you watch the picker move live and help plan the route out loud.
- If the picker leaves, tap **Take over picking**.

#### Round 2: ABC slotting (move the fast sellers)
1. Tap **Next: study the sales data and re-slot the warehouse**.
2. Study the chart of last month's sales.
   - **A** = the top 7 products, which make about 67% of all picks.
   - **B** = the next 11 products, about 19% of picks.
   - **C** = the last 18 products, about 14% of picks.
3. Re-slot the warehouse. Tap a shelf to pick it up, then tap another slot; the two swap places.
   - **Dark blue** shelves are A products. **Light blue** shelves are B products.
   - The **fast-pick zone** is the 8 slots nearest dispatch, marked with gold dashed outlines.
   - Move all 7 A products into the fast-pick zone, with B products close behind. Watch **Walk per pick now** drop.
   - **Do it for me** shows the best layout. **Undo all moves** goes back to the day-one layout.
   - Online, every team member can move shelves, and moves show up on every screen.
4. Tap **Pick with this layout** and pick the same six orders again.

#### Round 3: Batch picking (two orders per trip)
1. Tap **Next: batch picking**, then **Start round 3**.
2. Each trip now has two orders, one in **Tote 1** and one in **Tote 2**. You make 3 trips instead of 6.
3. Pick them the same way as before.

#### At the end
Tap **See the final results**. You see how much faster you got, your lines per hour in each round, metres walked compared with the shortest possible, and questions to talk over.

---

### Coffee Chain

**Your job:** You run one stage of a coffee supply chain. Roasted coffee travels down the chain, and orders travel up it:

**Coffee estates → Coffee roaster (Bengaluru) → Wholesaler (Ahmedabad) → Distributor (Vadodara) → Café (Vadodara) → Customers**

**Goal:** The lowest **total cost for the whole team** (all four stages added together) by the end of the game.

**Costs, for every stage, every week:**
- **₹10** for each bag in stock.
- **₹20** for each bag you owe the stage below you (backlog).

**Delays:**
- An order takes **1 week** to reach the stage above you.
- Coffee takes **2 weeks** to travel down one step.

#### Each week
1. **Read your stage's screen.** It shows:
   - *Bags in stock*, *Owed to* the stage below you, and *Your cost so far*.
   - *Arrived* this week from the stage above you.
   - *New order* this week from the stage below you. At the café, this is what customers want.
   - *Sent* this week. If you didn't have enough, the rest is added to what you owe and goes out when stock arrives.
   - *On the way to you:* bags arriving next week and in two weeks, and how much the stage above still owes you.
   - A table of your last five weeks.
2. **Decide your order.** Type how many bags to order from the stage above, or use **−10** and **+10**.
3. **Send it.**
   - *Solo:* tap **Send my order**. The computer orders for the other three stages.
   - *All four stages on one device:* set all four orders, then tap **Send all four orders**.
   - *Online:* tap **Send order** for your stage. You can tap **Update order** to change it until the week moves on. The week moves on when all four stages have ordered. The dark bar at the top shows who has ordered.
4. The next week starts automatically. The game doesn't say how many weeks are left.

**Online:** each team member runs one stage and sees **only their own stage**, just like a real supply chain. With fewer than four members, some members run two stages. Don't tell other stages your numbers; that's the challenge.

**Information sharing:** if your teacher switches this on (or you tick it in solo play), every stage also sees the café's customer sales each week.

#### At the end
The final report shows:
- Your team's total cost, and how it compares with three computer teams: **Typical players**, **Pass the order on** and **Plan from customer sales**.
- **The secret:** what customers really bought each week.
- A chart of every stage's orders, week by week, against real customer sales. This shows the bullwhip effect.
- A chart of each stage's stock, and what it owed.
- Each stage's cost, its order swing, its biggest order and the number of weeks it owed bags.
- Questions to talk over.

#### Tips
- Before you order, add up what is already on the way to you.
- A big order from the stage below doesn't always mean customers are buying more.

---

### For teachers

#### Running an online class
1. Open **teacher.html** (the **Teacher dashboard** link on the home page). The first time, set up Firebase; see below.
2. Under **Create a class**, enter a class name, choose the game and the number of teams, and set a teacher password. For Coffee Chain, you can also tick **information sharing**, so every stage sees the café's customer sales. Tap **Create class**.
3. Share the **class code** and the game link with the class. Tap **Show PINs** and give each team only its own PIN.
4. While teams play, the dashboard shows who is online, how far each team has got and live scores. **Projector view** shows only the class code and the ranking.
5. If a team gets stuck, use **Restart game** for that team. Use **Add a team** or **Rename a team** as needed.
6. After class, tap **Delete this class** to remove students' names and results.

To open the same class on another device, use **Open a class from another device** with the class code and your teacher password.

#### Practice games and solo play
- Teams or individual students choose **Practise on one device** on the game's start page.
- To compare results, open **Open the practice scoreboard** on your own device and type in each team's final result.
- For an individual graded activity with live scores, create an online class with one team per student and rename each team to the student's name.

#### Trying it out
On the teacher dashboard, choose **Try demo mode**. Online play then works inside your own browser only. Create a class, then open a game in two or three tabs and join the same team to see how teammates play together.

The **teacher's guide** (`teacher-guide.html`) has 60-minute lesson plans, the rules behind each game, debrief answer points and follow-up assignments.

---

## Files

| File | What it is |
| --- | --- |
| `index.html` | Home page |
| `supplier-showdown.html` | Supplier Showdown game |
| `warehouse-rush.html` | Warehouse Rush game |
| `coffee-chain.html` | Coffee Chain game |
| `teacher.html` | Teacher dashboard |
| `teacher-guide.html` | Teacher's guide |
| `firebase-config.js` | Online play settings (paste your Firebase config here) |

There are no folders to upload.
