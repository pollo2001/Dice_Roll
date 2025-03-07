# **Dice Roll Simulator - ARM Assembly 🎲**

This project simulates **100 random dice rolls**, detects **runs** of consecutive identical values, and counts the total number of runs. Written in **ARM assembly**, it includes functions for **random dice roll generation** and **run detection**.

---

## **Included Files 📁**

- **`main.s`**: Generates dice rolls, stores them, and calls `count_run`.
- **`count_run.s`**: Detects runs of consecutive identical dice rolls and prints their lengths and total occurrences.
- **`roll_dice.s`**: Generates random dice rolls and stores them in an array.
- **`mod.s`**: Calculates the **modulo** to constrain rolls between 1 and 6.
- **`play_dice.s`**: Main function, initializes memory, seeds random number generator, and calls `roll_dice` and `count_run`.
- **`Makefile`**: Compiles and links the assembly files into an executable.

---

## **How It Works 🚀**

1. **Random Dice Rolls**: The `roll_dice` function generates random dice rolls (1-6) and stores them.
2. **Run Detection**: The `count_run` function detects consecutive identical dice rolls and counts the total number of runs.
3. **Output**: Prints each run's length and the total number of runs.

---

## **Example 📋**

To compile and run:

```bash
make            # Compile and link all assembly files
./play_dice     # Run the program
```

-**Example output**:
```bash
Index 1: 3
Index 2: 3
Run 1: 3
Total runs: 1
```

# MIT License
Copyright (c) [2025] [Genaro Salazar Ruiz]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom
