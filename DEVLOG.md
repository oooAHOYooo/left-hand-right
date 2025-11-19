# Development Log - LHR_REBOOT

## Version Tracking

### Current Version: v0.1.0 (Initial Documentation)

**Date:** 2024-12-19  
**Engine:** Unreal Engine 5.6

---

## Version History

### v0.1.0 - Initial Documentation
- Created README.md and DEVLOG.md
- Documented project structure
- Identified core game mechanics:
  - Good/Bad tree system
  - Seed projectile mechanics
  - Animal AI system
  - Growth stone mechanics
  - Character and HUD systems

---

## Development Notes

### Core Systems

#### Tree System
- **BP_GoodTree** - Good tree blueprint
- **BP_GoodTree1** - Alternative good tree variant
- **BP_BadTree** - Bad tree blueprint

#### Projectile System
- **BP_GoodSeedProjecticle** - Good seed projectile
- **BP_BadSeed_Projectile** - Bad seed projectile

#### AI System
- **BP_Animal** - Base animal blueprint
- **Bad_Character_AI** - Bad character AI implementation

#### Other Systems
- **BP_GrowthStone** - Growth stone mechanic
- **BP_BadSpawner** - Bad entity spawner
- **LHR_CharacterBP** - Main character blueprint
- **WeaponData** - Weapon data asset

### UI/HUD
- **WBP_MainMenu** - Main menu widget
- **WBP_StatsHud** - Stats display HUD
- **WBP_TimerHud** - Timer display HUD

### Maps
- **LHR_DevMap** - Primary development map
- **LHR_SimpleMap** - Simple test map (default)
- **L_LHR_Ring3_FogTrees** - Ring map variant

### Input System
- Enhanced Input system configured
- Default and Mouse Look input mapping contexts
- Touch input support

---

## Version Check

To verify you're on the correct version:
1. Check this DEVLOG.md file
2. Verify Unreal Engine version matches 5.6
3. Check project file: `LHR_REBOOT.uproject` should show EngineAssociation: "5.6"

---

## Next Steps

- [ ] Define version numbering scheme
- [ ] Set up proper version tags in git
- [ ] Document major feature implementations
- [ ] Track bug fixes and improvements

---

## Notes

- Project uses Unreal Engine 5.6
- Split-screen support enabled (2-3 player)
- Lumen global illumination enabled
- Virtual shadow maps enabled
- Project uses Enhanced Input system

