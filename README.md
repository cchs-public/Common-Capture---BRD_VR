# Common Capture — BRD_VR

**Current Version:** 4.0.3
**Last Update:** 02/10/2026

---

## About the Game

* Question-based progression game
* Focused on **American history & milestones**
* One-level-at-a-time design
* Built as a **data-driven system** (scalable structure)
* Designed for expansion (levels, modes, categories, difficulty)

---

## Core Design Philosophy

* Minimal UI
* Fast interactions
* Clean progression
* No clutter
* No filler systems
* Focused gameplay loop:

  * Load level
  * Answer question
  * Progress forward

---

## Navigation System

* Level Select always available
* No forced progression lock
* Free level access at all times
* Menu-based navigation
* URL parameter loading
* main presets by BRD_VR explicitly
* Builder is custom questions

---

## Special Input Commands

> These are typed into the **answer input box**
> These are **navigation & development commands only**
> They do NOT count as correct answers

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

* **BRDBuild**

* Custom Question Model Mode
---

## Developer Notes

* Commands are intended if you want to skip questions.

* Does not bypass question logic unless intentionally used
* Game already allows manual level selection at all times
* Dev commands exist for speed + testing efficiency + fun

---

## System Direction

* Modular architecture
* Preset-based level system
* Scalable content design
* Engine-style structure
* Designed for future expansion:

  * Difficulty modes
  * Categories
  * Game modes
  * Time challenges
  * Scoring systems
  * Progress tracking
  * Achievements
  * Save systems

---

## Identity

**Project Name:** Common Capture
**Creator:** BRD_VR
**Focus:** Clean structure, scalable design, system-first architecture
**Rights:** I would ask you people not to copy the project or claim it as yours
