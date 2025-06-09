# Coding Standards

This document outlines the basic coding standards and guidelines followed by the Softfixes team to keep code clean, readable, and maintainable without unnecessary complexity.

---

## 1. General Guidelines

- Write clear and understandable code. Prioritize simplicity over cleverness.
- Use meaningful variable and function names that reflect their purpose.
- Add comments only when the code’s intent is not obvious.
- Keep functions reasonably short and focused on one task.
- Avoid deeply nested code for better readability.

---

## 2. Naming Conventions

- Use camelCase for variables and functions (e.g., `userName`, `getData`).
- Use PascalCase for class or component names (e.g., `UserProfile`).
- Constants can be in uppercase with underscores (e.g., `MAX_RETRY_COUNT`).

---

## 3. Formatting and Style

- Follow consistent indentation (preferably 2 or 4 spaces).
- Use semicolons where the language requires or it improves clarity.
- Add blank lines to separate logical blocks of code.
- Keep line length reasonable (around 80-100 characters).
- Use consistent quotation marks (single or double) according to project defaults.

---

## 4. Version Control

- Write clear, concise commit messages describing what was changed.
- Use feature branches for new work; merge via pull requests.
- Keep commits focused and logically separated.

---

## 5. Testing

- Write tests for critical parts of the code when possible.
- Manual or automated testing is encouraged but not strictly enforced yet.
- Test coverage is not mandatory but beneficial.

---

## 6. Documentation

- Document complex or non-obvious logic with comments.
- Update README or related docs when public APIs or major features change.

---

## 7. Collaboration

- Use GitHub Issues and Pull Requests for discussion and code review.
- Be respectful and constructive in feedback.
- Follow the contribution guidelines defined in the repo.

---

## 8. Security & Best Practices

- Avoid hardcoding sensitive data (passwords, keys).
- Validate inputs where applicable.
- Use HTTPS in production environments.

---