# ShadowClash

**ShadowClash** is a **tactical fighting** video game set in a **dark fantasy** world, where legendary creatures clash in **strategic duels**. Players must master unique skills, manage their resources, and make tactical decisions to defeat their opponents.

WARNING: Make sure your environment and dependencies are correctly configured to avoid issues while running the game.

---

## 📑 Table of Contents

- [Features](#-features)
- [Gameplay Mechanics](#-gameplay-mechanics)
- [Roles](#-roles)
- [Skills and Attributes System](#-skills-and-attributes-system)
- [Installation and Configuration](#-installation-and-configuration)
- [Execution](#-execution)
- [Testing](#-testing)
- [Documentation](#-documentation)
- [FAQ](#-faq)

---

## 🏆 Features

- **Character Management**: Create and customize your characters with attributes, skills, and equipment.
- **Challenge System**: Challenge other players, bet gold, and set up your equipment before each battle.
- **Round-based Combat**: Battles take place in rounds where every action influences the outcome.
- **Persistence**: All information is saved persistently, allowing you to continue your progress without losing data.

---

## 🕹️ Gameplay Mechanics

- **Tactical Combat**: Face your enemies in **round-based combat** where every action counts.
    - **Attack Phase**: The character attempts to deal damage to the opponent using their attack and skills.
    - **Defense Phase**: The opponent attempts to block or mitigate the damage using their defense and skills.

- **Objective**: Reduce the opponent's health to zero before they do the same to you.

---

## 🛠️ Roles

- **Administrator**: Manages the database, characters, weapons, armor, and game settings.
- **Player**: Creates and manages their character, participates in battles and challenges.

---

## ⚔️ Skills and Attributes System

Each character has skills and attributes that affect their performance in combat:

### Attributes:

- **Health (HP)**: The character's life. If it reaches 0, the character loses.
- **Attack**: Determines the damage the character can deal.
- **Defense**: Reduces incoming damage.
- **Speed**: Influences the turn order of actions.

### Skills:

- **Special Skills**: Each race has unique skills that alter the course of the battle.
- **Passive Skills**: Continuously affect the character, such as resisting poison or increasing critical hit chance.

---

## ⚙️ Installation and Configuration

1. **Clone the repository**:
    ```bash
    git clone [https://github.com/your-username/ShadowClash.git](https://github.com/your-username/ShadowClash.git)
    ```

2. **Navigate to the project directory**:
    ```bash
    cd ShadowClash
    ```
![imagen](https://github.com/user-attachments/assets/bc718729-9db8-4d6f-9bda-4729fd29db5e)

3. **Configure the environment**:
    - Make sure you have the **proper environment** to run the project (game engine, dependencies, etc.).
    - Adjust the necessary settings in the configuration files.

![imagen](https://github.com/user-attachments/assets/f8aab5ba-df91-4f7f-a726-9c5462a1e3cd)

---

## ▶️ Execution

1. **Run the application**:
    - Open the project in the game engine and run the main method to start the game.

---

## ✅ Testing

Unit tests have been implemented to verify the correct functionality of:

- **Character and attribute management**.
- **Combat logic**.
- **Data persistence**.

---

## 📚 Documentation

Technical documentation is integrated into the source code. It is recommended to check the comments and internal documentation to better understand how the system works.

---

## ❓ FAQ

**How do I create a character?** Select "Create Character" from the main menu and customize attributes, skills, and equipment.

**What races can I choose?** You can choose between **Vampires**, **Werewolves**, and **Hunters**, each with unique skills.

**How do I challenge another player?** From the main menu, select "Challenge another player" and bet gold before the fight.

**How many rounds does a battle have?** Each battle has multiple rounds, continuing until one of the characters loses all their health.

**Can I upgrade my character's skills?** Yes, skills improve as you level up by winning battles.

**How does betting work?** You can bet gold before each fight, and the winner takes all the bet gold.

---

**ShadowClash**: Conquer the darkness and forge your legend. The fight is about to begin! 💥
