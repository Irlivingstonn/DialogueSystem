# DialogueSystem

A modified dialogue system for Godot 4 inspired by [this tutorial](https://www.youtube.com/watch?v=CxA7o8ouyHM).  
Unlike the original fixed-screen implementation, this version dynamically positions dialogue boxes relative to the player (or another target node), making it suitable for free-roam games.

<div align="center">

[![GitHub release](https://img.shields.io/github/release/<your-username>/godot_dynamic_dialogue.svg)](https://github.com/<your-username>/godot_dynamic_dialogue/releases)  
[![Code Size](https://img.shields.io/github/languages/code-size/<your-username>/godot_dynamic_dialogue.svg?branch=main)](https://github.com/<your-username>/godot_dynamic_dialogue?branch=main)  
[![Last Commit](https://img.shields.io/github/last-commit/<your-username>/godot_dynamic_dialogue.svg)](https://github.com/<your-username>/godot_dynamic_dialogue/commits/main)  
[![GitHub issues](https://img.shields.io/github/issues/<your-username>/godot_dynamic_dialogue)](https://github.com/<your-username>/godot_dynamic_dialogue/issues)  
[![GitHub pull requests](https://img.shields.io/github/issues-pr/<your-username>/godot_dynamic_dialogue)](https://github.com/<your-username>/godot_dynamic_dialogue/pulls)  
[![Contributors](https://img.shields.io/github/contributors/<your-username>/godot_dynamic_dialogue.svg)](https://github.com/<your-username>/godot_dynamic_dialogue/graphs/contributors)  

</div>

---

## Table of Contents

1. [Features](#features)  
2. [Installation](#installation)  
3. [Usage](#usage)  
4. [Customization](#customization)  
5. [Demo](#demo)  

---

## Features

- Dialogue boxes that follow a target (e.g., player character).  
- Supports multiline dialogue with typewriter effect.  
- Works with free-roam or top-down games.  
- Easy to extend for branching dialogue or NPC interactions.  

---

## Installation

Clone the repository into your Godot project:

```bash
cd ~/GodotProjects/MyGame/addons
git clone https://github.com/<your-username>/godot_dynamic_dialogue.git
