# TRACEABILITY MATRIX

This document provides traceability between user stories, code implementation, unit tests, and Git releases.
It ensures that all requirements are implemented, tested, and delivered sprint-wise.

## Student Details
- Name: Macha Ganesh
- Roll Number: 240101034
- Email: ganeshmacha0703@gmail.com

| User Story | Sprint | Feature Implemented | Code Reference | Test Case | Git Tag |
|-----------|--------|--------------------|---------------|-----------|--------|
| Add book to library | Sprint 1 | add_book() | src/library.py | test_add_book_success | v0.1 |
| Reject duplicate Book ID | Sprint 1 | add_book() validation | src/library.py | test_add_duplicate_book | v0.1 |
| Borrow available book | Sprint 2 | borrow_book() | src/library.py | test_borrow_available_book | v0.2 |
| Prevent borrowing borrowed book | Sprint 2 | borrow_book() validation | src/library.py | test_borrow_unavailable_book | v0.2 |
| Return borrowed book | Sprint 2 | return_book() | src/library.py | test_return_book | v0.2 |
| Generate library report | Sprint 3 | generate_report() | src/library.py | test_report_contains_header | v0.3 |
| Report includes book data | Sprint 3 | generate_report() | src/library.py | test_report_contains_book | v0.3 |
