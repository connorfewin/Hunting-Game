# 🛠️ Open World Hunting Game - Dev Roadmap

A 30–60 min task-driven development roadmap to complete the game from start to finish.

✅ = Completed

---

# 📈 Project Phases

Each task should fit in a ~30–60 min session.

---

## 1. Project Setup
- [x] Create new Unity project (URP recommended)
- [x] Setup basic player capsule
- [x] Create flat ground terrain
- [x] Implement basic WASD player movement
- [x] Set up first-person camera (foloow mouse pointer)

---

## 2. Gun Mechanics Prototype
- [ ] Add basic gun object (placeholder shape)
- [ ] Implement raycast shooting from camera center
- [ ] Add basic crosshair UI
- [ ] Implement "Focus Aim" (Right Mouse Button) - slight zoom for basic iron sight
- [ ] Show bullet hit (spawn sphere at hit point)
- [ ] Display simple ammo counter (optional)

---

## 3. Animal Basics
- [ ] Create dummy animal prefab (cube placeholder)
- [ ] Add health system to animal
- [ ] Animal dies when hit by raycast
- [ ] Implement "drag animal" system (pickup/carry)

---

## 4. Money & Trade Loop Prototype
- [ ] Create Outpost (simple box placeholder)
- [ ] Trade animal for money on delivery
- [ ] Display money counter on UI

---

## 5. Basic Game Loop MVP
- [ ] Spawn random animals across terrain
- [ ] Hunt → Retrieve → Trade infinite loop

---

## 6. Animal AI Phase 1 (Sight)
- [ ] Vision range + field of view detection
- [ ] Animals flee if player seen
- [ ] Random flee direction

---

## 7. Animal AI Phase 2 (Hearing)
- [ ] Footstep noise system
- [ ] Hearing radius detection
- [ ] Stealth mode reduces noise

---

## 8. Animal Traits System
- [ ] Create ScriptableObjects for animal stats
- [ ] Traits: speed, vision, hearing, paranoia, weight, trade value
- [ ] Random animal type spawning

---

## 9. Vital Hit System
- [ ] Define hit zones: head, heart, body
- [ ] Head/Heart hit = instant death
- [ ] Body hit = bleedout mechanic

---

## 10. Bleedout System
- [ ] Bleeding over time if not instant kill
- [ ] Blood trail particle system
- [ ] Limping behavior when wounded

---

## 11. Weight & Carry System
- [ ] Animal weight attribute
- [ ] Player carry capacity
- [ ] Movement speed penalty when overloaded

---

## 12. Gun & Gear Upgrades Phase 1
- [ ] Create basic Gun Shop UI
- [ ] Implement gun upgrade system (damage, range, accuracy)
- [ ] Buy upgrades with money

---

## 13. Scope Upgrades
- [ ] Create scope items (2x, 4x, night vision, infrared)
- [ ] Attach scopes to gun
- [ ] Override base "Focus Aim" zoom when equipped
- [ ] Add scope swapping functionality

---

## 14. Vehicles Phase 1
- [ ] Create basic vehicle prefab (ATV placeholder)
- [ ] Implement Enter/Exit vehicle logic
- [ ] Drivable vehicle physics

---

## 15. Polish Pass 1
- [ ] Replace placeholders with low-poly models
- [ ] Add basic sounds: footsteps, gunfire, animal sounds
- [ ] Improve basic visual effects

---

## 16. Advanced Animal AI (Optional Enhancements)
- [ ] Herding behavior (stick near others)
- [ ] Random head turns when idle
- [ ] Special rare animals with unique traits

---

## 17. Map & UI Polish
- [ ] Add basic minimap
- [ ] Add waypoint system for Outpost
- [ ] Optional: dead animals shown on map

---

## 18. Field Dressing Mini-System
- [ ] "Hold E" to field dress animals
- [ ] Dressing increases trade value

---

## 19. Final Shop Systems
- [ ] Outpost upgrades: better pricing, faster trade
- [ ] Garage shop: vehicle upgrades, GPS, bigger storage

---

## 20. Silly/Fun Content Pass
- [ ] Add funny animals (Ghost Rabbit, Turbo Deer, etc.)
- [ ] Add rare events or hidden easter eggs

---

## 21. Polish Pass 2
- [ ] Add Day/Night cycle
- [ ] Add basic weather (rain impacts gameplay)
- [ ] Improve particle effects: blood, weather, gunfire

---

## 22. Basic Save/Load System
- [ ] Save player money, upgrades, inventory
- [ ] Save owned vehicles

---

# 🏁 Alpha Build = Complete!

---

## 📋 Notes:
- Start with first-person crosshair and simple "Focus Aim."
- Scopes and advanced upgrades build naturally off that foundation.
- Keep each phase simple, functional, and playable.
