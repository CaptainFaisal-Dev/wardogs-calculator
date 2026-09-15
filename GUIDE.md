# WARDOGS Fire Direction Center — How to Use

**Live tool:** https://captainfaisal-dev.github.io/wardogs-calculator/
Created by CaptainFaisal

Works on PC and phone. Nothing to install — just open the link.

---

## The 30-second version

1. Pick your **map** and your **artillery type** at the top.
2. **Click where your gun is** on the map.
3. **Click your target.**
4. Read the three numbers: **Distance**, **Azimuth**, **Mil** — dial those into your gun.

That's the whole tool. Everything below is extra.

---

## Step 1 — Pick your map and weapon

At the top you'll see two boxes.

- **MAPS** — Bakurani, Ozeti, or Zestafona. Pick whichever you're playing.
- **ARTILLERY TYPE** — L81 Mortar or SPH-2.

Pick these first, because the range rings and firing solution change depending on which gun you're using.

| | L81 Mortar | SPH-2 |
|---|---|---|
| Range | 132–684 m | 780–2,629 m |
| Arcs | One | Low and High |

---

## Step 2 — Place your gun

**Click once on the map** where your mortar or SPH-2 actually is.

A yellow crosshair marker appears, plus **range rings** showing your minimum and maximum range. Anything inside the inner ring is too close to hit; anything outside the outer ring is too far.

> For the SPH-2 there's also a dashed ring at 1,181 m — inside that distance, only the HIGH arc works.

---

## Step 3 — Place your target

**Click again** where you want the shells to land. A red X appears and a dashed line connects your gun to it.

The tool auto-switches from gun to target after your first click, so two clicks is all it takes.

**To move either one:** just drag the marker. The numbers update live as you drag.

**To re-place one specifically:** click the **⌖ GUN** or **✕ TARGET** button above the map first, then click the map.

---

## Step 4 — Read your firing solution

On the right side you get:

- **DISTANCE** — in meters. This is your **RNG** number on the gun.
- **AZIMUTH** — the compass bearing, 0–360°. Traverse the tube to this.
- **MIL** — the elevation to dial in. For the SPH-2 you get both LOW and HIGH arc options.

Each arc shows **IN RANGE** in green or a red warning like **TOO CLOSE** / **TOO FAR**.

**COPY FIRE MISSION** copies all of it as text you can paste into squad chat.

### In-game, that means:
1. Enter the mortar (**E**).
2. Traverse until your compass matches the **AZIMUTH**.
3. Set the **RNG**/mil to match what the tool says.
4. Fire one shell first (see Step 6).

---

## Step 5 — Mark the Control Zone

Every match the CZ lands somewhere different, so you set it yourself.

1. Click the **◎ CZ** button above the map.
2. Click where the zone is this match.

You get a white dashed circle at true scale (500 m radius, 550 m on Ozeti). **Drag it** to fine-tune.

**To remove it:** press the **◎ CZ** button a second time.

> **Why this matters:** with the CZ circle and your gun's range rings both on screen, you can see instantly whether a firing position actually covers the zone — *before* you waste time building there.

---

## Step 6 — Fix a miss (ranging correction)

Your first shell will rarely be perfect, because the firing tables assume flat ground and the maps aren't flat. Shooting uphill lands short; downhill lands long. So fire **one** ranging shell, watch where it lands, then correct.

In the **RANGING-SHOT CORRECTION** box:

1. Pick **SHORT** or **LONG** and type how many meters off it was.
2. Pick **LEFT** or **RIGHT** and type the sideways error in meters.
3. Press **CORRECT**.

You get a corrected azimuth and mil. Dial those in and fire for effect. **CLEAR** resets it.

---

## Step 7 — Save targets you'll hit again

Got a spot worth remembering — a tower, a bridge, a chokepoint?

1. Place your target on it.
2. Type a name in the **SAVED TARGETS** box.
3. Press **SAVE**.

It appears in the list and as a small dot on the map. **Click any saved target** to instantly re-aim at it — useful for switching between two known positions fast.

Press the **✕** next to one to delete it.

---

## Step 8 — Mark enemies and points of interest

**Right-click anywhere on the map** (on phone: **press and hold**) to open the marker menu.

| Marker | Color |
|---|---|
| Enemy Tank / APC / Infantry / Artillery / Heli / FOB | Red |
| Our FOB | Green |
| Heli LZ | Blue |
| Supply | Khaki |
| Danger | Amber |

Each uses the game's own icon so you can tell them apart at a glance.

**To remove one:** right-click (or hold) directly on it → **REMOVE MARKER**.

---

## Step 9 — Start a new match

Press **RESET MAP**, then press it again to confirm.

This clears your gun, target, CZ circle, and all enemy markers — a clean map for the new game. Your **saved targets stay**, since those are your permanent bookmarks.

---

## Map controls

| Action | PC | Phone |
|---|---|---|
| Move around | Drag | Drag |
| Zoom | Scroll wheel | Pinch |
| Zoom buttons | **+** / **−** / **FIT** | same |
| Place marker | Left-click | Tap |
| Marker menu | Right-click | Press and hold |

- **☀ slider** — brightens the map if the terrain is too dark to read.
- **TOPO / TERRAIN** — switches between real imagery and elevation contour lines. The contour view is genuinely useful for spotting whether your target is uphill or downhill from your gun.
- **HD ✓** appears bottom-right when high-detail imagery has loaded in.

---

## Things worth knowing

**Always fire one ranging shell first.** The firing tables assume your gun and target are at the same height. They usually aren't. One ranging shell plus a correction beats a perfect calculation onto a hillside.

**Level your SPH-2.** It's a vehicle — park it on a slope and the elevation you dialed isn't the elevation you get. Check the tilt markers either side of the vehicle silhouette in the gunner's view.

**Spread is normal.** Shells land in a group, not on a pixel. The further you shoot, the wider that group — that's built into the weapons, not an error in your math.

**Your data is private and automatic.** Everything saves in your own browser as you go. Close the tab, come back later, it's all still there. Your friends' markers never touch yours.

**The mortar's range is community-measured**, not published by the developers, and Early Access patches can change it. If shots consistently land off at a known distance, tell me and the tables can be updated.

---

## Sharing it

Send friends the link:
**https://captainfaisal-dev.github.io/wardogs-calculator/**

It works on any phone or PC browser, free, no account or install needed.

---

*Terrain and ballistics data from the open-source wardogs-calculator project by Apollyon (MIT licence). Unofficial fan tool, not affiliated with BULKHEAD or Team17.*
