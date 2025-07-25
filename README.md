# 🧾 Client Documentation

Welcome to your client's documentation. This document provides a complete overview of all available modules, features, and configuration options.

---

## 🧩 Legend

- **[PREMIUM]**: Indicates a feature reserved for Premium users.
- Features without the [PREMIUM] tag are available in the free version, but may have limited customization.

---

## 📚 Table of Contents

- [⚔️ Combat](#️combat)
- [🎯 Advanced Combat](#advanced-combat)
- [🏃 Movement](#movement)
- [🧰 Utilities](#utilities)
- [🎨 Configuration & Visuals](#configuration--visuals)

---

## ⚔️ Combat

### 🎯 Aim Assist

- `Enable Aim Assist`: Toggle the module on or off.
- `Aim Assist Keybind`: Set the key to activate Aim Assist.
- `On Click Only`: Only activate when clicking.
- `Click Aim Duration`: How long Aim Assist remains active when clicking.
- `Field of View`: The FOV (in degrees) for detecting targets.

**[PREMIUM] Options:**
- `Bypass Antibot`: Only targets moving entities.
- `Smart Tracking`: Attempts to choose the correct enemy.
  - `Minimal Lock Duration`: Minimum lock-on time.
- `Prediction`: Predicts enemy movement for more accurate aiming.
- `Pearl Aimbot`: Instantly aims at the nearest enemy after throwing a pearl.
  - `Pearl Range`: Range for detecting targets post-throw.
  - `Movement Threshold`: Player motion needed to trigger.
- `Predictive Pearl Aimbot (ALPHA)`:
  - `Pearl Slot`: Inventory slot of the Ender Pearl.
  - `Max Distance`: Max distance between player and pearl landing.
  - `Max Distance from Enemy at Landing`: Max enemy distance from pearl landing.
- `Auto Pearl (WIP)`: Automatically throws a pearl when needed.
- `Smart Aim`: Simulates human-like movement for bypassing anti-cheats.
- `Only Slot`: Only works when holding a specific item slot.
- `Priority Choice`: Choose how targets are prioritized (distance, health...).
- `Point Choice`: Choose what part of the body to aim at (head, torso...).
- `Break Blocks`: Stops aiming when a block is between you and the target.
- `Customization Sliders`:
  - `Minimum Aim Interval`: Minimum time between aim corrections.
  - `Horizontal/Vertical Force`: Aim strength per axis.
  - `Precision`: Lower value = more accurate.
  - `Max/Min Distance`: Distance range of the Aim Assist.
  - `Acceleration`: Aim acceleration speed.
  - `Randomization`: Adds randomness to aiming.
- `Entity Number`: Number of entities scanned per tick.
- `Travel Entity List Backward`: Reverse scan order.
- `Enable Epsilon`: Special anti-bot bypass method.

---

### 🖱️ TriggerBot

- `Enable TriggerBot`: Toggle on/off.
- `Min/Max Clicks Per Second`: CPS range.
- `TriggerBot Keybind`: Activation key.
- `TriggerBot Reaction Time`: Delay before first hit.

**[PREMIUM] Options:**
- `Hit Select`: Only triggers after being hit.
  - `Trade Duration`: Time active after being hit.
  - `Enable Distance`: Distance threshold from enemy.
- `One Tap`: Automatically performs a one-tap.
  - `One Tap Distance`: Vertical trigger range.
  - `One Tap Duration`: Time between attacks.
  - `Fast One Tap`: Increases chance of successful one-taps.

---

## 🔪 Advanced Combat

### 🧻 Reach

- `Enable Reach`: Toggle reach extension.
- `Reach Keybind`: Activation key.
- `Only Ground`: Only activates while on ground.
- `Only Moving`: Requires movement.
- `Only Slot`: Only activates for certain item slots.
- `Min/Max Reach`: Range bounds.

**[PREMIUM] Options:**
- `Silent Reach`: Only activates during hurt time.
- `Reach Anticheat Bypass`: Tries to bypass server checks *(experimental)*.

---

### 🟥 Hitbox

- `Enable Hitbox`: Toggle the module.
- `Horizontal/Vertical Hitbox Value`: Change hitbox size by axis.

---

### 🧲 Misplace

- `Enable Misplace`: Toggle on/off.
- `Only On Click`: Only pulls entities when clicking.
- `Reverse Misplace`: Pushes entities instead of pulling them.
- `Range`: Start range for pulling.
- `Pull Distance`: How far to pull entities.
- `Sleep Time`: Delay between updates.

---

## 🏃 Movement

### 🪂 Velocity

- `Enable Velocity`: Toggle knockback reduction.
- `Only On Click / Ground / Targeting`: Conditional activation.
- `Min/Max Vertical/Horizontal`: Knockback reduction percentages.

**[PREMIUM]**: `Bypass Server AC`

---

### 🦘 Auto Jump Reset

- `Enable Auto Jump Reset`: Toggle on/off.
- `Mode`: Choose between `Input` (fast) and `Internal` (stable).

**[PREMIUM] Full Customization:**
- `Jump Delay`
- `Ignore First Hit`
- `Not Legit Jump Reset`
- `Spam Jump`

---

### 🏃‍♂️ Other Movement Modules

- `Speed Hack`: Increases movement speed.
- `Boost`: Dash in camera direction.
- `Timer`: Modify global game speed.
  - **[PREMIUM]**: `Timer AC Bypass`
- `Auto S Tap`: Automatic backward tapping.
- `W Tap`: Repositions forward after hits.
- `Auto Sprint`: Always sprint.
- `Counter Strafe`: Auto-strafe after being hit.
- `Fly`: Enables flight.

---

## 🧰 Utilities

### 🌀 Blink **[PREMIUM]**

- `Blink Key`: Activation key.
- `Duration`: Time during which packets are blocked.
- `Min/Max Interval`: Automatic blink frequency.

---

### 🖱️ Clicker

- `Toggle Clicker / Right Clicker`: Left/right click automation.
- `Priming`: Activates only when both buttons are held.
- `Min/Max CPS`: Clicks per second.
- `Avoid Menu`: Disable in menus.
- `Rapid Mode`: Temporarily boosts CPS after being hit.

---

### 🧩 Other Utility Features

- `Auto 360`: Instantly performs a 360° turn.
- `No Hurt Cam`: Removes screen shake on damage.
- `Fullbright`: Makes the world fully lit.
- `No Teleport Rotation`: Prevents camera rotation after teleport.
- `No Item Use Delay`: Removes item delay.
- `No Jump Delay`: Removes jump cooldown.

**[PREMIUM]**
- `Health Threshold`: Enables features only when low on health.
- `MiddleClick Friend System`: Add friends to whitelist (middle click).

---

## 🎨 Configuration & Visuals

- `Color Customization`: Change menu and module colors.
- `Rounding`: Adjust corner radius of the GUI.
- `Animation Speed`: Speed of UI transitions.
- `DPI Scale`: UI scaling for high-resolution screens.

**Options:**
- `Hide/Show Keybind`: Toggle menu visibility.
- `Config Management`: Save/load configurations.
- `Eject`: Safely remove the client from memory.
- `Stream Mode`: Hide GUI in OBS or recording.
- `Reverse Mouse Buttons`: Left-handed compatibility.

---

