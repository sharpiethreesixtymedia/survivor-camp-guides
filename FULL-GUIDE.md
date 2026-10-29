# Survivor Camp: Full Guide

*Last updated Oct 29, 2026. Matches stream overlay v0.22.0 and SharpieBot v0.29.1. Shop launch: **Fri Oct 30, 2026**. The shorter version is the Quick Start.*

Hey, welcome to camp! This guide explains everything from scratch, so you don't need to know anything going in. If you get stuck, jump to the FAQ at the bottom.

---

## Contents
1. What Survivor Camp is
2. Linking your account (step by step)
3. Stream chat commands (the `!` ones)
4. Discord commands (the `/` ones)
5. `!` vs `/`: which one goes where
6. Your backpack
7. Scrap, ranks and the shop
8. Customizing your survivor's look
9. Guests vs linked survivors
10. Other stuff worth knowing
11. Coming soon / planned
12. FAQ and troubleshooting
13. For mods: admin commands

---

## 1. What Survivor Camp is

Survivor Camp is a little pixel-art game that lives at the bottom of Sharpie360's stream.

- You type `!camp join` in the stream chat, and your own tiny survivor walks onto the screen.
- Your survivor wanders around camp. You can make it dance or wave.
- If your survivor is holding a tool, it uses it now and then on its own: chops a stump with an ax, fishes in a puddle, shoots an arrow, takes a drink, and so on.
- Your name floats above your survivor, with a small icon for the platform you're chatting from (YouTube, Kick, Rumble, Twitch, or a gray bubble for anything else).
- **Jest**, Sharpie360's black cat and the channel mascot, roams camp too. She has a purple name tag. She's not a viewer, so she never takes your spot. Sometimes she walks over and sits next to a survivor.

It works on every platform Sharpie360 streams to: YouTube, Rumble, Twitch, Kick, and others. All the chats are gathered into one feed, so it doesn't matter which one you watch on.

**Survivor Camp is tied to the SharpieBot Discord server.** You can play as a guest with no Discord at all. But if you **link** your stream chat name to your Discord account, you get:
- a **gold name** (guests are white),
- a **longer stay** in camp,
- your **own look**: skin tone, hair color, hairstyle, body type (man or woman) and mood,
- your **own outfit**, picked in your Discord backpack,
- a **100 Scrap linking bonus** and, if you link before the shop opens, a spot as a **Founding Survivor** with free starter gear (see section 7),
- the ability to move your survivor **from Discord** with `/camp join`, `/camp dance` and so on.

---

## 2. Linking your account (step by step)

Linking connects your stream chat name (like your YouTube name) to your Discord account. **You never share a password, login or token.** All you use is a short one-time code.

### What you need
- To be a member of Sharpie360's Discord server.
- A stream that's live right now, with you in its chat.

### Steps
1. **In Discord, get your code.** In any channel where you can use bot commands, type `/camp link` and press Enter.
   - SharpieBot answers privately (only you can see it) with a **6-character code** and the full command ready to copy, like `!camp link AB12CD`.
   - The code works **once**, for **10 minutes**. If you run `/camp link` again, the old code stops working and you get a new one.
2. **Copy the whole command** from the code box: `!camp link YOURCODE`.
3. **Paste it into the STREAM chat**, on YouTube, Twitch, Kick, Rumble or wherever you're watching, while Sharpie360 is live.
   - **Not in Discord!** If you paste it in Discord by mistake, SharpieBot **deletes your message** to keep your code safe and tells you it belongs in stream chat. Your code still works, so just paste it in stream chat. (If the bot couldn't delete it, it cancels that code instead, and you'll need a fresh one from `/camp link`.)
4. **Check that it worked.** You'll see:
   - A reply in stream chat: `Linked! Welcome to camp, YOURNAME.`
   - A DM from SharpieBot confirming the link, with "Not you? Run /camp unlink" in case it wasn't you.
   - If your survivor is already on screen, its name turns **gold** right away.
5. **Your linking bonus:** linking earns **100 Scrap**, once. Before the shop opens it waits for you (see `/camp wallet`), and it's paid on launch day. Unlinking and linking again never pays twice.
6. **Do it again for each platform you use.** Watch on both YouTube and Kick? Link each one with its own new code. You still get **one survivor**. When you type from the other platform, your survivor just switches its platform icon.

### Checking and removing links
- `/camp linkedplatforms` in Discord shows which platforms you've linked.
- `/camp unlink` in Discord removes all your links. To remove just one, pick a platform.
- `!camp unlink` in stream chat unlinks **only the name that typed it**, on that platform. Your other platforms stay linked.

### Linking troubleshooting
| What you see | What it means / what to do |
|---|---|
| `that code didn't work (wrong or expired)` | Codes last 10 minutes and work once. Run `/camp link` again for a new one. |
| `that chat name is already linked to another Discord account` | That stream name belongs to someone else's link. They need to unlink it first (`/camp unlink`, or `!camp unlink` from that name). |
| `too many tries. Wait a few minutes` | Too many wrong codes. Wait about 10 minutes and use a fresh code. |
| `linking is offline right now` | The bot or the camp is having a moment. Try again later in the stream. |
| `type !camp link CODE` | You forgot the code after `!camp link`. |
| No reply at all | Chat replies can be switched off or slowed down. Check whether you got the DM in Discord, or run `/camp linkedplatforms`. |
| SharpieBot deleted my message in Discord | You pasted the code in Discord. Paste it in **stream** chat instead. |

**Safety:** Nobody from the channel will ever ask for your password, login or any account token. If someone does, it's not us. Don't post your link code anywhere except the live stream chat, and use it right away.

---

## 3. Stream chat commands (the `!` ones)

Type these in the **live stream chat** on any platform (YouTube, Rumble, Twitch, Kick, and others). Every command is `!camp`, a space, then one word. They aren't case-sensitive, so `!CAMP Dance` works too.

| Command | What it does |
|---|---|
| `!camp` | A quick welcome message with the basics. |
| `!camp help` | Lists the commands in one line. |
| `!camp join` | Your survivor walks into camp (if there's room). |
| `!camp leave` | Your survivor walks off screen. |
| `!camp dance` | Your survivor hops and spins for 3 seconds (you have to be in camp). |
| `!camp wave` | Your survivor waves for 3 seconds (you have to be in camp). |
| `!camp link CODE` | Links this chat name to Discord, using the code from `/camp link`. |
| `!camp unlink` | Unlinks this chat name (this platform only). You're a guest again. |
| `!camp scrap WORD` | Claims a stream code shown on stream (linked only, once per code). |

Good to know:
- **Older forms still work:** `!joincamp`, `!leavecamp`, `!dance`, `!wave`, `!linksurvivor CODE`. Typing without the space works too: `!campjoin`, `!campdance`, `!camphelp` and so on. `/camp legacycmds` in Discord lists them all.
- **Plain `!join` and `!link` are NOT camp commands.** `!join` is used for giveaways.
- An unknown word like `!camp xyz` is ignored quietly, so chat stays clean.
- `!camp` has to be at the **start** of your message. `hey !camp join` won't count.
- Emotes have a short cooldown (about 5 seconds per person), so spamming dance won't do anything.
- Welcome and help replies are limited (about one a minute for the whole chat, and once every 10 minutes per person), so you might not always get a reply. That's normal.

---

## 4. Discord commands (the `/` ones)

Type these in **Sharpie360's Discord server**. Type `/camp` and Discord shows a menu of options. **Every reply is private**: only you can see it.

### Account and info
| Command | What it does |
|---|---|
| `/camp link` | Gets your one-time code for linking (see section 2). |
| `/camp unlink [platform]` | Removes one platform's link, or all of them if you leave it empty. |
| `/camp linkedplatforms` | Shows which platforms you've linked. |
| `/camp wallet` | Your Scrap, XP and rank (see section 7). |
| `/camp daily` | Claim your daily Scrap (starts when the shop opens). |
| `/camp help` | Lists the stream chat commands and what linking gives you. |
| `/camp legacycmds` | Lists the older chat commands that still work. |

### Your survivor's style
| Command | What it does |
|---|---|
| `/camp look` | Pick a skin tone, hair color and hairstyle. Pick `random: True` to roll a new look (see section 8). |
| `/camp body` | Pick your survivor's body type: Man or Woman. |
| `/camp mood` | Pick your survivor's mood: Happy or Content (Grumpy is coming soon). |
| `/camp backpack` | Try on your outfit and tool (see section 6). Open to everyone now. |
| `/camp shop` | Browse and buy items (see section 7). **Not open yet.** |

### Moving your survivor from Discord (linked members only, while the stream is on)
| Command | Same as | What it does |
|---|---|---|
| `/camp join` | `!camp join` | Your survivor walks into camp. |
| `/camp leave` | `!camp leave` | Your survivor walks off. |
| `/camp dance` | `!camp dance` | Dance for 3 seconds. |
| `/camp wave` | `!camp wave` | Wave for 3 seconds. |

- You'll get a short private answer within a few seconds, like "💃 Your survivor is dancing!" or "Camp is full right now…".
- If the stream overlay isn't running, you'll see "🏕️ Camp isn't open right now… Try again when Sharpie360 is live!"
- Not linked yet? It tells you to run `/camp link` first.
- You can send one camp command every 3 seconds.
- **Linking itself can't be done from Discord.** The code always goes in stream chat. That's on purpose, because it proves the stream name is really yours.

---

## 5. `!` vs `/`: which one goes where

This is the part people mix up most, so here's the short version:

- **`!` = stream chat.** Typed as a normal chat message on YouTube, Twitch, Kick, Rumble and so on.
- **`/` = Discord.** Slash commands in Sharpie360's Discord server. Discord pops up a menu when you type `/`.

| Command | Stream chat (`!`) | Discord (`/`) |
|---|---|---|
| Welcome line | `!camp` | (use `/camp help`) |
| Command list | `!camp help` | `/camp help` |
| Join camp | `!camp join` | `/camp join` (linked only) |
| Leave camp | `!camp leave` | `/camp leave` (linked only) |
| Dance | `!camp dance` | `/camp dance` (linked only) |
| Wave | `!camp wave` | `/camp wave` (linked only) |
| **Get a link code** | no | **`/camp link`** |
| **Use the link code** | **`!camp link CODE`** | no (the bot deletes it to protect you) |
| Unlink | `!camp unlink` (this name only) | `/camp unlink` (one platform or all) |
| See your links | no | `/camp linkedplatforms` |
| Skin, hair and hairstyle | no | `/camp look` |
| Body type and mood | no | `/camp body`, `/camp mood` |
| Your Scrap, XP and rank | no | `/camp wallet` |
| Daily Scrap | no | `/camp daily` |
| Backpack (outfits) | no | `/camp backpack` |
| Shop (not open yet) | no | `/camp shop` |
| Old commands list | no | `/camp legacycmds` |

**What happens if you use the wrong one:**
- `!camp join` (or similar) typed in **Discord**: SharpieBot gives you a gentle tip to use the slash version, like `/camp join`. The tip disappears after a minute.
- `!camp link CODE` typed in **Discord**: the bot deletes it to keep your code safe and tells you to paste it in stream chat.
- `/camp ...` typed in **stream chat**: nothing happens. Stream chat doesn't know slash commands.

Memory trick: **the code is born in Discord (`/`) and used in stream chat (`!`).**

---

## 6. Your backpack

The backpack is where you **try on and wear** your Survivor Camp items. Open it in Discord with `/camp backpack`. It's open to everyone, even though the shop isn't yet.

### What you see
- **A picture on top** of your actual survivor (your body type, hairstyle, hair color, skin tone, mood and outfit), front and side view. A green "Current Outfit" label means what you're wearing now. A blurple "Trying On: X" label means you're trying something on, with a small "equip to keep it" hint under it.
- **A card below it** with numbered item tiles, 15 per page (5 per row).

### The buttons
- **Dropdown:** All Items, Heads, Bodies or Tools. (Founding Survivors also get a **Founder Picks** tab, see section 7.)
- **Three rows of numbers (1-15):** tap a number to **try that item on**. The picture updates.
- **Bottom row:** ◀ Back / **Equip** / **Unequip All** / Next ▶ / Close.

### How to dress up
1. Run `/camp backpack`.
2. Pick a type in the dropdown (or stay on All Items).
3. Tap a number to try an item on.
4. Like it? Press **Equip** to keep it. On an item you already wear, the button reads **Unequip** instead.
5. You can wear **one head, one body and one tool** at a time.
6. **Unequip All** takes everything off, and you show as the plain survivor.

**Colors:** green = equipped, blurple = trying on, gray = in your backpack, red = Unequip All.

### Does it show on stream?
Yes, if you're linked. Your survivor picks up the change **within about a minute, even if it's already in camp.** No need to leave and rejoin.

### Pre-launch preview (right now)
Until the shop opens, your backpack shows **every item** so you can try them all on. A line at the bottom says it's a pre-launch preview:
- **Linked:** you'll pick **2 hats, 2 outfits and 2 tools** to keep when the shop opens.
- **Not linked:** link your account before then to keep 2 hats, 2 outfits and 2 tools for good.

When the shop opens (target **Fri Oct 30**), the backpack only shows items you **own**. New survivors start with no items. You get items by buying them in `/camp shop`, or as a Founding Survivor (section 7). Trying on is free, and looks (skin, hair, hairstyle, body, mood) are always free.

Only you can press your backpack's buttons, and they stop working after 10 minutes. Just run `/camp backpack` again.

---

## 7. Scrap, ranks and the shop

### The shop is not open yet
The shop is **private for now** and isn't open to members. The target launch day is **Fri Oct 30, 2026**. Everything in this section describes how it will work. You can already **link your account** and **try items on** in your backpack (section 6).

### Scrap and XP
- **Scrap** is Survivor Camp's currency. You spend it in the shop. It has no real-money value.
- Every Scrap you earn is also **1 XP**. XP is a lifetime total and never goes down. It sets your **rank**.
- Everyone in the Discord server has a Scrap balance and XP, linked or not, but you need to link to use the shop's items on stream.

### Checking your Scrap: `/camp wallet`
Private reply with your Scrap, XP, rank and a bar showing progress to the next rank. If you get a gift, it shows at the top.
- **Before launch:** your Scrap shows 0, but XP and rank show what you've really earned since Oct 16. A line reads **"Waiting for Launch: N Scrap"**. That's what you'll start with on launch day (what you earned plus your 100 linking bonus, if you're linked).

### How you earn Scrap (starts at launch)
| Way | How much |
|---|---|
| Linking bonus | **100** once, for linking a stream chat name |
| `/camp daily` | **15** Scrap, **+1** for each day in a row, up to **25**. Once a day, resets at midnight Chicago time. If you miss a day the streak starts over. |
| Chatting in Discord | 2 Scrap per message, at most one counted a minute, up to 120 a day |
| Voice chat | 1 Scrap every 5 minutes in a voice channel with 2 or more people, up to 60 a day |
| Watching the stream (linked) | 1 Scrap per 5 active minutes, up to 36 a day |
| Stream codes (linked) | Type `!camp scrap WORD` when a code shows on stream. Once per code, up to 100 a day |

`/camp daily` only works after launch. Before then it just tells you when it starts.
Everything you earn since **Oct 16** carries over on launch day, so you aren't starting from zero.

### What To Expect
We ran a 14-day blind test counting what people would have earned. Real daily pace:

| Kind Of Member | Scrap A Day |
|---|---|
| Most active | about 28-43 |
| Regulars | about 7-13 |
| Casual drop-ins | about 1-4 |

So a regular can grab a cheap starter item in about a week, and the most active folks can pick up a couple a week. Ranks are a long climb on purpose: Apex is a big deal.

### Ranks
| Rank | XP needed |
|---|---|
| Castaway | 0 |
| Scavenger | 60 |
| Forager | 200 |
| Nomad | 500 |
| Pathfinder | 1,100 |
| Ranger | 2,000 |
| Survivalist | 3,750 |
| Legend | 6,250 |
| Paragon | 10,000 |
| Apex | 15,000 |

### Founding Survivors
Everyone who **links before the shop opens** is a **Founding Survivor**. You get:
- a gold **Founding Survivor** tag on your backpack picture,
- a one-time, free **Founder Picks** tab in `/camp backpack`: choose up to **2 heads, 2 outfits and 2 tools** from the starter items (except Vollie, a premium item you buy with Scrap), then press **Lock In** and confirm **Yes, Lock In Forever**. Your picks are yours for good and can't be changed.

The Founder Picks tab appears when the shop opens.

### How to browse, preview and buy (once the shop is open)
1. Run `/camp shop`.
2. **The top picture** shows the selected item big on the left. On the right are its name, type, set, price, and either "You'd have X left", "You need X more" or OWNED.
3. **The card below** is a grid of 15 numbered tiles per page, in order: Heads, Bodies, Tools, then Specials.
4. **Dropdown:** All, Heads, Bodies, Tools, Specials or Sets.
5. **Number buttons (1-5, 6-10, 11-15):** pick an item. These line up with the tiles.
6. **Preview:** switches the top picture between the **item by itself** and **your survivor wearing it** (with your skin, hair and current outfit).
7. **Buy:** shows the price. Press it, then confirm with **Yes, buy for N** (or Cancel). The Scrap comes off, and the item is yours. You can't be charged twice, and your balance can't go below zero.
   - The Buy button says **Owned ✓** if you have it, **Need N more** if you can't afford it, or **Coming soon** for things not on sale yet.
8. **◀ Back / Next ▶** change pages. **Close** closes the shop.

**Colors:** green = owned, blurple = selected, gray = everything else. A dimmed tile with a red price means you can't afford it yet.

### The Sets view
Pick **Sets** in the dropdown. There are 5 outfit sets, each a head plus a body:

| Set | Head | Body |
|---|---|---|
| Leaf | Leaf crown | Leaf wrap |
| Beach | Sunhat | Swimsuit |
| Pajamas | Nightcap | Pajamas |
| Hide | Hide cap | Hide tunic |
| Fur | Fur hood | Fur coat |

- Each set shows how many pieces you own (x/2) and what it costs to finish.
- The top picture shows both pieces side by side, or your survivor wearing both.
- Each missing piece has its own **Buy** button. Owned pieces show a green ✓.
- **Pieces are sold separately.** There are no bundle deals; you complete a set one piece at a time.
- 3 sets per page.

### Prices (Scrap)
The starter gear is 22 items at **75 to 300 each** (all 22 together: **2,525**). The priciest is **Vollie** (300), the volleyball with a smiley face; it's a premium item, so it isn't one of the free Founder Picks. New tiers of gear unlock over time, so Scrap you save now still has somewhere to go.

| Heads | | Bodies | | Tools | |
|---|---|---|---|---|---|
| Leaf crown | 75 | Leaf wrap | 90 | Stone knife | 75 |
| Sunhat | 90 | Swimsuit | 100 | Torch | 75 |
| Nightcap | 90 | Pajamas | 100 | Wood spear | 90 |
| Hide cap | 100 | Hide tunic | 110 | Coconut flask | 90 |
| Fur hood | 125 | Fur coat | 150 | Slingshot | 100 |
| | | | | Stone ax | 100 |
| | | | | Stone pickax | 100 |
| | | | | Clay bottle | 100 |
| | | | | Makeshift fishing pole | 125 |
| | | | | Bow with arrow | 150 |
| | | | | Volleyball (red handprint) | 190 |
| | | | | Vollie (volleyball with a face) | 300 |

**Specials (shown as "Coming soon", can't be bought yet):** Hair color unlock 150, WILSON! 190, Campfire 250.

These prices are the same in the stream overlay's item list. They may still get small changes before launch.

### Tools and what they do
Hold one tool at a time. Every so often your survivor uses it:

| Tool | What your survivor does |
|---|---|
| Stone knife | Whittles a stick (shavings fall) |
| Torch | Holds it up, flame flickers |
| Wood spear | Jabs |
| Coconut flask / Clay bottle | Takes a drink |
| Slingshot | Shoots a pebble across the screen |
| Stone ax | Chops a stump |
| Stone pickax | Swings at a rock |
| Makeshift fishing pole | Casts into a puddle |
| Bow with arrow | Shoots an arrow across the screen |
| Volleyball (Wollie) | Just holds him |
| Vollie | Just holds him, like the Volleyball |

---

## 8. Customizing your survivor's look

Everything here is done in Discord. It shows on stream once you're linked.

### Skin tone, hair color and hairstyle: `/camp look`
All looks are **free**.
- **Skin tones (5):** light, default, tan, brown, deep.
- **Hair colors (6):** brown, black, darkBrown (dark brown), blonde, auburn, gray.
- **Hairstyle (`style`):** Default, Short, Buzz, Tied, Messy, Ponytail, Long, Bun, Bob/Fro, Bald. Every style works on both body types. Default is the body's own hair (Short for the man, Ponytail for the woman).
- Example: `/camp look skin:tan hair:auburn style:Bun`. You can change just one of them.
- **Feeling lucky?** `/camp look random:True` rolls a random skin tone, hair color and hairstyle, always different from what you have now, and saves it. (Linked members only.) If you also pick a `style`, that style is kept and only the colors roll.
- You can save a look before linking. It shows up on stream once you link.
- Changes show on stream **within about a minute**, even if your survivor is already in camp.
- `custom_hair` (your own hex color like `#3fa7ff`) is the **Hair Color unlock** in the shop (a Special, coming soon). Until then, it tells you it isn't unlocked.

### Body type: `/camp body`
Pick **Man** or **Woman**. Free. Your skin, hair, mood and outfit stay the same.

### Mood: `/camp mood`
Pick **Happy** (always smiling) or **Content** (the normal face, the default). Free. **Grumpy** is coming soon and says so if you try it.

### Outfits: `/camp backpack`
Pick a head, a body and a tool (section 6). Right now you can try on everything. After the shop opens, you wear what you own.

### Starter outfits
Never touched your backpack? Until the shop opens, you get a **random starter outfit** so not everyone looks the same. It's always the same one for the same name: one body, sometimes its matching hat, and sometimes a simple tool. Once you equip something in your backpack, your choice wins. If you press **Unequip All**, you show as the plain survivor. After launch, new linked survivors start with no items, and guests still get a random starter outfit.

### Guests
Guests always have the default skin tone and brown hair. Link up to use your own look.

---

## 9. Guests vs linked survivors

| | Guest (not linked) | Linked survivor |
|---|---|---|
| Name color | White | **Gold** |
| How long you stay | **3 minutes** from when you joined. Chatting doesn't add time. | **No fixed limit.** You walk off after **10 minutes without chatting** (any chat message counts, not just commands). |
| Look | Default skin and hair, starter outfit | Your `/camp look`, `/camp body`, `/camp mood` and `/camp backpack` picks |
| Several platforms | One survivor per platform | **One survivor** for all your linked platforms |
| Control from Discord | No | Yes (`/camp join`, `leave`, `dance`, `wave`) |
| Scrap bonus and Founder Picks | No | 100 Scrap linking bonus, and Founding Survivor perks if you link before launch |

**Rejoin cooldown (everyone):** after your survivor leaves for any reason (time up, `!camp leave`, or removed by the streamer), you have to wait **5 minutes** before you can `!camp join` again. You'll get a "rejoin cooldown" message if you try sooner. For linked survivors, this covers all your platforms together.

**Other limits:**
- Camp holds **20 survivors** at once. When it's full, you'll be told it's full.
- The streamer can **pause joins**, and then you'll hear the camp is closed for now.
- Typing `!camp join` again while you're in camp just tells you you're already there. It doesn't reset a guest's timer.
- If a guest links while on screen, the linked rules apply from that moment.

*(These are the default numbers. The streamer can change them during a stream.)*

---

## 10. Other stuff worth knowing

- **Jest the cat:** Sharpie360's black polydactyl cat with yellow eyes and big "mitten" paws. She wanders, sits, naps (watch for the little z's), and sometimes sits next to a survivor. Only the streamer controls her, and she has no chat commands yet.
- **Platform icons:** the little logo before your name shows where you last typed from. Linked on several platforms? It switches when you chat from another one.
- **YouTube names** show without the `@`.
- **Privacy:** the camp only knows your **public chat name**. Linking saves your platform, public chat name, a scrambled (one-way) version of your Discord ID, and your look. It never asks for or keeps passwords or tokens. If you leave the Discord server, your link data is wiped. Normal chat messages aren't saved, and link codes are hidden in the logs.
- **Scrap before launch:** since Oct 16 the bot has been quietly counting what you'd earn (chat, voice, stream watch time). It carries over on launch day. Check `/camp wallet` to see your XP and the Scrap waiting for you.
- **Stream down or overlay off:** Discord camp commands say camp isn't open. Your look, backpack and links are all saved, so nothing is lost.

---

## 11. Coming soon / planned

**None of this is built yet.** Details, prices and timing can change.

### Shop launch
- The shop opens on **launch day, target Fri Oct 30, 2026**. Your Scrap carries over, Founding Survivors make their picks, and `/camp daily` starts.

### More ways to earn Scrap
- **Video codes:** a hidden code word in videos, redeemed with a `/camp code` command.
- **YouTube comment points:** linked members commenting on videos earn a little Scrap.
- Rank rewards are planned and will never be sold in the shop.

### New items and gear
- **New gear tiers** that unlock over time.
- **Flaming arrow** for the bow.
- **`/camp spin`**, a spin-the-wheel idea.

### Shop events
- **Sales** on items.
- **Double Scrap / double XP** events.
- **Set bundles** (head and body together): the code exists but is **off by design**. Pieces are sold one at a time.

### Specials (shown in the shop as "Coming soon")
- **Hair Color unlock** (150): lets you use `/camp look custom_hair:#hex` for any hair color.
- **WILSON!** (190): a special animation where your survivor holds up the volleyball and yells "WILSON!" (Wollie is the volleyball, a nod to Cast Away and Stranded Deep).
- **Campfire** (250): an add-on survivors can gather around. Details still to come.

### New looks
- A **Grumpy** mood.
- **Facial hair** (draft art exists, currently on hold).

### Jest
- A **pet Jest** animation (an idea like `!camp pet`, where she walks to your survivor and purrs).
- An idea for a `!camp treat` that costs Scrap.

### Server perks
- Shoutout on stream, naming a caravan NPC, dog or landmark, picking a stream challenge, and a name color for 30 days.

---

## 12. FAQ and troubleshooting

**I typed `!camp join` and nothing happened.**
Make sure it's at the very start of your message, with a space: `!camp join`. Plain `!join` isn't ours. Other possibilities: camp is full, joins are paused, you're on the 5-minute rejoin cooldown, or the overlay isn't on right now (it only runs during streams). Chat replies are limited, so you won't always get a message back.

**I typed a `!camp` command in Discord and got a tip.**
`!` commands go in stream chat. In Discord, use the slash version, like `/camp join`.

**The bot deleted my message in Discord!**
You pasted your link code in Discord. That's on purpose, to keep the code safe. Paste it in the **stream** chat instead. The code still works. (If the bot says it cancelled your code, run `/camp link` for a new one.)

**My code says wrong or expired.**
Codes last 10 minutes and work once. Running `/camp link` again replaces the old one. Get a fresh code and use it right away.

**`/camp join` says camp isn't open.**
The overlay only runs while Sharpie360 is live. Try again during a stream.

**`/camp join` says I'm not linked.**
Do the linking steps in section 2 first.

**I changed my outfit or look, but my survivor didn't change.**
Give it about a minute. Make sure you're linked, because guests always show the default look. Also check that you pressed **Equip**: just trying something on doesn't save it.

**Why is my survivor wearing something I never picked?**
That's your starter outfit (guests and not-yet-launch survivors get one). Equip something in `/camp backpack` to change it.

**I watch on two platforms. Will I have two survivors?**
Not if both are linked. You get one survivor, and it switches its icon to whichever platform you type from. Guests get one survivor per platform.

**My guest survivor left after 3 minutes.**
That's the guest limit. Link up for a longer stay (until you've been quiet for 10 minutes).

**I can't open `/camp shop` or `/camp backpack`.**
The shop isn't open to members yet. The staff can also limit these commands to certain roles for a while. If so, the bot tells you which role is needed. Also, the buttons stop after 10 minutes, so just run the command again.

**When does the shop open? Can I buy things now?**
Not yet. The target launch day is Fri Oct 30, 2026. Until then you can link your account, try items on in `/camp backpack`, and check `/camp wallet`.

**My wallet says 0 Scrap but I have XP.**
That's normal before launch. Your Scrap starts on launch day. The **Waiting for Launch** line shows what you'll start with.

**`/camp daily` says it hasn't started.**
It starts when the shop opens.

**What's a Founding Survivor?**
Anyone who links their account before launch. You get a gold tag and a one-time free pick of 2 heads, 2 outfits and 2 tools from the starter items (not Vollie), in the backpack's Founder Picks tab. Link now to be one.

**Someone asked for my password to "link" me.**
That's a scam. Linking only ever uses the one-time code from `/camp link`. Report it to the staff.

**How do I stop being linked?**
Run `/camp unlink` in Discord (all platforms, or pick one), or type `!camp unlink` in stream chat from the name you want to unlink.

---

## 13. For mods: admin commands

Members don't need this part. These commands are for staff only, and every change is logged.

**`/campadmin`** (needs Manage Server, or the mod role once it has been added):
- `check` shows a member's Scrap, XP, rank and their last 10 changes.
- `give` gives a member 1 to 10,000 Scrap, with a reason and a private or public notice.
- `give-all` gives every member Scrap, after a confirm. It makes one no-ping post in the campfire channel and has a 10-minute cooldown.
- `take` takes Scrap away (never below 0).
- `founder` (`add`, `remove`, `list`) changes or shows who is a Founding Survivor.
- `setup` sets the campfire channel and the mod log channel.

**Launch day:** `/sharpie shop launch` (staff, once, with a confirm) turns the shop on, carries over everyone's Scrap and saves the Founding Survivors. Then check `/campadmin founder list`, and run the launch day gift with `give-all`. The full order is in the bot's DOCS.md under "Launch Plan".

---

See you at camp. 🔥
Stay Sharp! 🔪
