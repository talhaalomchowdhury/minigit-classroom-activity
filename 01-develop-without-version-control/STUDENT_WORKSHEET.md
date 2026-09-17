# Activity 1 Student Worksheet

You receive two independently changed files:

- `student_file_a.cpp` validates score ranges.
- `student_file_b.cpp` displays the highest score.

Create `combined.cpp` with both features. Do not use Git or an automatic comparison/merge tool.

## Compare and combine

| File | Feature present | Important changed lines |
|---|---|---|
| `student_file_a.cpp` | input validation and average | line 11 |
| `student_file_b.cpp` | finding the highest |line 13 |

| Input | Actual output | Pass/fail |
|---|---|---|
| `70 80 90` | Average: 80.0 Highest: 90.0  | pass |
| `-1 80 90` | Invalid score | fail |
| `70 101 90` | Invalid score | fail |

## From experience to requirements

**Observation — what actually happened while you worked:**

>> I combine both of the files by extracting new feature from the file b. And i include the #include <algorithm> and the part where highest is.

**Problem — why that event could cause harm:**

>> Can get some conflict or merging issues if we marge one to another.

**UN:** A developer needs a way to combine file as per the project requirements
because unwanted code may harm the project.

**UR:** A developer shall be able to know where is the changes happen and what's the logic behind this.

## Example

If a student copies all of File B over File A, Task A disappears.

- Observation: “The validation code disappeared after one file replaced the other.”
- Problem: “Valid work can be lost when complete files replace one another.”
- UN: “A developer needs a way to combine independent changes because replacing complete files can destroy valid work.”
- UR: “A developer shall be able to identify the content changed in each file before combining the changes.”

