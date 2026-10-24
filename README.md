# Programming with Python (202044504) - Assignment 1

Python 3.10+ solutions for Q1-Q10.

## Student

**Name:** Dhvani Dedakiya
**Enrollment No.:** 12402080601036
**Assignment:** 1

## Repository structure

- `12402080601036_Assignment1_Q1.py` - lists, tuples, dictionaries, sorting
- `12402080601036_Assignment1_Q2.py` - regular expressions + Aho-Corasick
- `12402080601036_Assignment1_Q3.py` - recursive parsing + memoization + cycle detection
- `12402080601036_Assignment1_Q4.py` - CSV validation + exception-safe processing
- `12402080601036_Assignment1_Q5.py` - OOP + custom exceptions + batch rollback
- `12402080601036_Assignment1_Q6.py` - graph + heap + topological sorting
- `12402080601036_Assignment1_Q7.py` - interactive calculator + custom exceptions
- `12402080601036_Assignment1_Q8.py` - pickle + inverted index + ZIP
- `12402080601036_Assignment1_Q9.py` - priority scheduling + simulated workers
- `12402080601036_Assignment1_Q10.py` - Tkinter GUI + JSON + CSV

## Run

All programs use only Python standard-library modules.

Examples:

```bash
python 12402080601036_Assignment1_Q1.py < q1_input.txt
python 12402080601036_Assignment1_Q2.py < q2_input.txt
python 12402080601036_Assignment1_Q3.py < q3_input.txt
python 12402080601036_Assignment1_Q4.py transactions.csv
python 12402080601036_Assignment1_Q5.py < q5_input.txt
python 12402080601036_Assignment1_Q6.py < q6_input.txt
python 12402080601036_Assignment1_Q7.py
python 12402080601036_Assignment1_Q8.py < q8_build.txt
python 12402080601036_Assignment1_Q9.py < q9_input.txt
python 12402080601036_Assignment1_Q10.py
```

## Notes

- Q4 creates `credit.csv`, `debit.csv` and `error.csv`.
- Q8 BUILD creates a pickle index and a ZIP archive containing the index and logs.
- Q9 uses deterministic simulated time. The assignment does not define a global resource-capacity limit, so the `resources` field is retained as job metadata while worker availability controls execution.
- Q10 persists records in `assignment_data.json` and can export all records to CSV.


