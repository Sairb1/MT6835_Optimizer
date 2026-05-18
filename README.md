<div align="center">

# 🌡️ MT6835 Optimizer

### Optimize Heat & Battery Life for MediaTek Dimensity 6100+ / 6300 / 6400

<img src="https://img.shields.io/badge/MT6835-Optimizer-blueviolet?style=for-the-badge&logo=android"/>
<br/>
<img src="https://img.shields.io/badge/Chipset-Dimensity%206100%2B%20%7C%206300%20%7C%206400-brightgreen?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Root-Magisk%20%7C%20KernelSU%20%7C%20APatch-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Android-11%2B-red?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Telegram-colorosmodules-229ED9?style=for-the-badge&logo=telegram"/>

<br/>

### Premium thermal & battery optimization module for MT6835 devices

Made with ♥ by **[Ayan (@imnotaino)](https://t.me/imnotaino)**  
Updates & Support → **[t.me/colorosmodules](https://t.me/colorosmodules)**

</div>

---

# 📖 What is this?

**MT6835 Optimizer** is a specialized Magisk/APatch/KernelSU module engineered specifically for the:

- MediaTek Dimensity 6100+
- MediaTek Dimensity 6300
- MediaTek Dimensity 6400

based on the **MT6835 platform**.

Unlike Snapdragon platforms, MT6835 devices use heavily restricted voltage tables hardcoded directly into the kernel and DVFS framework.

That means:
- traditional undervolting doesn't work
- sysfs voltage editing is blocked
- kernel-level voltage scaling is inaccessible on stock kernels

So instead of fake "undervolting tweaks", this module optimizes the actual thermal behavior properly by tuning:
- CPU governor response
- frequency ramp timings
- MediaTek GED boost behavior
- scheduler aggressiveness

Result:
- lower temperatures
- reduced throttling
- smoother sustained performance
- improved battery life
- less aggressive thermal spikes

without sacrificing peak performance.

---

# ✨ Features

## ⚡ Advanced Governor Optimization

Tunes:
```bash
sugov_ext
```

rate limits for smoother CPU scaling behavior.

### Applied Values

| Parameter | Value |
|---|---|
| Up Rate Limit | `4000us` |
| Down Rate Limit | `500us` |

### Why this matters

Stock MT6835 governor behavior ramps frequencies aggressively and stays boosted longer than necessary.

This module:
- smooths voltage ramp-up
- reduces sudden thermal spikes
- drops frequencies back to idle faster
- improves sustained efficiency

Result:
- cooler device
- less random heating
- better idle behavior

---

# 🚫 MediaTek GED Boost Disabler

Disables aggressive MediaTek GPU/CPU boosting logic:

```bash
ged_boost_enable
boost_gpu_enable
ged_smart_boost
```

These boosts artificially spike frequencies during:
- scrolling
- launcher animations
- light UI interaction

which wastes battery and creates unnecessary heat.

This module safely disables them while preserving real workload performance.

---

# 📱 Interactive Magisk Action Button

Integrated:
```bash
action.sh
```

support allows you to:
- instantly re-apply optimizations
- refresh governor tuning
- monitor live CPU temperatures

directly inside the Magisk app.

No reboot needed.

---

# ⚡ Premium Flashing Experience

Includes a fully customized flashing terminal UI featuring:
- animated typewriter output
- live device information
- Android version detection
- kernel information
- battery percentage
- codename parsing

during installation.

---

# 📸 Flash Preview

```text
╔══════════════════════════════════════╗
║          MT6835 Optimizer            ║
║      Thermal & Battery Tuning        ║
╚══════════════════════════════════════╝

  Developer : Ayan (@imnotaino)
  Channel   : t.me/colorosmodules

  Flash Time : 2026-05-18 15:42:11

──────────────────────────────────────
          ★  Device  Info  ★
──────────────────────────────────────
  Device  : realme Narzo 60x
  Codename: ossi
  Android : 15  (SDK 35)
  Build   : RMX3782_15.0.0.xxx
  Kernel  : 5.15.x
  Battery : 82%
──────────────────────────────────────

  ► Initialising optimization engine...
  ► Verifying MT6835 platform...
  ► Applying governor tuning...
  ► Disabling GED boost layers...
  ► Optimizing scheduler response...
  ► Setting thermal balance profile...
  ► Finalizing runtime configuration...

══════════════════════════════════════
      ✓ MT6835 Optimizer Ready!
══════════════════════════════════════

  ➤  t.me/colorosmodules

  Made with ♥ by Ayan (@imnotaino)
```

---

# 📦 What the module modifies

The module dynamically tunes:
- CPU governor rate limits
- GED boost parameters
- scheduler responsiveness
- runtime thermal behavior

without:
- kernel patching
- boot image modification
- partition editing

Everything remains:
- system-less
- OTA safe
- fully reversible

---

# 📋 Compatibility

| Component | Support |
|---|---|
| Chipset | MT6835 |
| SoC | Dimensity 6100+ / 6300 / 6400 |
| Root | Magisk / KernelSU / APatch |
| Android | Android 11+ |

---

# 📥 Installation

1. Download latest:
```text
MT6835_Optimizer.zip
```

2. Flash via:
- Magisk
- KernelSU
- APatch

3. Reboot device

4. Enjoy cooler temperatures & improved battery life ⚡

---

# ❓ FAQ

## Q: Does this undervolt the CPU?
No.

MT6835 stock kernels block direct undervolting.

This module optimizes governor behavior instead.

---

## Q: Will performance decrease?
No.

Peak performance remains intact.

The module mainly reduces unnecessary aggressive boosting behavior.

---

## Q: Does this reduce heating?
Yes.

Especially during:
- idle
- scrolling
- social media usage
- light gaming
- standby

---

## Q: Is this safe?
Yes.

No kernel patching or partition modification is performed.

---

## Q: Can I uninstall anytime?
Yes.

Disable/remove module and reboot.

Everything reverts automatically.

---

# 👑 Credits

| Role | Name |
|---|---|
| Developer | Ayan (@imnotaino) |
| Platform | MediaTek MT6835 |
| Framework | Magisk / KernelSU / APatch |

---

# 📢 Telegram Channel

### 👉 https://t.me/colorosmodules

---

<div align="center">

## ⚡ Optimized for efficiency. Built for MT6835.

Made with ♥ by Ayan

</div>
