# Survivor Camp: The Full Beginner's Guide

*Last updated Nov 24, 2026. Matches Survivor Camp v0.54.0 and SharpieBot v0.52.5. The shorter version is the Quick Start.*

Hey, welcome to camp! This guide explains everything from scratch, so you don't need to know anything going in. If you get stuck, jump to the FAQ at the bottom.

---

## Contents
1. What Survivor Camp is
2. Linking your account (step by step)
3. Stream chat commands (the `!` ones)
4. Discord commands (the `/` ones)
5. The camp site
6. `!` vs `/`: which one goes where
7. Your backpack
8. Scrap, ranks and earning
9. The shop
10. Customizing your survivor's look
11. Guests vs linked survivors
12. Other stuff worth knowing
13. Coming soon
14. FAQ and troubleshooting

[Command glossary](#command-glossary): every command in one list.

---

## 1. What Survivor Camp is

Survivor Camp is a little pixel-art game that lives at the bottom of the screen during Sharpie360's adventures.

- You type `!camp join` in stream chat, and your own tiny survivor walks onto the screen.
- Your survivor wanders around camp. You can make it dance, wave, cheer, sit down or walk somewhere.
- If your survivor is holding a tool, it uses it now and then on its own: chops a stump, fishes in a puddle, shoots an arrow, throws a snowball, and so on.
- Your name floats above your survivor, with a small icon for the platform you're chatting from.
- **Jest**, Sharpie360's black cat and the channel mascot, roams camp too. She has a purple name tag. She's not a viewer, so she never takes your spot.

It works on every platform Sharpie360 goes live on: **YouTube, Rumble, Twitch, Kick and VP Zone**. It doesn't matter which one you watch on. On Twitch, Kick and VP Zone, camp's chat replies come from the **SharpieBot** account.

There's also a **camp site**, camp.sharpiethreesixty.media, where you can sign in, see camp, run your survivor and shop (section 5). The camp site is in beta testing right now; ask in Discord for early access.

**Survivor Camp is tied to the SharpieBot Discord server.** You can play as a guest with no Discord at all. If you **link** your stream chat name, you get:
- a **gold name** (guests are white),
- a **longer stay** in camp,
- your **own look**: skin tone, hair color, hairstyle, body type and mood,
- your **own outfit**, picked in your backpack,
- watch-time Scrap and stream codes (section 8),
- a one-time **100 Scrap welcome bonus** and free **Starter Picks** (section 7),
- control of your survivor **from Discord** and the camp site.

---

## 2. Linking your account (step by step)

Linking connects your stream chat name (like your YouTube name) to your survivor. **You never share a password, login or token.** All you use is a short one-time code.

### Steps
1. **Get your code.** Either:
   - in Sharpie360's Discord, type `/camp link` (SharpieBot answers privately), or
   - on the camp site, open **Stream Links** and press **Get Link Code**.
   You get the full command, like `!camp link AB12CD`. The code works **once**, for **10 minutes**. Getting a new code cancels the old one.
2. **Copy the whole command**: `!camp link YOURCODE`.
3. **Paste it into the STREAM chat** on the platform you're watching, while Sharpie360 is live.
   - **Not in Discord!** If you paste it in Discord by mistake, SharpieBot deletes your message to keep your code safe and tells you it belongs in stream chat. Your code still works. (If the bot couldn't delete it, it cancels that code, and you'll need a fresh one.)
4. **Check that it worked.** You'll get a reply in stream chat (`Linked! Welcome to camp, YOURNAME.`), a DM from SharpieBot, and your survivor's name turns **gold** right away.
5. **Do it again for each platform you use**, and control your **one survivor** from each platform. When you type from another platform, your survivor just switches its platform icon.

### Checking and removing links
- `/camp linkedplatforms` in Discord, or the **Stream Links** panel on the camp site, shows your linked names.
- `/camp unlink` in Discord removes all your links. To remove just one, pick a platform. **Unlink** in Stream Links does the same for one name.
- `!camp unlink` in stream chat unlinks **only the name that typed it**.

### Linking troubleshooting
| What you see | What it means / what to do |
|---|---|
| `that code didn't work (wrong or expired)` | Codes last 10 minutes and work once. Get a new one. |
| `that chat name is already linked to another Discord account` | That name belongs to someone else's link. They need to unlink it first. |
| `too many tries. Wait a few minutes` | Too many wrong codes. Wait about 10 minutes and use a fresh code. |
| `linking is offline right now` | The bot or camp is having a moment. Try again later. |
| `type !camp link CODE` | You forgot the code after `!camp link`. |
| No reply at all | Check whether you got the DM, or run `/camp linkedplatforms`. |

**Safety:** Nobody from the channel will ever ask for your password, login or any account token. If someone does, it's not us. Don't post your link code anywhere except the live stream chat, and use it right away.

---

## 3. Stream chat commands (the `!` ones)

Short on time? The [Command glossary](#command-glossary) lists every command with a one-line description.

Type these in the **live stream chat**. Every command is `!camp`, a space, then a word. They aren't case-sensitive.

| Command | What it does |
|---|---|
| `!camp` | A quick welcome message. |
| `!camp help` | Lists the commands in one line. |
| `!camp join` | Your survivor walks into camp (if there's room). |
| `!camp leave` | Your survivor walks off screen. |
| `!camp dance` / `wave` / `spin` | Emotes (you have to be in camp). |
| `!camp dance2` / `cheer` | A disco dance, or fist pumps with hops. |
| `!camp left` / `right` / `stop` | Walk left, walk right, or stop. |
| `!camp goto 0-100` | Walk to a spot: 0 is the far left, 100 the far right. |
| `!camp sit` | Sit down where you are, facing the way you were facing. |
| `!camp watch` | Sit facing away, watching the adventure. |
| `!camp getup` | Stand back up (sits also end after about 5 minutes, or with another action). |
| `!camp hand left` / `right` / `swap` / `empty` | Pick the hand that holds your tool, swap it, or put the tool away. |
| `!camp scrap WORD` | Claim a stream code shown on screen (linked only, section 8). |
| `!camp link CODE` | Link this chat name, using your code. |
| `!camp unlink` | Unlink this chat name (this platform only). |

Good to know:
- **Older forms still work:** `!joincamp`, `!leavecamp`, `!dance`, `!wave`, `!spin`, `!linksurvivor CODE`. Typing without the space works too: `!campjoin`, `!camphelp` and so on. `/camp legacycmds` in Discord lists them.
- **Plain `!join` and `!link` are NOT camp commands.** `!join` is used for giveaways.
- An unknown word like `!camp xyz` is ignored quietly, so chat stays clean. Emotes, walking and sitting show on screen with no chat reply.
- `!camp` has to be at the **start** of your message.
- Emotes have a short cooldown (about 2 seconds per person).
- While your survivor is inside the Driftwood Nest shop (section 9), `!camp` commands don't work. Head back to camp first.

---

## 4. Discord commands (the `/` ones)

Type these in **Sharpie360's Discord server**. Type `/camp` and Discord shows a menu. **Every reply is private**: only you can see it.

### Account and Scrap
| Command | What it does |
|---|---|
| `/camp link` | Gets your one-time link code (section 2). |
| `/camp unlink [platform]` | Removes one platform's link, or all of them. |
| `/camp linkedplatforms` | Shows which platforms you've linked. |
| `/camp wallet` | Your Scrap, XP and rank. |
| `/camp daily` | Claim your daily Scrap. |
| `/camp help` | Lists the stream chat commands. |
| `/camp legacycmds` | Lists the older chat commands that still work. |

### Style, gear and shop
| Command | What it does |
|---|---|
| `/camp look` | Skin tone, hair color and hairstyle. `random:True` rolls a new look. |
| `/camp body` | Man or Woman. |
| `/camp mood` | Happy, Content or Grumpy. |
| `/camp hand` | Left, Right, Swap or Empty (tool put away). |
| `/camp backpack` | Try on and equip what you own (section 7). |
| `/camp shop` | Browse, preview, buy and sell (section 9). |
| `/camp sell` | Sell an item you bought back for what you paid. |

### Moving your survivor from Discord (while live)
`/camp join`, `/camp leave`, `/camp dance`, `/camp wave`, `/camp dance2`, `/camp cheer`, `/camp sit`, `/camp watch`, `/camp getup` work just like the `!camp` versions.

- They work if you've linked a stream chat name **or** signed in on the camp site with Discord.
- If camp isn't running, you'll see "Camp isn't open right now… Try again when Sharpie360 is live!"
- You can send one camp command every few seconds.

---

## 5. The camp site

**camp.sharpiethreesixty.media** shows camp live, on any screen, including phones. The camp site is in beta testing right now; ask in Discord for early access.

- **Sign in** with **Discord** or **Google** (coming soon). Google sign-in won't need a YouTube channel.
- **No stream chat name needed.** Signed in, you can press **Join** (or type `!camp join` in the site chat) and walk in under your camp name. Link a stream chat name later and it's still one survivor.
- **Actions:** join, leave, emotes, walk left/right/stop, Go To (press it, then tap the spot), hands. On a keyboard: A or ← walks left, D or → walks right, S or ↓ stops.
- **Daily button:** claim your daily Scrap here or with `/camp daily`. Once a day either way.
- **Backpack:** your items, the Storage Chest and gifts (section 7).
- **Driftwood Nest:** the shop hut in camp (section 9).
- **Stream Links:** your linked chat names, Get Link Code, and Unlink.
- **Anchored Accounts** (in Settings): the sign-ins that open your survivor. Add a second one (say Google as well as Discord, once Google sign-in is live) so you can sign in either way. You always keep at least one. Already have a survivor? Sign in with that account first, so you don't start a new one by mistake.
- You stay signed in for 30 days while you keep using the site.

---

## 6. `!` vs `/`: which one goes where

- **`!` = stream chat** (and the camp site's chat box).
- **`/` = Discord.** Discord pops up a menu when you type `/`.

| Command | Stream chat (`!`) | Discord (`/`) |
|---|---|---|
| Join, leave, emotes, sit | `!camp join` … | `/camp join` … |
| Walk and Go To | `!camp left`, `!camp goto 50` | no (camp site Actions) |
| **Get a link code** | no | **`/camp link`** (or the camp site) |
| **Use the link code** | **`!camp link CODE`** | no (the bot deletes it to protect you) |
| Unlink | `!camp unlink` (this name only) | `/camp unlink` |
| Hand | `!camp hand left` | `/camp hand` |
| Stream codes | `!camp scrap WORD` | no |
| Look, body, mood | no | `/camp look`, `/camp body`, `/camp mood` |
| Wallet and daily | no | `/camp wallet`, `/camp daily` |
| Backpack and shop | no | `/camp backpack`, `/camp shop` |

If you type `!camp join` in **Discord**, SharpieBot gives you a gentle tip to use the slash version. `/camp ...` typed in **stream chat** does nothing.

Memory trick: **the code is born in Discord (or the camp site) and used in stream chat.**

---

## 7. Your backpack

The backpack is where you **try on and wear** your items. Open it with `/camp backpack` in Discord or **Backpack** on the camp site.

- You wear **one head, one body, one tool and one accessory** at a time.
- In Discord: pick a tab (All items, Heads, Bodies, Tools, Accessories), tap a number to **try it on**, then press **Equip** to keep it. **Unequip all** shows the plain survivor. Buttons stop after 10 minutes; just run it again.
- On the camp site: tap or double-tap an item to equip it. The backpack holds 50 items.
- **Storage Chest** (camp site): extra room for gear. Tier I is 24 slots for 500 Scrap, II is 48 for 1,000, III is 96 for 2,000. Store, Take or Swap items between the backpack and the chest.
- **Gifts** (camp site): give an item you **bought** to another survivor. If they already own it, you can pick a different item or send its Scrap value instead. Free items can't be gifted. A gift you receive shows a pop-up and a NEW mark.
- Changes show on screen **within about a minute**, even if your survivor is already in camp.

### Starter Picks
Linked members get a one-time, free **Starter Picks** tab in `/camp backpack`: choose up to **2 heads, 2 outfits and 2 tools** from the starter items (not Vollie), then press **Lock In** and confirm. Your picks are yours for good and can't be changed.

### Founding Survivors
Everyone who linked by **Sun Nov 8, 2026, 8 AM Central** is a **Founding Survivor**: a gold tag on the backpack picture, a gold glow in camp, the Founding Survivor Discord role, and every starter item except Vollie, free. That window has closed.

---

## 8. Scrap, ranks and earning

- **Scrap** is camp's currency. You spend it in the shop. It has no real-money value.
- Earned Scrap also counts as **XP**. XP is a lifetime total, never goes down, and sets your **rank**. Spending Scrap never lowers XP.
- Everyone in the Discord server has a wallet. You need to be linked to earn watch-time Scrap and stream codes.
- Check it with `/camp wallet`, or see your Scrap at the top of the camp site.

### How you earn Scrap
| Way | How much |
|---|---|
| Welcome bonus | **100** once |
| Daily (`/camp daily` or the site's Daily button) | **16** on day 1, **+1** for each day in a row, up to **25**. Resets at midnight Central. Miss a day and the streak starts over. |
| Chatting in Discord | 2 per message, one counted a minute, up to 120 a day |
| Voice chat | 1 every 5 minutes with 2 or more people, up to 60 a day |
| Watching live (linked) | 1 per 5 active minutes, up to 36 a day |
| Stream codes (linked) | `!camp scrap WORD` when a code shows on screen. Usually **20**. Normal codes pay up to **100**, with a **100 a day** cap. **Special Drops** pay up to **500** and skip the daily cap. Once per code. |
| Rank-ups | Bonus Scrap for each new rank (see below). Rank bonus Scrap isn't XP. |

Typical pace: regulars make about **7-13 a day**, the most active folks **28-43**, casual drop-ins **1-4** (before the daily and stream codes).

### Ranks
| Rank | XP needed | Rank-up bonus |
|---|---|---|
| Castaway | 0 | |
| Scavenger | 60 | 25 |
| Forager | 200 | 50 |
| Nomad | 500 | 75 |
| Pathfinder | 1,100 | 100 |
| Ranger | 2,000 | 125 |
| Survivalist | 3,750 | 150 |
| Legend | 6,250 | 175 |
| Paragon | 10,000 | 200 |
| Apex | 15,000 | 225 |

When you rank up, camp says so in stream chat and on the camp site.

---

## 9. The shop

Shop two ways:
- **Discord:** `/camp shop`. Filters: All, Heads, Bodies, Tools, Accessories, Holidays, Specials, Sets. **Preview** shows the item alone or on your survivor. **Buy** asks you to confirm. **Sell** shows on items you can sell.
- **The Driftwood Nest** on the camp site: click the hut in camp (or the Shop tab) and your survivor walks in. Walk with W A S D or the arrows (a pad on phones), and press **E** at the counter to open the shop window. **Leave Shop** or the stairs take you back out.

You can't be charged twice, and your balance can't go below zero.

**Selling:** sell an item you bought for exactly what you paid, in `/camp shop`, `/camp sell` or at the Nest. One sale a minute. Free items (Starter Picks, founder items) can't be sold. A worn item is taken off.

**Sets:** Leaf, Beach, Pajamas, Hide, Fur, Santa and Snowman, each a head plus a body. Pieces are sold one at a time; there are no bundle deals.

### Prices (Scrap)
60 items you can buy, plus 5 camp-only accessories and 2 coming soon.

**Starter** (22 items)
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

**Wood** (7 items)
| Heads | | Bodies | | Tools | |
|---|---|---|---|---|---|
| Branch crown | 75 | Reed wrap | 90 | Wooden sword | 90 |
| Carved bowl helm | 100 | Bark vest | 110 | Wooden shield | 90 |
| | | Wooden plank armor | 150 | | |

**Bone** (11 items)
| Heads | | Bodies | | Tools | |
|---|---|---|---|---|---|
| Skull helm | 240 | Fang collar | 275 | Bone knife | 210 |
| Horn crown | 260 | Rib vest | 290 | Bone spear | 225 |
| | | Plate armor | 310 | Bone ax | 240 |
| | | | | Bone pickax | 240 |
| | | | | Bone shield | 275 |
| | | | | Bone sword | 290 |

**Special tools:** Carved Totem 150, Compass 300, Lantern 500.

**🎃 Halloween** (on sale through December): Witch Hat 150, Pirate Hat + Eye Patch 175, Ghost Sheet 175, Jack-O'-Lantern 225, Skeleton Suit 200, Zombie Rags 200, TOT Bag 125.

**🎄 Christmas:** Santa Hat 150, Santa Suit 200, Snowman Head 225, Snowman Body 200, Antlers 150, Ugly Sweater 200, Candy Cane Sword 175, Wrapped Gift 125, Snowball 150, Twinkle Lights 150 (an accessory).

**Camp-only accessories:** Camp Bandana, Driftwood Shades, Sea Breeze Scarf, Tideline Shells and Trail Patch Sash. They show in the shop, but they **can't be bought with Scrap** right now (the Nest marks them "Equip only"). If you have one, wear it in the accessory slot.

**Coming soon:** WILSON! (190) and Campfire (250).

### Tools and what they do
Every so often your survivor uses its tool: the stone knife whittles, the torch flickers, spears jab, the flask and bottle take a drink, the slingshot and bow shoot across the screen, the axes chop a stump, the pickaxes swing at a rock, the fishing pole casts into a puddle, swords (including the Candy Cane Sword) swing, and the **Snowball** gets thrown. The volleyballs, shields, Lantern, Compass, Carved Totem, TOT Bag and Wrapped Gift are just held or carried.

---

## 10. Customizing your survivor's look

All looks are **free** and set in Discord. Changes show on screen within about a minute.

- **`/camp look`:** skin tone (light, default, tan, brown, deep), hair color (brown, black, dark brown, blonde, auburn, gray, or any `custom_hair` hex like `#3fa7ff`), hairstyle (Default, Short, Buzz, Tied, Messy, Ponytail, Long, Bun, Bob/Fro, Bald). `random:True` rolls a new look.
- **`/camp body`:** Man or Woman.
- **`/camp mood`:** Happy, Content or Grumpy.
- **`/camp hand`:** which hand holds your tool.
- Guests always show the default look with a random starter outfit. Link up to use your own.

---

## 11. Guests vs linked survivors

| | Guest (chat name, not linked) | Linked survivor |
|---|---|---|
| Name color | White | **Gold** |
| How long you stay | **5 minutes** from joining | Until **20 minutes without chatting** |
| Look | Default look, starter outfit | Your look and gear |
| Several platforms | One survivor per platform | **One survivor** for all |
| Control from Discord and the camp site | No | Yes |
| Watch Scrap and stream codes | No | Yes |

Signed in on the camp site with no stream chat name? You can join from the site or Discord under your camp name. Link a chat name so your stream chatting counts too.

Camp holds **20 survivors**, and the streamer can pause joins. *(These are the defaults; they can change during an adventure.)*

---

## 12. Other stuff worth knowing

- **Jest the cat:** Sharpie360's black polydactyl cat. She wanders, sits, naps and sometimes sits next to a survivor. Only the streamer controls her.
- **Platform icons:** the little logo before your name shows where you last typed from. YouTube names show without the `@`.
- **Privacy:** camp only knows your **public chat name**. Linking saves your platform, public chat name, a scrambled (one-way) version of your Discord ID, and your look. Google sign-in (coming soon) shares your email and name to sign you in, but camp stores only the account id. Passwords and tokens are never asked for or kept. Link codes are hidden in the logs.
- **Not live:** Discord camp commands say camp isn't open. Your look, items and links are all saved.

---

## 13. Coming soon

**Not built yet.** Details and timing can change.
- **WILSON!** (190): your survivor holds up the volleyball and yells "WILSON!"
- **Campfire** (250): an add-on survivors can gather around.
- More gear tiers, sales, and events like double Scrap.
- Facial hair, a pet-Jest animation, and rank rewards (never sold in the shop).

---

## 14. FAQ and troubleshooting

**I typed `!camp join` and nothing happened.**
Make sure it's at the start of your message, with a space. Other reasons: camp is full, joins are paused, or Sharpie360 isn't live.

**I typed a `!camp` command in Discord and got a tip.**
`!` commands go in stream chat. In Discord, use the slash version.

**The bot deleted my message in Discord!**
You pasted your link code there. Paste it in **stream** chat instead.

**`/camp join` says I'm not linked.**
Link a chat name (section 2) or sign in on the camp site with Discord, then try again.

**My commands stopped working on the camp site.**
You're probably inside the Driftwood Nest. Leave the shop first.

**I changed my outfit but my survivor didn't change.**
Give it about a minute, and check that you pressed **Equip** (trying on doesn't save).

**I watch on two platforms. Will I have two survivors?**
Not if both are linked. Guests get one per platform.

**I can't sell or gift an item.**
Free items (Starter Picks, founder items) can't be sold or gifted.

**Someone asked for my password to "link" me.**
That's a scam. Linking only ever uses the one-time code. Report it to the staff.

**How do I stop being linked?**
`/camp unlink` in Discord, **Unlink** in Stream Links, or `!camp unlink` from the name you want to unlink.

---

## Command glossary

Every Survivor Camp command in one place. `!` commands go in **stream chat** (YouTube, Rumble, Twitch, Kick, VP Zone). `/` commands go in **Discord**.

*`/` only works in Discord. Twitch and Kick block slash commands they don't know, so stream chat uses `!`.*

### 💬 Stream chat (`!`)

**Getting in**
- `!camp join` · your Survivor walks into camp
- `!camp leave` · your Survivor walks out of camp
- `!camp help` · SharpieBot replies with the basic command list
- `!camp` · camp replies with a quick welcome

**Moving and emotes** (your Survivor has to be in camp)
- `!camp dance` · your Survivor dances
- `!camp wave` · your Survivor waves
- `!camp spin` · your Survivor spins in place
- `!camp dance2` · your Survivor does a disco dance
- `!camp cheer` · your Survivor cheers with fist pumps
- `!camp left` · your Survivor walks left
- `!camp right` · your Survivor walks right
- `!camp stop` · your Survivor stops walking
- `!camp goto 50` · your Survivor walks to a spot (0 = far left, 100 = far right)
- `!camp sit` · your Survivor sits down where it is
- `!camp watch` · your Survivor sits facing away to watch the adventure
- `!camp getup` · your Survivor stands back up

**Look and gear**
- `!camp hand left` · your Survivor holds its tool in the left hand
- `!camp hand right` · your Survivor holds its tool in the right hand
- `!camp hand swap` · your Survivor switches its tool to the other hand
- `!camp hand empty` · your Survivor puts its tool away (it stays in your backpack)

**Scrap**
- `!camp scrap WORD` · claim a stream code shown on screen for Scrap (linked Survivors)

**Account**
- `!camp link CODE` · link this chat name to your Survivor, using the code from `/camp link`
- `!camp unlink` · unlink this chat name (this platform only)

Older forms still work: `!joincamp`, `!leavecamp`, `!dance`, `!wave`, `!spin`, `!linksurvivor CODE`, and every command typed without the space (`!campjoin`).

### 🎮 Discord (`/`)

**Getting in** (while live; linked, or signed in on the camp site with Discord)
- `/camp join` · your Survivor walks into camp
- `/camp leave` · your Survivor walks out of camp

**Moving and emotes**
- `/camp dance` · your Survivor dances
- `/camp wave` · your Survivor waves
- `/camp dance2` · your Survivor does a disco dance
- `/camp cheer` · your Survivor cheers with fist pumps
- `/camp sit` · your Survivor sits down where it is
- `/camp watch` · your Survivor sits facing away to watch the adventure
- `/camp getup` · your Survivor stands back up

**Look and gear**
- `/camp look` · set your Survivor's skin tone, hair color and hairstyle (free; `random:True` rolls a new look)
- `/camp body` · set your Survivor's body type: Man or Woman
- `/camp mood` · set your Survivor's face: Happy, Content or Grumpy
- `/camp hand` · set your Survivor's dominant hand (Left, Right, Swap, or Empty to put the tool away)
- `/camp backpack` · try on and equip your Survivor's gear

**Scrap and shop**
- `/camp wallet` · see your Scrap, XP and rank
- `/camp daily` · claim your daily Scrap
- `/camp shop` · browse, preview, buy and sell gear for your Survivor
- `/camp sell` · sell an item you bought back for what you paid

**Account**
- `/camp link` · get a one-time code to link a stream chat name to your Survivor
- `/camp linkedplatforms` · see which chat names are linked to your Survivor
- `/camp unlink` · unlink one platform, or all of them
- `/camp help` · see the stream chat commands
- `/camp legacycmds` · see the older chat commands that still work

---

See you at camp. 🔥
Stay Sharp! 🔪
