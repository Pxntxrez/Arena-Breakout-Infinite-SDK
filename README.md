# Arena Breakout: Infinite — SDK Dump

Full internal SDK dump for **Arena Breakout: Infinite** (Unreal Engine 4).

## Stats

| | |
|---|---|
| **Game** | Arena Breakout: Infinite |
| **Engine** | Unreal Engine 4 |
| **Date** | 2026-02-22 |
| **Classes** | 5,934 |
| **Structs** | 4,862 |
| **Offsets** | 52,448 |
| **Dump time** | ~32 seconds |

## Files

| File | Description |
|------|-------------|
| `SDK_Dump/Offsets.h` | C++ namespaced offset constants — plug directly into your project |
| `SDK_Dump/SDK_Full.h` | Full class/struct definitions with inheritance, padding, and types |
| `SDK_Dump/offsets_flat.txt` | Flat `Class.Property = 0xOFFSET` list — easy to search and grep |

## Quick reference

```cpp
// Actor
Actor.RootComponent = 0x168;  // SceneComponent*
Actor.Owner = 0x110;          // Actor*
Actor.Instigator = 0x150;     // Pawn*

// Character
Character.Mesh = 0x380;               // SkeletalMeshComponent*
Character.CharacterMovement = 0x388;  // CharacterMovementComponent*
Character.CapsuleComponent = 0x390;   // CapsuleComponent*
Character.bIsCrouched = 0x440;        // uint8_t (bitfield)
```

## Disclaimer

For educational and research purposes only. Use at your own risk.
