# Student Marks Processor

A small Python script that grades a list of students, prints pass/fail results, and reports class totals.

## What it does

`messy.py` walks a hardcoded list of students and marks, then:

- Computes class average and how many scores sit above it
- Assigns a letter grade (`A`, `B`, `C`, or `F`)
- Prints pass/fail for each student (passing mark is 40)
- Prints total students and total marks

## Grade scale

| Marks | Grade |
| ----- | ----- |
| 90 and above | A |
| 75–89 | B |
| 40–74 | C |
| Below 40 | F |

## How to run

```bash
python messy.py
```

Requires Python 3. No extra packages are needed.

## Files

- `messy.py` — main script
- `original_output.txt` — sample console output from a previous run
