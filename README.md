# Basic Spell Casting System

## Objective

Create a simple spell casting system in C++ that uses enums to represent different spells and type conversion to manage spell effects. This project will test your understanding of enums, type conversion, and conditionals.

## Requirements

### Spell Casting System

The program should:
- Use an enum to represent different spell types (e.g., Fireball, Ice Spike, Heal).
- Use variables to store the player's name, health, and mana.
- Use conditionals and type conversion to handle the effects of casting different spells.
- Display the results of the spell casting based on the chosen spell.

### Input Details

The program should collect the following inputs:
- Player's name (string)
- Spell choice (enum): Fireball, Ice Spike, Heal

### Output

The program should display the player's name, health, mana, and the result of the spell cast.

## Steps

### 1. Set Up Project

- Create a new C++ project and set up your development environment.
- Include necessary headers (`<iostream>`, `<string>`).

### 2. Define Enums and Variables

- Define an enum for spell types.
- Define variables for the player's name, health, and mana.

### 3. Prompt User for Input

- Use `std::cin` to collect the player's name.
- Use `std::cin` to collect the player's spell choice and cast it to the corresponding enum value.

### 4. Handle Spell Effects

- Use conditionals (`if`, `else if`, `else`) to apply the effects of the chosen spell on the player's health and mana.
- Use type conversion if necessary to manage the spell effects.

### 5. Display Results

- Display the player's name, health, mana, and the result of the spell cast.

## Example User Interaction

```plaintext
Enter your character's name: Merlin
Choose your spell (1: Fireball, 2: Ice Spike, 3: Heal): 1
Merlin casts Fireball!
Health: 100
Mana: 70
Result: A blazing fireball erupts, dealing massive damage to the enemy.
```
## Submission Details

### 1. Complete the project and ensure it is bug-free.

### 2. Add the completed project to your GitHub repository.

### 3. Submit the link to your repository through your program dashboard to continue the program.

### 4. A code review will be processed once the submission is received.
