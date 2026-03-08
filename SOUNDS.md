# Moonbird Arena Shooter - Sound Effects Documentation

Complete sound package for the HTML5 Canvas mobile arena shooter game.

## Overview

- **Total Sounds**: 25 sound effects
- **Format**: WAV files (mono, 22.05kHz or 44.1kHz)
- **Size**: ~800KB total (significantly reduced from previous 1.4MB)
- **All sounds are legally usable commercially**

## Recent Updates (March 7, 2026)

**Replaced 8 sound effects for better quality and smaller file sizes:**

1. **kill-sound.wav**: 220KB → 10KB (22x smaller)
2. **skully-activate.wav**: 14KB → 100KB (higher quality spooky effect)
3. **halo-activate.wav**: 2KB → 129KB (real healing/angelic sound)
4. **rampage-stinger.wav**: 28KB → 55KB (professional hit stinger)
5. **unstoppable-stinger.wav**: 24KB → 24KB (different dramatic stinger)
6. **godlike-stinger.wav**: 10KB → 24KB (more epic stinger)
7. **legendary-stinger.wav**: 11KB → 25KB (ultimate dramatic stinger)
8. **enemy-whoosh.wav**: 220KB → 35KB (6x smaller, trimmed wind effect)

## Sound Sources & Licensing

### jsfxr Generated Sounds (CC0)
Generated using the `jsfxr` npm package with built-in presets. All CC0 public domain.

1. **laser-shoot.wav** (2KB)
   - Source: jsfxr preset "laserShoot"
   - Usage: Primary weapon firing sound (repeats every 200ms)
   - Notes: Quiet and subtle to avoid annoyance

2. **combo-ping.wav** (23KB)  
   - Source: jsfxr preset "powerUp"
   - Usage: Combo multiplier increment sound (x2, x3, etc.)
   - Notes: Rising pitch indicates progression

3. **crown-collect.wav** (4KB)
   - Source: jsfxr preset "pickupCoin" 
   - Usage: +500 score collection sound
   - Notes: Classic coin/cha-ching effect

4. **powerup-collect.wav** (3KB)
   - Source: jsfxr preset "powerUp"
   - Usage: General powerup collection
   - Notes: Bright and rewarding

5. **game-start.wav** (15KB)
   - Source: jsfxr preset "jump"
   - Usage: Game session start sound
   - Notes: Energetic and upbeat

6. **menu-tap.wav** (8KB)
   - Source: jsfxr preset "blipSelect"
   - Usage: UI button/menu interactions
   - Notes: Clean and responsive

7. **powerup-expire.wav** (2KB)
   - Source: jsfxr preset "hitHurt" 
   - Usage: When powerup effects wear off
   - Notes: Descending tone for negative feedback

### Kenney Asset Sounds (CC0)
From Kenney.nl asset packs: Sci-fi Sounds, Impact Sounds, Music Jingles. All CC0 licensed.

8. **player-hit.wav** (30KB)
   - Source: Kenney `impactMetal_001.ogg`
   - Usage: Player taking damage
   - License: CC0
   - Notes: Processed with ffmpeg for consistency

9. **player-death.wav** (54KB)
   - Source: Kenney `explosionCrunch_002.ogg`
   - Usage: Player death/game over
   - License: CC0

10. **enemy-hit.wav** (27KB)
    - Source: Kenney `impactMetal_000.ogg` 
    - Usage: Confirming enemy hit
    - License: CC0

11. **enemy-death.wav** (58KB)
    - Source: Kenney `explosionCrunch_001.ogg`
    - Usage: Enemy destruction sound
    - License: CC0

12. **enemy-whoosh.wav** (35KB) *NEW*
    - Source: ViRiX Dreamcore "Wind effects 5.wav" (trimmed to 0.4s)
    - Usage: Fire trail or charging enemy movement
    - License: CC0 (via OpenGameArt Magic SFX Sample)
    - Notes: Much shorter and lighter than previous Kenney thruster sound

13. **powerup-spawn.wav** (41KB)
    - Source: Kenney `forceField_000.ogg`
    - Usage: When powerups appear on screen
    - License: CC0

14. **chromie-shockwave.wav** (43KB)
    - Source: Kenney `lowFrequency_explosion_001.ogg`
    - Usage: Rainbow wave kill-all explosion
    - License: CC0

15. **flame-activate.wav** (215KB)
    - Source: Kenney `thrusterFire_002.ogg`
    - Usage: Fire powerup activation
    - License: CC0

16. **raincloud-activate.wav** (215KB)
    - Source: Kenney `spaceEngineLow_002.ogg`
    - Usage: Rain cloud powerup activation 
    - License: CC0

17. **game-over.wav** (86KB)
    - Source: Kenney `lowFrequency_explosion_000.ogg`
    - Usage: Final defeat/game over screen
    - License: CC0

18. **kill-sound.wav** (10KB) *NEW*
    - Source: Kenney Impact Sounds `impactGeneric_light_001.ogg`
    - Usage: Quick kill confirmation tick (0.12 seconds)
    - License: CC0
    - Notes: Perfect punchy tick, 22x smaller than old computerNoise

19. **rampage-stinger.wav** (55KB) *NEW*
    - Source: Kenney Music Jingles `jingles_HIT04.ogg`
    - Usage: RAMPAGE combo callout stinger (0.64s)
    - License: CC0

20. **unstoppable-stinger.wav** (24KB) *NEW*
    - Source: Kenney Music Jingles `jingles_HIT08.ogg`
    - Usage: UNSTOPPABLE combo callout stinger (0.28s)
    - License: CC0

21. **godlike-stinger.wav** (24KB) *NEW*
    - Source: Kenney Music Jingles `jingles_HIT12.ogg`
    - Usage: GODLIKE combo callout stinger (0.27s)
    - License: CC0

22. **legendary-stinger.wav** (25KB) *NEW*
    - Source: Kenney Music Jingles `jingles_HIT16.ogg`
    - Usage: LEGENDARY combo callout stinger (0.29s)
    - License: CC0

### External Sources

23. **duck-quack.wav** (43KB)
    - Source: Free Sounds Library
    - URL: https://www.freesoundslibrary.com/duck-quack/
    - License: CC BY 4.0
    - Usage: Duck powerup activation and "QUACK!" text
    - Notes: Trimmed to 1 second, processed for consistency

24. **skully-activate.wav** (100KB) *NEW*
    - Source: AntumDeluge "Witch Cackle" via OpenGameArt.org
    - URL: https://opengameart.org/content/witch-cackle
    - License: CC0
    - Usage: Dark/spooky skull powerup activation (1.16s)
    - Notes: Perfect evil cackle for skull activation

25. **halo-activate.wav** (129KB) *NEW*
    - Source: ViRiX Dreamcore "Healing Full.wav" (trimmed to 1.5s)
    - URL: https://opengameart.org/content/magic-sfx-sample
    - License: CC0
    - Usage: Heavenly/angelic halo powerup activation
    - Notes: Ethereal healing sound, much better than jsfxr placeholder

## Stinger Progression

The combo stingers now have proper dramatic progression using Kenney's Hit Jingles:
- **Rampage**: Professional hit stinger (0.64s)
- **Unstoppable**: Shorter but more intense (0.28s)
- **Godlike**: Similar length, different tone (0.27s)
- **Legendary**: Ultimate finale stinger (0.29s)

Each uses different Kenney Hit Jingles to create variety while maintaining dramatic escalation.

## Technical Processing

- All new sounds processed using ffmpeg for mono conversion and normalization
- Volume levels adjusted to approximately 70-80% to prevent clipping
- Converted to mono WAV format for mobile optimization
- Sample rates: 22.05kHz for small sounds, 44.1kHz for complex sounds
- Total package size significantly reduced while improving audio quality

## Implementation Notes

- **kill-sound.wav** is THE most critical sound - fires every 200ms, now much lighter
- **enemy-whoosh.wav** is 6x smaller, perfect for mobile performance
- Combo stingers use professional musical hits instead of explosion placeholders
- **skully-activate.wav** has genuine spooky character with evil cackle
- **halo-activate.wav** provides proper ethereal/healing feel
- All sounds tested for mobile compatibility
- File sizes optimized for fast loading on mobile devices

## Generation Scripts

- `generate-sfx.js` - Creates jsfxr sounds
- `copy-kenney-sounds.js` - Processes Kenney pack sounds
- `generate-specialty-sfx.js` - Creates placeholder specialty sounds

## Audio Packs Used

1. **Kenney Impact Sounds** - https://kenney.nl/assets/impact-sounds (130 assets, CC0)
2. **Kenney Music Jingles** - https://kenney.nl/assets/music-jingles (85 assets, CC0)
3. **ViRiX Dreamcore Magic SFX** - https://opengameart.org/content/magic-sfx-sample (CC0)
4. **OpenGameArt CC0 Collection** - Various artists, CC0 licensed

---

*Updated on March 7, 2026 for Moonbird Arena Shooter*  
*All sounds cleared for commercial use*  
*Total package size reduced by ~600KB while improving audio quality*