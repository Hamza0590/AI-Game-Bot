# 🕹️ Street Fighter II - AI GameBot (MLP-Based)

This project is a partial implementation of an **AI GameBot** for **Street Fighter II**, powered by a **Multi-Layer Perceptron (MLP)** model. The AI is trained to predict game actions based on previous game states and simulate real-time decision-making during gameplay.

> ⚠️ **Important:** This ZIP archive **will not run the game on its own**. It contains only the **core AI logic and support files**, not the full game environment.

---

## 📦 What's Included in the ZIP?

* `mlp_model.py`
  Contains the MLP model architecture used to predict actions from game states.

* `controller.py`
  Handles the mapping between the model’s output and actual game controls (e.g., jump, punch, move left/right).

* `button.py`
  Defines the key mappings used to simulate player actions in the game.

* `game_states.csv`
  A dataset of recorded game states used for training and evaluating the AI model.

---

## 🤖 What Does This AI Do?

* It uses game state data (from `game_states.csv`) to predict the next best move in the game.
* The MLP model processes input features from the CSV and outputs an action.
* The `controller.py` module maps these actions to button presses.
* When integrated properly with a game environment, it can **play Street Fighter II autonomously**.

---

## 🕹️ Emulator Information

The game is intended to be run using the **BizHawk emulator**. However, **BizHawk, ROM files, and actual game integration are not included in this ZIP** due to size and licensing constraints.

To run the complete system, you would need:

* BizHawk emulator properly set up.
* Lua scripts to extract live game state and inject controller inputs.
* The game ROM (not provided).

---

## ⚠️ Limitations

* This ZIP is not a standalone runnable project.
* No emulator, ROM, or Lua integration scripts are included.
* It is meant for educational or development purposes, demonstrating how AI can be trained on game data.

---

## 💡 Use Cases

* Study how neural networks can interact with retro games.
* Use the dataset and model as a starting point for your own reinforcement learning experiments.
* Learn how to connect ML models with emulated game environments.

---

## 📁 File Size Note

The full project (including videos, emulation data, and environment scripts) exceeded **GitHub’s 100 MB size limit**. This ZIP contains only the core components necessary to demonstrate the AI model and its interaction logic.

---
