+++
title = 'Onboarding (MO2)'
weight = 30
+++

Now that Synergy VR is downloaded and installed, you'll manage the list and launch the game through **Mod Organizer 2 (MO2)**.

{{< aside type="btw" title="Full load order" >}}
If you'd rather just read the whole list, it's on the [Load Order](/load-order/synergy-rc35/) page: every mod, searchable, with links to its Nexus page.
{{< /aside >}}

## Before you play…

You don't need to understand everything about MO2 before your first launch. Synergy VR arrives configured and playable, and the setup below is mostly a series of choices rather than a list of chores.

Scroll down (or filter!) the left pane until you reach a folder labeled {{< btn-inline folder >}}START HERE - EXPAND TO SETUP{{< /btn-inline >}}. It's light blue and easy to find.

<div class="separator mo2-start">
  <i class="fa fa-folder"></i> ▸ START HERE - EXPAND TO SETUP
</div>

Expand it and you'll find four numbered steps plus a folder of optional mods. Work through those in order.

{{< aside type="btw" title="Find it fast" >}}
There's a filter box at the bottom of the left pane. Type `START` and MO2 will hide everything else. Then click on that `START` row, and it will show you the appropriate row in context.
{{< /aside >}}

---
## Step 1 — Preferred Runtime

<div class="separator mo2-runtime">
  <i class="fa fa-folder"></i> ▸▸ Step 1 - Select ONE Preferred Runtime
</div>

A _VR runtime_ is the software layer between the game and your headset. Step 1 asks you to pick one, and nothing here is enabled to start with. This is a decision for you to make. Selecting nothing means you're using SteamVR.

### OpenComposite

<div class="separator sub mo2-ocu">
  <i class="fa fa-folder"></i> ▸▸▸ Open Composite
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> OpenComposite Unleashed for Skyrim VR
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> OC - ENB Fix (ONLY Enable if Wireless &amp; Using ENB)
</div>

{{< nexus 171182 >}}OpenComposite Unleashed{{< /nexus >}} is the right choice for most players. It talks to your headset's native OpenXR runtime and skips SteamVR entirely, which usually means a few frames back and one less layer to go wrong.

Enable **OC - ENB Fix** only if you're playing wirelessly *and* using an ENB preset. If either of those things isn't true, leave it off.

### SteamVR

<div class="separator sub mo2-steamvr">
  <i class="fa fa-folder"></i> ▸▸▸ Steam VR
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> VRIK Controller Bindings - Easy Shout
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> VRIK Controller Bindings - Standard
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> Controller Bindings - Kvite
</div>

Stick with SteamVR if you have a _really good reason_, like a treadmill, body trackers, or some other accessory that needs it. Then enable _one_ of the three binding sets, which replace Skyrim VR's stock controls:

* {{< nexus 53186 >}}Controller Bindings - Kvite{{< /nexus >}} is default in OCU, and a good place to start.
* {{< nexus 23416 >}}VRIK Controller Bindings - Standard{{< /nexus >}} only differs slightly from vanilla.
* {{< nexus 49650 >}}VRIK Controller Bindings - Easy Shout{{< /nexus >}} is the same as VRIK Standard apart from the binding for _use shout/power_.

{{< aside type="alert" title="Don't enable these bindings with OpenComposite" >}}
If you chose OpenComposite, leave all three binding mods **off**. OCU manages controller bindings itself, and a SteamVR binding mod on top of it will fight for the same inputs. To customize your controls under OCU, use its own Configurator instead: right-click the OpenComposite Unleashed mod, choose {{< btn-inline >}}Open in Explorer{{< /btn-inline >}}, and run the Configurator from there.
{{< /aside >}}

---
## Step 2 — ENB Preset

<div class="separator mo2-perf">
  <i class="fa fa-folder"></i> ▸▸ Step 2 - Select ENB Preset
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly" checked> HOSE NATIII - SYNERGY ENB - Performance
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> HOSE NATIII - SYNERGY ENB - Quality
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> Scenery ENB VR - LUX Edition
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> SNIP's ENB - REALISM (WIP)
</div>

**HOSE NATIII - SYNERGY ENB - Performance** is the default preset at the moment. It's built for this list and tuned for VR, with nice daylight and nights dark enough that carrying a torch is worthwhile (immersion!).

The others are alternatives, not additions, so enable _one_ at most:

* **HOSE NATIII - SYNERGY ENB - Quality** is the same as HOSE'S preset with things cranked up for those with GPU power to spare.
* {{< nexus 35545 >}}Scenery ENB VR - LUX Edition{{< /nexus >}} is a different look entirely, built around the list's Lux lighting.
* **SNIP's ENB - REALISM (WIP)** is a work in progress (hence the "WIP") and is currently only really tuned for exterior daytime.

---
## Step 3 — Performance Options

<div class="separator mo2-cs">
  <i class="fa fa-folder"></i> ▸▸ Step 3 - Select Performance Options
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> Grass Density - Quality
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> LOD Distance - Quality
</div>

Both entries here trade frames for scenery, and both are unchecked by default, which automatically leaves you on more performance-friendly presets. Check **Grass Density - Quality** for thicker grass, or **LOD Distance - Quality** for more detailed distant terrain and structures. Each one costs frame rate outdoors, so add them one at a time and see how you (and your hardware) feel about it.

---
## Step 4 — Werewolf and Vampire Bodies

<div class="separator mo2-grass">
  <i class="fa fa-folder"></i> ▸▸ Step 4 - Select One Werewolf &amp; Vampire Body
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly" checked> Werewolf Body for VR
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> WereBear Body for VR
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly" checked> Vampire Lord Body for VR - Male
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> Vampire Lord Body for VR - Female
</div>

These give you a first-person body when you transform, instead of a floating camera with hands. {{< nexus 56394 >}}Werewolf{{< /nexus >}} and {{< nexus 57318 >}}Vampire Lord - Male{{< /nexus >}} are on by default, so if that suits you, there's nothing to do here. Swap them if you like, but remember to turn off the defaults if you enable the alternatives.

---
## Optional Mods

<div class="separator mo2-optional">
  <i class="fa fa-folder"></i> ▸▸ OPTIONAL MODS - Expand to Select
</div>

Everything here is tested against the list. Most is off by default, because most of it comes down to personal taste.

{{< aside type="alert" title="Sync Plugins after enabling" >}}
Whenever you enable or disable an optional mod, run {{< btn-inline >}}Tools{{< /btn-inline >}} → {{< btn-inline >}}Tool Plugins{{< /btn-inline >}} → {{< btn-inline >}}Sync Plugins{{< /btn-inline >}} afterward.
{{< /aside >}}

### Convenience

<div class="separator sub mo2-convenience">
  <i class="fa fa-folder"></i> ▸▸▸ Convenience
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> VRIK Closed Fist
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly" checked> Unlimited Sprinting
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> Insects Begone REDUX
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> Fuz Ro D-oh for Skyrim VR
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> Paraphernalia - VR Dragon Riding
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> Unread Books Glow SSE with MCM
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> More Gold for Merchants - SkyPatcher
</div>

* {{< nexus 182410 >}}VRIK Closed Fist{{< /nexus >}} closes your hands while your weapons are drawn, which makes it clearer whether the game considers you to be in combat.
* {{< nexus 5098 >}}Unlimited Sprinting{{< /nexus >}} removes the stamina drain from sprinting. On by default.
* {{< nexus 91644 >}}Fuz Ro D-oh{{< /nexus >}} adds support for unvoiced dialogue, keeping subtitles on screen long enough to read.
* {{< nexus 105045 >}}Insects Begone REDUX{{< /nexus >}} removes the spiders and bugs.
* {{< nexus 106120 >}}Paraphernalia - VR Dragon Riding{{< /nexus >}} is a lightweight take on dragon riding as fast travel. No requirements, and safe to add mid-playthrough.
* {{< nexus 20679 >}}Unread Books Glow{{< /nexus >}} puts a glow on any book you haven't read yet. Adjust it with its MCM.
* **More Gold for Merchants** ({{< nexus 115157 >}}Wealthy Merchants{{< /nexus >}} on Nexus) gives traders more gold via SkyPatcher, so unburdening your pack doesn't require as many trips.

### Immersion

<div class="separator sub mo2-immersion">
  <i class="fa fa-folder"></i> ▸▸▸ Immersion
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> Durability VR
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> Physical Dodge VR
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> DovaVR Locomotion
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> Be Seated Skyrim VR Edition
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly" checked> No Enemybar and no Names
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> Swap Drop and Hold Redux - VR
</div>

* {{< nexus 76830 >}}Durability VR{{< /nexus >}} degrades weapons and armor with use. This applies to yours, your followers', and your enemies', and it's highly configurable.
* {{< nexus 58605 >}}Physical Dodge VR{{< /nexus >}} lets you lean or step aside to trigger a dodge. If you have the space, Why press a button when you can just _move_?
* {{< nexus 154803 >}}DovaVR Locomotion{{< /nexus >}} drives movement from arm swings instead of the thumbstick. You will look ridiculous, and you will get your steps in.
* {{< nexus 16613 >}}Be Seated{{< /nexus >}} lets you sit down more or less anywhere — a tavern bench, a rock in the wilderness — and actually eat or drink there.
* **No Enemybar and no Names** ({{< nexus 17812 >}}Minimal Enemy Healthbar VR{{< /nexus >}} on Nexus) is on by default. The mod offers several variants. This is the one that drops both the floating health bar and the enemy's name.
* {{< nexus 185816 >}}Swap Drop and Hold Redux{{< /nexus >}} lets you grab a weapon to equip it, tap and hold the trigger to drop it, or yank your equipped weapon across to the other hand to swap. No menus involved.

### Utilities

<div class="separator sub mo2-fps">
  <i class="fa fa-folder"></i> ▸▸▸ Utilities
</div>
<div class="mod sub">
  <input type="checkbox" class="readonly"> Prisma UI Additem Menu
</div>

{{< nexus 179949 >}}Prisma UI Additem Menu{{< /nexus >}} adds an in-game menu for spawning any item from the game or from any mod in the list. It's a great way to test something or recover from a glitch. Oh, and to cheat.

---

Launch the game with the {{< btn-inline play >}}Run{{< /btn-inline >}} button at the top right of MO2, and give the mod menus a moment to register themselves before you start poking at them.
