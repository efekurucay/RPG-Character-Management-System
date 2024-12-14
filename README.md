# About
This project was created as part of an assignment or coursework for CSE102 Computer Programming. As a first-year Computer Engineering student, I developed this project to enhance my skills in software development and algorithm design.

If you're reviewing this project, your feedback or suggestions would be greatly appreciated. Thank you!

# RPG Character Management System

A comprehensive Role-Playing Game (RPG) character management system implemented in Java, featuring various character classes, combat mechanics, and spell systems.

## Features

- **Multiple Character Classes:**
  - Warrior: Combat-focused class with weapon mastery
  - Cleric: Healing-focused class with spell casting abilities
  - Paladin: Hybrid class combining combat and healing abilities

- **Combat System:**
  - Weapon-based combat mechanics
  - Damage calculation system
  - Health and healing management
  - Battle status tracking

- **Spell System:**
  - Healing spell implementation
  - Spell learning mechanics
  - Mana/resource management

- **Party Management:**
  - Party formation and management
  - Character roles (Fighters, Healers)
  - Party size limitations
  - Party-wide operations

- **Exception Handling:**
  - Custom exceptions for game logic
  - Error handling for invalid operations
  - Party management exceptions

## Technical Details

- **Design Patterns:**
  - Object-Oriented Programming principles
  - Inheritance hierarchy for character classes
  - Interface implementation for different abilities
  - Exception handling for error management

- **Class Structure:**
  - Abstract base classes for common functionality
  - Interface segregation for different abilities
  - Encapsulation of character properties
  - Polymorphic behavior for different character types

## Getting Started

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- Any Java IDE (Eclipse, IntelliJ IDEA, etc.)

### Installation
1. Clone the repository
2. Open the project in your preferred IDE
3. Build and run the project

## Usage Example

```java
// Create a new party
Party adventureParty = new Party();

// Create characters
Warrior warrior = new Warrior("Aragorn");
Cleric cleric = new Cleric("Gandalf");
Paladin paladin = new Paladin("Uther");

// Add characters to party
adventureParty.addCharacter(warrior);
adventureParty.addCharacter(cleric);
adventureParty.addCharacter(paladin);

// Equip weapons and learn spells
warrior.lootWeapon(new Weapon("Sword", 10, 20));
cleric.learnSpell(new Spell("Heal", 20, 30));

// Combat example
warrior.attack(enemy);
cleric.castSpell(warrior); // Heal the warrior
```

## Contributing

Feel free to contribute to this project by:
1. Forking the repository
2. Creating a new feature branch
3. Making your changes
4. Submitting a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Yahya Efe Kuruçay
- Website: [efekurucay.com](https://efekurucay.com)
- Date: December 2023
