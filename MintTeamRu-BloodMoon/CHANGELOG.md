# Changelog

## [1.0.0] – Initial Release

### Added
- Blood Moon world event.
- Configurable event cycle (every 5 days).
- Blood-red atmospheric visuals (moon, fog, sky, ambient).
- Temporary +1 star bonus for enemies during the Blood Moon.
- Automatic star removal at dawn.
- Safe revert for enemies that were unloaded during the night.
- Increased enemy spawn rate during the event.
- Controlled enemy duplication (non-recursive).

### Balance & Safety
- Excluded dangerous and special creatures:
  - Lox
  - Deathsquito
  - Hen / Chicken
  - Wolf
  - Boar
- All tamed creatures are excluded from buffs and duplication.
- Prevented star stacking across multiple Blood Moons.
- Prevented uncontrolled mob multiplication.

### Technical
- Server-authoritative logic with client synchronization.
- Minimal performance impact.
- Safe handling of world streaming and entity loading/unloading.

---
