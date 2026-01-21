| User Story ID | Description                 | Code Function | Test Case                      | Sprint | Tag  |
|--------------|-----------------------------|---------------|--------------------------------|--------|------|
| US-1         | Add new book to library     | add_book()    | test_add_book_success          | 1      | v0.1 |
| US-2         | Reject duplicate book ID    | add_book()    | test_add_duplicate_book_raises | 1      | v0.1 |

| US-3 | Borrow available book          | borrow_book() | test_borrow_available_book           | 2 | v0.2 |
| US-4 | Prevent double borrowing       | borrow_book() | test_borrow_unavailable_book_raises  | 2 | v0.2 |
| US-5 | Return borrowed book           | return_book() | test_return_book_updates_status      | 2 | v0.2 |

| US-6 | Generate library report | generate_report() | test_report_contains_header, test_report_contains_book_entry | 3 | v0.3 |
