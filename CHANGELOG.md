# Changelog

## 1.7.12

- Every file of the addon now starts with its licence (GPL version 2), the author's name and the
  tribute to Kuron. Nothing changes in the game.

## 1.7.11

- Cooldowns > Both rows: "Show keybinds" puts the key bound on your action bars on each icon
  (the game's bars or EllesmereUI's), with its size, position and colour. Off by default.
- Shapeshift Counter: "One on each side" is now called "Shapeshifts left, Shifting Power right".
  Shifting Power is a Feral talent shown in Cat Form only, so without it the right side is empty.

## 1.7.10

- Horizontal and vertical offsets for the cooldown rows (each row's page), the shapeshift counter
  and Clearcasting's arcs (spacing and height). All 0 by default, so nothing moves until you set
  them. A moved row keeps its room in the HUD, so the rest stays where it was.

## 1.7.9

- Each combo point has its own colour (Resource Bars > Combo points). Your current colours are
  kept: points 1 to 4 take the combo point colour, the fifth its own.
- Clearcasting's arcs: their own width, height and colour. Your current size and colour are kept.

## 1.7.8

- Demoralizing Roar is in Cooldowns > "Add from the druid list". The game's Cooldown Manager only
  offers it as a bar, so its time left on the target had no icon to show on.

## 1.7.7

- Same as 1.7.6, which didn't reach CurseForge.

## 1.7.6

- Abilities the target is out of range of (Feral Charge, Faerie Fire, ...) turn red-grey on the
  cooldown icons, as in the game's Cooldown Manager. A switch under Rotation Hints > Range.
- Cast Sounds: a sound file of your own when Clearcasting procs.

## 1.7.5

- The blue mark on the energy bar (Shifting Power's energy ceiling) now shows only while Shifting
  Power is ready or within 3 seconds of it. Change the seconds, or have it always shown, under
  Rotation Hints.

## 1.7.4

- The timers on the target (Rip, Rake, Pounce, Lacerate, Faerie Fire, Demoralizing Roar, Moonfire,
  Insect Swarm) and the bleed immunity mark no longer go away when a form's rotation hints are
  turned off. Each timer has its own switch, now in its own section at the top of Rotation Hints.
  Had the hints off? The timers show again; turn off the ones you don't want.
- `/miao status` tells why a timer isn't on its icon.
- Barkskin no longer fades or hides outside caster form: it can be cast in every form.

## 1.7.3

- Prowl and Pounce are no longer added to the top cooldown row. Want them? Add them under
  Cooldowns > Add from the druid list.
- "Remove from this row" now removes Prowl, Pounce and other spells you added yourself; before,
  some of them stayed.

## 1.7.2

- Faerie Fire and Demoralizing Roar: a green + in the corner of the icon when the one on the target
  is someone else's (the time left already counts anyone's).
- Demoralizing Roar's time left also counts Demoralizing Shout, Hex of Weakness, Demoralizing
  Screech and Vindication, and Faerie Fire's counts Curse of Recklessness: only one of each group
  applies, so with another class's up there's no need to cast yours.
- New option under Cooldowns: show one decimal on the countdown numbers below a number of seconds
  (off by default).

## 1.7.1

- Prowl and Pounce now appear in the top cooldown row in Cat Form (the game's Cooldown Manager
  doesn't offer them). Already placed or removed them yourself? Then nothing changes.

## 1.7.0

- Pounce: time left on its bleed, on the Pounce icon (the game's Cooldown Manager can't show it).
  Pounce also gets the bleed immunity mark.
- Bleed immunity: elementals, undead and mechanicals now get a yellow ? on Rip, Rake and Lacerate
  instead of a red X, since some of them take bleeds. Your bleeds decide: the red X once the
  target is immune to one, and a Rip that lands clears the ?. Remembered per kind of enemy until
  you log out.
- Mana text now shows on the default mana row (in a smaller font); before, it needed the row to
  be at least 8 high.

## 1.6.2

- Powershifting (for example `/cast !Dire Bear Form`) no longer leaves the HUD showing caster form.

## 1.6.1

- The Clearcasting alert shows in caster form again: out of combat it now goes by the buff itself,
  and in combat any spell Clearcasting makes free can show it.
- `/miao status` lists the state of each aura timer, to help with reports.

## 1.6.0

- Rotation hints follow the latest wowsims rotation: Ferocious Bite at 5 combo points from 60
  energy (45 with Clearcasting); the Hybrid / Claw build uses Bite from 5 combo points only, so
  its 4-point ring and mark are gone; Shifting Power up to 53 energy; Enrage lights when rage is
  short of Lacerate.
- The cast bar is now off by default (and switched off once on update); turn it on under
  Resource Bars, Cast Bar. With it off you have the game's own cast bar.
- The cast bar's description in the settings now says how to go back to the game's own cast bar.

## 1.5.3

- Lacerate (and every other aura timer whose aura stacks) shows its stacks next to the time left.
  Its own switch on the Rotation Hints page.

## 1.5.2

- Faerie Fire now shows its time left on the target in every form (Cat, Moonkin, caster, Travel),
  as it did in Bear Form, instead of only its cooldown. Each form has its own switch in the new
  Faerie Fire section of the Rotation Hints page.

## 1.5.1

- The cast bar replaces the game's own by default, so there is only one: while Miao Litter's is
  on, the game's cast bar stays away (switch back any time; a reload resets it too). You can also
  keep the game's and show Miao Litter's only when it is hidden, or show both.
- The cast bar now also shows when the HUD is hidden (out of combat, without a target or while
  mounted, if you set it that way), and it is always fully visible.
- Turning Miao Litter off in its settings gives the game's cast bar back right away.

## 1.5.0

- New: a cast bar under the HUD (or above it), only while you cast. Turning off EllesmereUI's
  Resource Bars also removed its cast bar; this one takes over. Its own switch, size, position and
  colours on the Resource Bars page.
- New Welcome page at the top of the settings: what Miao Litter is, how much you can change, and
  where to start.
- The first-login prompt now says hello, and a first login with nothing to turn off gets a short
  welcome too (once). Both suggest a SharedMedia addon for more bar textures and fonts.
- The swing timer now has its own thin row at the bottom of the bars, so the main bar is less
  crowded. You can put it back inside the main bar (Resource Bars page, Swing timer, "Where").
- The second row shows a dark bar in a form that has nothing for it (for example Moonkin with
  background energy off), like the combo point row, instead of an empty gap. A gap is an option.
- The block order on the General page lists every row, including the health bar and the swing timer.

## 1.4.1

- Shapeshift counter: choose which forms are counted and their order (the big cell is your current
  form; in caster form, the first of your order). Shapeshift Counter page, "Forms".
- Combo point colours can also be set right in the combo points section of the Resource Bars page.

## 1.4.0

- First login: one simple prompt lists what Miao Litter replaces (the game's own cooldown
  display, EllesmereUI's Cooldown Manager and Resource Bars) and turns them off, for this
  character only. Your other characters keep their setup.
- The EllesmereUI page, and the Miao Litter page inside EllesmereUI's options, can switch those
  EllesmereUI parts on and off for this character.
- The tracking reminder only asks for abilities the Cooldown Manager can actually track (no more
  Ferocious Bite, Maul or Moonfire).
- A note on the no-bleeds option: on Forever some undead, mechanical and elemental enemies still
  take bleeds.
- A tribute to Kuron under the author's name in the settings window.

## 1.3.1

- The global cooldown line is thinner, glows, and takes a highlight colour that contrasts with the
  main bar (blue on energy, cyan on rage, gold on mana), led by a soft glowing dot. Your own colour
  and the dot are options.
- The swing timer's dark background strip has an opacity setting.
- The swing timer also shows in caster form (you can melee there too).
- Fixed: the global cooldown line around the main bar only showed now and then in Cat Form, when
  abilities were pressed back to back.

## 1.3.0

- New: a swing timer, a thin line inside the bottom of the main bar, in Cat and Bear Form. It
  turns orange while Maul is queued.
- New: the global cooldown as a line that runs once around the main bar's border.
- Both can be switched off, each on its own (Resource Bars page).
- Fixed: the first-login reminder about untracked abilities drew its text under the buttons
  when the list was long.

## 1.2.0

- New: a health bar (off by default; Resource Bars page). It sits under the second row and can be
  moved like the other blocks.
- Background energy now also shows in Travel Form.
- The shapeshift counter follows everything that makes a shift cheaper (Natural Shapeshifter, the
  Idol of Shifting Tides, Rune of Metamorphosis, set bonuses) as soon as it changes; a free shift
  shows the top count.
- Fixed: "Use Miao Litter's rows" in the EllesmereUI prompt could leave EllesmereUI's Cooldown
  Manager on (when your addon list has it on for that character); it is now switched off for
  the character and checked before the reload.
- First login: if the game's own cooldown display is on next to Miao Litter's rows, you are asked
  which one to keep (or both). The Cooldowns page has a switch for it.
- A reminder lists the abilities you know that aren't tracked in the game's Cooldown Manager yet
  (so they have no icon and no hint), with a button to open it. It can be turned off.

## 1.1.0

- New **Cast Sounds** tab: play your own .ogg, .wav or .mp3 file when you cast a spell. Add as many as
  you like; each has a spell (every rank counts), a sound file, when it plays (cast succeeds, or
  cast / channel starts), a volume channel, a note, and a Test button.
- Bear and Moonkin hints on your cooldown icons, from the wowsims rotations: Primal Bite, Maul,
  Enrage, Lacerate / Faerie Fire / Demoralizing Roar timers, Barkskin and Frenzied Regeneration at
  low health, marks on the rage bar; Moonfire / Insect Swarm timers, Starfire during Eclipse,
  Innervate at low mana.
- A red X on Rip, Rake and Lacerate when your target is an elemental, undead or mechanical (bleeds don't work on them; each type has its own switch).
- Icons can be round or rounded, with shaded edges or gloss, and their own border. One setting
  (Appearance → Icons) covers the cooldown rows, the shapeshift counter and the Clearcasting icon.
- Fixed: the HUD went back to its starting position after an option change, a loading screen, a
  relog or a reload when it had been placed with EllesmereUI's unlock mode (or another mover). It
  now remembers where it actually is.
- A link to the Druid Discord on the About page and in the game's AddOns settings.
- Settings tidied up: combo points moved onto the Resource Bars page; the second row's mana and
  background energy options are in one section; what a cooldown icon shows (numbers, swipe,
  greying, opacity) is set once for both rows; the hints page is grouped by form. Your settings
  carry over.
- Outside Cat Form the combo point row is filled by a dark bar instead of an empty gap (or empty,
  dimmed points, or nothing: your choice on the Resource Bars page).

## 1.0.0

First public version. (0.1.0 and 0.2.0 were private test builds.)

- Resource bars for every form: a main bar (energy, rage or mana) and one thin row under it for
  mana and background energy. Nothing moves or resizes when you shapeshift.
- Combo points spread across the bar, in five shapes.
- Shapeshift counter that works in combat: the current form, small cells for the other forms you
  know, and Shifting Power.
- Clearcasting alert: blue arcs bouncing on both sides of the bars, flash, timer line, icon, sound.
- Cat rotation hints on your cooldown icons (Rip, Rake, Bite, Shifting Power) and marks on the
  energy bar; the build (Cat / Shred or Hybrid / Claw) is detected from your talents.
- Cooldown rows fed by the game's Cooldown Manager; the top row is one centred line and shows only
  what the current form can cast.
- Six themes, five layouts, profiles with text import and export.
- Settings window (`/miao`), a page in the game's AddOns options, English and Simplified Chinese.
- EllesmereUI: accent colour, options page, unlock mode, and a prompt when its Cooldown Manager and
  Miao Litter's cooldown rows are both on.
- Druid only: on other classes the addon does nothing at all.
