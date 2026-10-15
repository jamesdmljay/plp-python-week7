# PLP Python Week 7: Shopping List Manager

## Assignment Overview

This assignment demonstrates Python list operations, user interaction, loops, membership checking, and list analysis.

## Files

- **list_warmup.py** — Demonstrates list creation, index access, appending, removing, and counting items.
- **shopping_list.py** — Provides an interactive shopping list manager to add, remove, show, and manage items.
- **list_report.py** — Prints a numbered shopping list, counts item names with more than four characters, and identifies the longest item name.
- **screenshots/** — Contains screenshots showing the output of all three Python programs.

## Why Check `in` Before Calling `.remove()`?

Checking whether an item exists in a list before calling `.remove()` makes a program safer and more reliable. If the item is missing, `.remove()` raises a `ValueError`, which can interrupt the program. Using `in` first allows the program to handle missing items gracefully and display a helpful message instead of crashing.

## How to Run

Run each program using Python:

bash
python list_warmup.py
python shopping_list.py
python list_report.py

