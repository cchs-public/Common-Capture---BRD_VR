# Common Capture — BRD_VR

**Current Version:** 3.5.1
**Last Update:** 2/5/2026

---

## About the Game

* Question-based progression game
* Focused on **American history & milestones**
* Linear progression system
* Starts at **Christopher Columbus (1492)**
* Ends at **first iPhone release (2007)**
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
* URL parameter loading (`?l=` system)

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

  * Custom Question Model Option
---

## Developer Notes

* Commands are intended for:

  * Testing
  * Navigation
  * Debugging
  * Development flow
* Does not bypass question logic unless intentionally used
* Game already allows manual level selection at all times
* Dev commands exist for speed + testing efficiency

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
