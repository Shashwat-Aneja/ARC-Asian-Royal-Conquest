# Gameplay Systems — ARC

## 1. Player Controller
- Third-person movement using Unreal’s Character class.
- Sprint, jump, crouch.
- Smooth camera orbit and collision.

## 2. Combat System
- Light attack combo chain (3-hit)
- Heavy attack (high damage, slow)
- Dodge roll
- Hit detection via animation notifies
- Damage interface for enemies

## 3. AI System
- Enemy types: Soldier, Archer, Scout
- Behavior Tree for:
  - Patrol
  - Chase
  - Attack
  - Retreat
- Perception Component for sight & hearing

## 4. World Systems
- Time-of-day cycle
- Weather variations
- Spawning wildlife
- Resource pickups

## 5. Inventory System
- Weapons
- Herbs
- Crafting materials
- Basic UI elements

## 6. Quest System
- Simple objective-based quests
- “Talk → Explore → Defeat → Return” loops
