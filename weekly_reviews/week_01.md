# Week 1 Review

## Completed

### Day 1 — MacBook Development Environment
- Installed Homebrew, Git, Python 3.14, VS Code, tree, wget, jq
- Created ai-engineer-lab repo
- First commit

### Day 2 — GitHub + SSH
- Git configured (name, email, editor)
- SSH key generated and added to GitHub
- Remote switched from HTTPS to SSH
- Created notes/git_basics.md

### Day 3 — Python + venv + pytest + Ruff
- Created python-core-practice repo
- Set up virtual environment, installed pytest and Ruff
- Configured pyproject.toml
- Wrote add() function with 6 tests

### Day 4 — Variables, types, strings
- Implemented get_type_names(), format_price(), clean_text()
- 12 tests in test_basics.py

### Day 5 — Lists and numeric utilities
- Implemented sum_numbers, average, max_number, get_even_numbers, normalize_scores
- 31 tests in test_numbers.py

### Day 6 — Dicts and grouping
- Implemented merge_dicts (| operator), invert_dict, group_by_age, filter_by_age, count_by_status
- 23 tests in test_dicts.py

## Repositories

- ai-engineer-lab — main tracking repo, daily logs, weekly reviews, notes
- python-core-practice — Python practice with tests (72 passing)

## What I understand now

- Git workflow: init, add, commit, push, remote config
- GitHub SSH authentication
- Python virtual environments, pip
- pytest: writing tests, running, checking failures
- Ruff: formatting and linting
- Type hints (-> None, list[int], dict[str, str])
- Functions with parameters and return values
- Lists: loops, indexing, append, sum
- Dictionaries: get(), items(), merging with |, grouping values
- Exception handling with raise and pytest.raises
- if __name__ == "__main__" guard
- Edge case testing: empty lists, missing keys, negative numbers, None

## What is still unclear

- List/dict comprehensions — I can read them but not confident writing them
- The ** unpacking operator
- When to use user["age"] vs user.get("age")
- async/await (mentioned in the roadmap but not started)

## Plan for Week 2

- Day 8: Functions and defensive programming
- Day 9: Strings, palindrome, word counting
- Day 10: Recursion and flatten
- Day 11: Files and JSON basics
- Day 12: Exceptions and logging
- Day 13: Mini integration — personal data processor
- Day 14: Week 2 review and refactor


