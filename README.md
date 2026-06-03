# Diy-Gaming-sim
## Features

- 🎮 XInput (Xbox Controller) support
- 🛞 Analog steering wheel
- 🚗 Accelerator pedal (RT)
- 🛑 Brake pedal (LT)
- ✋ Handbrake (LB)
- 🔘 Additional button (RB)
- ⚙️ Sequential shifter
- 🦶 Internal clutch logic
- 🎯 Steering smoothing
- 🎮 Works with games that do not support a separate clutch input

## Internal Clutch System

The wheel uses an internal clutch system.

Instead of sending the clutch as a separate controller button, the firmware checks whether the clutch pedal is pressed before allowing a shift.

This provides:

- Cleaner controller mapping
- Compatibility with games that lack clutch support
- Prevention of accidental shifts
- More realistic sequential shifting

### Shift Logic

- Clutch pressed + shifter forward → Shift Up (L3)
- Clutch pressed + shifter backward → Shift Down (R3)
- No clutch → Shift commands ignored
