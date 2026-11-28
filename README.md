# Tire Data Tracking

https://github.com/TheMohawk13/Tire-Data-Tracker

Currently on V1.1 Beta

Everything the Tire Set Tracker does (dry and wet allocation, sessions, laps, saved events), plus a **Runs** tab for recording each run's pressures and temperatures, a garage prep section for durometer readings on each tire set, and buttons to send a run or a whole session to the engineer.

Created by Ryne Hoover Transportation.

This is a separate project from Tire Set Tracker. It has its own repository, its own address and its own saved data, so the two never mix.

## Put it on your phone

1. Open the link in Safari (iPhone) or Chrome (Android) and let it finish loading.
2. iPhone: tap **Share**, then **Add to Home Screen**. Android: browser menu, then **Install app** or **Add to Home Screen**.

The icon has a blue accent so you can tell it apart from Tire Set Tracker.

## How to use it

**Tire sets tab** works like Tire Set Tracker: create an event, pick IMSA Standard (5 dry, 3 wet), IMSA Endurance (7 dry, 5 wet), SRO (6 dry, unlimited wet) or Test (no limit), and add your sets. Laps and the allocation counters come from the runs you record on the Runs tab.

**SRO events** allow 6 dry sets and unlimited wet sets. If you are in the bronze test at that event, tick **Bronze test at this event** to allow a 7th dry set. Wet sets have no limit, so the wet counter just counts the sets you have used. The tick is saved with the event.

**Runs tab** follows how a session actually goes:

1. **Send out.** Choose the tire set and the session, enter the cold pressures for LF, RF, LR and RR (optional), and tap **Send out**. If you took them, also enter the **Ambient temp** (for example the garage air temperature when you set the base pressures) and the **Track temp**. Both boxes are optional, and each is one value per run. The run appears under **On track** as, for example, "Practice 2 · Run 3". The runs are numbered automatically within each session.
2. **Bring in.** When the car comes in, tap **Bring in** on that run and enter the laps, the hot pressures and the tire temperatures (inside, middle, outer) for all four tires, plus the **Ambient temp** and **Track temp** if you didn't already enter them at Send out (a value entered here replaces one entered at Send out). Fill in only what you measured. Tap **Save run**.
3. The pressure you set after the engineers' changes goes in as the cold pressure of the next run. When you pick a tire set, the screen shows the last hot pressures recorded on it for reference.

Finished runs are listed under their session as a table with the four tires in columns, including the pressure change and the inside minus outer temperature difference. Under the table, the run's ambient and track temperatures show if you entered them.

**No units.** The app has no unit labels or unit settings. Type your numbers in whatever your team uses (psi, kPa or bar, °F or °C). Nothing is converted, so what you type is what the engineer sees.

**Pressures keep what you typed and always show a decimal.** Type 27 and it becomes 27.0 when you leave the box. Type 1.80 and it stays 1.80. Tables and messages show the same numbers (27.0, 31.6, 1.80). The pressure change uses as many decimals as the larger of the cold and hot readings, with at least one, so 1.80 to 2.05 gives +0.25 and 27.0 to 31.2 gives +4.2.

**Sending to the engineer.**

- **Send a run.** As soon as you tap **Save run**, a "Run saved" bar appears with a **Send run** button. Every finished run in the list also has its own **Send** button, so you can send it later or send it again.
- **Send a session report.** Each session has a **Send session report** button. It sends every finished run in that session, the laps per tire set, and the garage durometer readings of the sets used.
- **Choose where it goes.** On a phone, the share sheet opens, where you pick WhatsApp, Messages or any other app. If the share sheet isn't available, a window shows the text with **WhatsApp**, **Text message** and **Copy** buttons. You can edit the text there before you send it.
- **From a paper sheet.** Enter the run from the paper, then send it the same way.

The message is plain text, for example:

```
Road America (06/12/2027)
Practice 2, Run 3 - Set D3 (Dry), 8 laps
Cold pressure: LF 27.0 · RF 27.0 · LR 26.0 · RR 26.0
Hot pressure: LF 31.2 · RF 31.6 · LR 29.8 · RR 30.1
Pressure change: LF +4.2 · RF +4.6 · LR +3.8 · RR +4.1
Ambient temp: 68
Track temp: 91
Temp in/mid/out:
LF 188/182/174 (in-out +14)
```

**Durometer (garage prep)** is recorded once per tire set, not per run. On the Tire sets tab, scroll to **Durometer (garage prep)**, choose the set, and enter the inside, middle and outer readings for LF, RF, LR and RR as you prep the tires before first use. Saving again for the same set replaces the earlier readings. The readings show on that set's card.

**Edit sessions.** Under **Start a run**, open **Edit sessions** to add sessions (for example "Practice 5" or "Race 2") or remove ones you don't need. A session that already has runs can't be removed. New events start with a default list that depends on the type (IMSA Standard, IMSA Endurance, SRO or Test), and you can change it.

## Fixing mistakes

- **Discard a run that is still on track:** tap **Discard**, then tap it again to confirm.
- **Remove a finished run:** tap **Remove** next to it, on the Runs tab or on the tire set's card.
- **Delete a set or an event:** tap the delete button, then tap it again to confirm.
- **Skip the opening screen:** tap anywhere on it.

## Where your data lives

Everything is saved on **your own device only**. People you share the link with start with a blank copy. Clearing your browser's website data erases it, and a different phone or browser will not have your events.

---

© 2026 Ryne Hoover Transportation. All rights reserved. Copying, modifying, redistributing or reselling this code requires written permission.
