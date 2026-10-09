# Pandas Turn-Based Battle RPG (Prototype)

This is a simple turn-based battle RPG built with Python and Pandas. 
I developed this project to practice data management using Pandas DataFrames.

## Features
- Manage player and enemy stats using Pandas DataFrames (`pd.DataFrame`).
- Target selection system using index numbers.
- Dynamic health points (HP) calculation.

## How to Play
1. Run the script in your Python environment (like Google Colab).
2. Enter `1` to start your turn.
3. Choose your target: Enter `1` for Goblin or `2` for Slime.

## Code Example
Here is how the game calculates damage using Pandas:
```python
damage = df.loc[0, "ATK"]
edf.loc[a, "hp"] = edf.loc[a, "hp"] - damage
```

## Future Plans (Roadmap)
* Add enemy counter-attacks (Turn loop). ✅️
* Add skills and MP system.
* Drop defeated enemies from the DataFrame. ✅️
