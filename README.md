# 🛠️ Open World Hunting Game - Dev Roadmap
---

# 📈 Project Phases

## 1. Project Setup
- [x] Create new Unity project (URP recommended)
- [x] Setup basic player capsule
- [x] Create flat ground terrain
- [x] Implement basic WASD player movement
- [x] Set up first-person camera (foloow mouse pointer)

---

## 2. Gun Mechanics Prototype
- [x] Add basic gun object (placeholder shape)
- [x] Implement raycast shooting from camera center
- [x] Add basic crosshair UI
- [x] Implement "Focus Aim" (Right Mouse Button) - slight zoom for basic iron sight
- [x] Show bullet hit (spawn sphere at hit point)
- [ ] Display simple ammo counter (optional)

---

## 3. Animal Basics
- [x] Create dummy animal prefab (cube placeholder)
- [x] Add health system to animal
- [x] Animal dies when hit by raycast
- [x] Animal ragdoll when dead
- [x] Implement "drag animal" system (pickup/carry)

---

## 4. Money & Trade Loop Prototype
- [x] Create Outpost (simple box placeholder)
- [x] Trade animal for money on delivery
- [x] Display money counter on UI

---

## 5. Basic Game Loop MVP
- [x] Spawn random animals across terrain
- [x] Hunt → Retrieve → Trade infinite loop

---

## 6. Animal Movement
- [x] Herd Wandering/movement
- [x] Herd Scatter (from gun hit point)
- [x] General Player Avoidance

---

## 7. Hunting Improvements
- [x] Head Shot (Instant kill)
- [x] Body shot (Slows animal down)
- [x] Improve rectical (opaque)
- [x] Gun Sway
- [x] Better hit prefab
  - [x] Stays on animal
  - [x] Looks like wound
     
---
## 8. Basic Store
- [x] Ammo Counter
  - [x] Reload Delay
- [x] Purchase Ammo
- [x] Basic Trading Post UI
  - [x] Sell Sheep Button
  - [x] Buy Ammo Button 

---
## 9. Second Animal (Rare/paranoid)
- [x] Create second animal prefab
- [x] Increase hunting difficulty
- [x] Increased rarity
- [x] Stronger hurding. Try and stay closer together
- [x] Giraffe in the market
- [x] Fix Scatter speed

---
## 10. Hover Info
- [x] Create animal stats UI
- [x] When aiming display animal stats ui
- [x] Distance away indicator

---
## 11. Better Animal Movements
- [ ] Scatter (on gun shot) in random direction
- [ ] Scatter options (paranoid level)
  - Gun Shot Only (Sheep)
  - Player in no sight range or gunshot (Giraffe)
  - Player in sight range, no sight range, or gunshot
- [ ] Player avoidance speed (in comparison to base speed and scatter speed (could pick a random number in between the two))
- [ ] Herd Player Avoidance (if one animal scatters or avoid, once another animal sees it (in sight range or no sight range)) it scatters or avoids too

--- 
## 12. Animal Migration
- [ ] Setup general migration
- [ ] Editable migration stats (Idle sheep vs migrating giraffe)
- [ ] Scatter override from migration
