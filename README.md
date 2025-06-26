# 🧠 Room Zero

**Room Zero** is a daily Unreal Engine 5.6 escape room project where each level represents one day of learning. The game evolves over time, with new mechanics added daily as the developer progresses.

---

## ✅ Current Progress

* Set up project structure and base folders
* Built Main Menu with Start and Quit buttons
* Created clean game flow:

  * Start Game → loads first level
  * Menu does not persist after level load
* Separated GameModes for menu and gameplay
* Implemented persistent inventory system using `BP_RoomZeroGameInstance`
* Added reusable functions:

  * `AddItemToStash(FInventoryEntry)`
  * `AddItemToLoadout(FInventoryEntry)`
* Key pickup system now stores items directly into stash

---

## 🗂️ Key Components

* `MainMenuLevel` with `GM_MainMenu`
* `Level_01_RoomZero` with `GM_RoomZero`
* `WBP_MainMenu` for UI
* `BP_MainMenuController` handles menu logic
* `BP_RoomZeroGameInstance` manages `StashInventory` and `LoadoutInventory`

---

## 🛠️ Next Up

* Display stash & loadout inventory in UI
* Allow player to select items before entering a level
* Key item → unlocks multi-key door
* Add `RemoveItemFromStash()` logic (optional)
* Dev log popup in main menu
* Level\_02 with first real puzzle (requires inventory use)

---

## 🎯 Goal

A growing escape room game and living journal of daily Unreal progress.

---

Let me know if you want it formatted as a Markdown file or auto-saved into your project folder!
