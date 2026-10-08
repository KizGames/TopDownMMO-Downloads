# TopDownMMO Prototype - Downloads

Playable test builds of an early 3D top-down action MMO prototype (made with Godot 4).

## How to play (Windows)
1. Go to **Releases** (right side of this page) and download `TopDownMMO_Prototype_Windows.zip` from the latest release.
2. Unzip it, then double-click `TopDownMMO_Prototype.exe`.
3. If Windows shows "Windows protected your PC", click **More info** > **Run anyway** (the game isn't signed yet).
4. Create your character (Male/Female, faction, looks, name) and click **Enter World**. Your character is saved; next time you can continue with it or make a new one.

## Controls
- WASD: move
- Mouse: aim (your character faces the cursor)
- Left Click: sword attack, 160° arc, 2.6 m reach (hold to keep swinging)
- Space: dash (5 m)
- Q: skillshot projectile (range 20 m)
- R: test heal - heals the friendly target under the mouse for 25 (15 m range), or yourself
- X: draw / sheathe your sword and shield
- E / Right Click: placeholders for now
- Alt + Mouse Wheel: camera zoom (up = closer and lower, down = further and more top-down)
- Double-tap Alt: reset the camera to the normal view
- Tab: character panel (your info + change your looks); Tab or Esc closes it

## What's new
Latest version: **0.1.07**. New in this build:
- **Sword & Shield:** your sword hangs on your hip and the shield on your back out of combat; attacking draws them, they go away by themselves after 5 s, and **X** draws/sheathes them.
- **Health, death and respawn:** 100 health, a health bar, red damage numbers; if you die you respawn at the start after 5 s.
- **Healing Dummies + R test heal:** two green-bar dummies next to the training dummies; press **R** to heal them (or yourself).
- **First enemies:** a placeholder camp south-east of the start, and enemies now walk around trees and rocks.
- **The wolf den** with animated wolves: pack fights, leaps you can dodge, bleed, revenge hunts with a howl, and an angry lone alpha.

All versions: see [CHANGELOG.md](CHANGELOG.md).

## Where is the wolf den?
**North-west of where you start**, about 57 m away: a dirt circle with rocks and a rock ridge in front. It holds 6 gray wolves, 2 darker matriarchs and 1 big black alpha.

**Careful - wolf tips:**
- Wolves fight as a **pack**: hit one and the others nearby join in. Pull one or two at a time from the edge.
- Gray wolves and matriarchs make you **bleed** (it stacks; shown above your health bar). Don't let many bite you at once.
- Matriarchs and the alpha **leap** at you: when an orange lane and red circle appear on the ground, **dash (Space) sideways** out of it.
- Kill 3 gray wolves and a **matriarch hunts you**; kill a matriarch and the **alpha hunts you** (a howl and a big warning tell you). You run a little faster than every wolf, so running away works if you dodge the leaps.
- The den refills faster while a matriarch is alive, and the alpha gets angrier when it is the last wolf left.

Version numbers: from 0.1.04 on, every update adds one to the last number (0.1.05, 0.1.06, ...). Builds before that were numbered 0.1.0 to 0.3.0.
