# Changelog

What's new in each playable build of the TopDownMMO Prototype.
Download builds from the [Releases](https://github.com/KizGames/TopDownMMO-Downloads/releases) page.
Dates are in Pacific Time.

## 0.1.07 - 2026-10-08
- **Sword & Shield:** your character now carries a sword and a round wooden shield. Out of
  combat the sword hangs on your hip and the shield on your back; attacking draws them and
  they go away by themselves after 5 seconds. Press **X** to draw or sheathe them yourself.
  With weapons out you hold the shield up in front.
- **You can get hurt now:** 100 health, a health bar, red numbers for damage you take, a death
  screen, and a respawn at the start point after 5 seconds.
- **Healing Dummies and R = Test Heal:** two dummies with green health bars next to the
  training dummies start half full. Press **R** to heal the one under the mouse (or yourself)
  for 25. A placeholder until healing weapons exist.
- **First enemies:** a small placeholder camp south-east of the start (a Brute and two
  Skirmishers). They chase you, flash a red warning on the ground before they hit, and give
  up if you run far enough. All enemies now find their way around trees and rocks.
- **The wolf den** north-west of the start: 6 gray wolves, 2 matriarchs and 1 big black alpha,
  with real animated wolf models (trot, gallop, bite, leap, flinch, death, howl).
  - Wolves fight as a pack: hit one and its friends nearby join in.
  - Matriarchs and the alpha **leap** at you after an orange/red warning on the ground; dash
    sideways to dodge. Gray wolf and matriarch bites make you **bleed** (stacks, shown on the HUD).
  - Kill 3 gray wolves and a **matriarch hunts you**; kill a matriarch and the **alpha hunts
    you**. The hunter howls, a big warning appears on screen, and it follows you a long way.
  - The den refills faster while a matriarch is alive and slower once both are dead.
  - The alpha gets angrier (notices you from further away, leaps and bites more often) when it
    is the last wolf left.
- **Known rough spots:** the Brute and Skirmishers are still plain shapes; the shield can
  poke into the chest in some attack frames; the alpha can get a little closer than its body
  looks; the wolves' tails are a bit stiff.

## 0.1.06 - 2026-10-08
- **New bodies from our concept art:** the male and female characters were made from Richard's
  concept drawings with the help of an AI 3D tool, then cleaned up and fitted to our own
  skeleton, so all the animations work just like before. Skin tones, hair styles, hair colors
  and beards all still work, and the underwear is painted on.
- **New default sword** with a wider blade.
- **Known rough spots:** the bodies look smoother than the faceted concept art, hands and feet
  are simple "mittens", the old hairstyles look rough next to the new bodies, there is some
  creasing at the shoulders and hips, faint marks on the thighs, and the sword rests across the
  body when standing still.

## 0.1.05 - 2026-10-08
- **New Albion-style bodies:** the male and female characters were rebuilt to look like Albion
  Online's: chunky, clean low-poly shapes, broad shoulders, a slightly bigger head, bigger hands
  and feet, and smooth painted-looking shading. Skin tones, hair styles, hair colors and beards
  all still work, and all the animations are the same.
- **Painted underwear and a light skin texture:** the underwear is now painted on the body
  instead of being a separate piece, and the skin has a subtle hand-painted look. This keeps the
  body clean so armor can be added on top later.
- **Softer, more painted world:** grass, dirt, rocks, bushes, trees and the training dummies have
  very light painted detail and gentle shading near the ground. Their shapes are unchanged.
- **Smaller training dummies:** about 1.1-1.2x your height instead of towering over you; their
  health bars and names moved down to match.
- The character creation screen is unchanged.

## 0.1.04 - 2026-10-07
> **New version numbers:** this build comes after 0.3.0 but is called **0.1.04**. From now on
> every update adds one to the last number (0.1.05, 0.1.06, ...). Older builds keep their old numbers.

- **Character creation!** The game now starts on a creation screen: pick Male or Female, a
  faction (placeholder names for now), skin tone, hair style, hair color and (male) beard, or
  hit Randomize. Drag with the mouse to turn your character, scroll to zoom. Type a name (2-16
  letters, no spaces or numbers) and click **Enter World**.
- **New characters:** more detailed, athletic low-poly male and female models with hands, feet
  and faces, 4 hair styles each, 6 hair colors, 6 skin tones and 3 beard styles.
- Only the **Guardian (Tank)** role and the **Human** race can be picked for now; the other roles
  (Priest, Rogue, Mage) and races show "Coming soon".
- **Your character is saved.** Next time you can continue with it or create a new one.
- **Your name shows above your head** in the game.
- **Tab** now shows your character and lets you change your looks (and Male/Female) any time.

## 0.3.0 - 2026-10-07
- **Sound!** Sword swings, hits and misses (a miss sounds different from a hit), spell cast,
  spell impacts (different sounds for hitting a dummy, hitting a rock/tree/bush or the ground,
  and fizzling out at max range), dash, soft footsteps, dummies falling and standing back up,
  and a click when a skill is still on cooldown. All sounds are made from scratch and are early
  versions; feedback welcome.
- **Backwards and sideways running:** moving away from the mouse plays a backwards jog with the
  character leaning back; moving sideways plays a sideways run while the chest keeps facing the mouse.
- **No more sliding feet:** the running animations now play at exactly the speed you move.
- **Tab: character select.** Pick Male or Female any time; your sword and animations come along.
  Tab or Esc closes the menu.
- Spells now hit bushes too (you can still walk through bushes).

## 0.2.1 - 2026-10-07
- **Adjustable camera:** hold **Alt** and roll the **mouse wheel**. Wheel up moves the camera
  closer and lower, behind your character; wheel down moves it further away and more top-down.
  The camera glides smoothly between steps.
- **Double-tap Alt** to glide back to the normal view.
- The mouse wheel on its own does nothing for now (saved for later).

## 0.2.0 - 2026-10-07
- **Real characters:** you now play as a low-poly human instead of a capsule, with animations
  for standing, running, sword swings, dash and casting. The sword is held in the character's hand.
- A male (used in this build) and a female character were made; choosing between them in-game
  comes later.
- These characters are **early placeholders**: simple shapes and basic animations that will
  change a lot. Gameplay (speed, ranges, hit areas) is the same as 0.1.1.

## 0.1.1 - 2026-10-07
- **Wider sword swings:** the basic attack now covers a 160° arc (was 120°), still 2.6 m reach.
  A white slash shows exactly what each swing can hit.
- **Skillshot range:** the Q projectile now travels up to 20 m. If it doesn't hit anything,
  it fizzles out with a small poof.
- **Ranges in meters:** the bottom bar shows each skill's range (Attack 2.6 m, Dash 5 m,
  Skillshot 20 m).

## 0.1.0 - 2026-10-07
- First playable test zone: WASD movement, mouse aim, Space dash, left-click sword attack,
  Q skillshot, and training dummies with health bars and damage numbers.
