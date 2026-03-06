# Common Capture — BRD_VR

## About the Game

* Question and preset-based game
* Focused on **Presets, and custom presets**
* Built as a scalable and structured system
* Designed for expansion (levels, modes, categories, difficulty)

---

## Core Design Philosophy

* Minimal UI
* Fast interactions
* Clean systems
* No clutter
* Focused gameplay loop

---

## Navigation System

* Any preset or level is always unlocked
* No forced progression lock
* Menu-based navigation
* URL parameter loading
* Main presets by BRD_VR explicitly
* Builder is custom a questions system
* Credits page shows the special input commands within it.

---

## Special Input Commands

> These are typed into the **level answer input box**
> These are **navigation & development commands**
> They can **skip levels** and certain things, but use them **whenever**.

### Commands

* **BRDPrev**

  * Move back one level

* **BRDNext**

  * Move forward one level

* **BRDSkip##**

  * Jump directly to a specific level
  * Examples:

    * `BRDSkip5` → Level 5
    * `BRDSkip20` → Level 20
   
* **BRDMovePreset##**

  * Jump directly to a preset AND level
  * Examples:

    * `BRDMoveMath5` → Level 5
    * `BRDMovePreset215` → Level 20

* **BRDBuild**

* Custom Question Model Mode (with custom downloaded presets)
* Make any question set, play it, and save it for reupload later
---

## Developer Notes

* Commands are intended if you want to skip questions.

* Ability to bypass question logic when intentionally used
* Game already allows manual level selection at all times
* Dev commands exist for speed + travel efficiency + fun

---

## Identity

**Project Name:** Common Capture
**Creator:** BRD_VR
**Focus:** Clean structure, scalable design, system-first architecture
**Rights:** I would ask you people not to copy the project or claim it as yours
