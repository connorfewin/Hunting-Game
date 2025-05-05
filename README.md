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
- [ ] Ammo Counter
  - [ ] Reload Delay
- [ ] Purchase Ammo
- [ ] Basic Trading Post UI
  - [ ] Sell Instructions
  - [ ] Buy Instructions 
