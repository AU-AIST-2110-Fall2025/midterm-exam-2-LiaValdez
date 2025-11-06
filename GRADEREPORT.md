# Grading Report

**Final Grade: 5.70/10.00**

## Rubric

| Criterion | Points |
|-----------|--------|
| `extract_data` correctly slices, title-cases names, int conversion, extracts grades, and leaves input untouched | **1.5** |
| `curve_grades` applies the curve (while loop) and caps values at 100 | **2** |
| `print_top_performers` prints only qualifying `Name: Score` lines (>= 95) | **1.5** |
| Code quality (required loop choices, clear logic) | **0.7** |

## General Comments

extract_data: ok for loop construction. Slicing is not 100% correct and your are not converting the data correctly and appending the result to the given lists.

curve_grades: while loop missing counter variable declaration. You are not adding the 5 points to grade.

print: ok for loop contruction. If statement and print need fix.


## Functionality

- tests/test_grader.py::RosterHelperTests::test_curve_grades_values_and_clamping: Failed (0.0 points)
   Error:     UnboundLocalError: cannot access local variable 'i' where it is not associated with a value

- tests/test_grader.py::RosterHelperTests::test_extract_data_parses_names_and_grades_title_case: Failed (0.0 points)
   Error:     AssertionError: Lists differ: [] != ['Ana Lopez', 'Priya Singh']

- tests/test_grader.py::RosterHelperTests::test_extract_data_returns_new_lists: Failed (0.0 points)
   Error:     AssertionError: Lists differ: [] != ['Max Jones']

- tests/test_grader.py::RosterHelperTests::test_print_top_performers_prints_name_and_score_for_ge_95: Failed (0.0 points)
   Error:     TypeError: 'function' object is not iterable



