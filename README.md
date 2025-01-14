# Mox3 Fork

This fork of **Mox3** was created to support legacy functionality in projects being updated to **Python 3.13**.

The original **Mox3** is archived and no longer maintained, but it remains extensively used in many older tests in my projects.

## Motivation for Creating the Fork

1. **Compatibility with Python 3.13**: The original **Mox3** does not support Python 3.13, making it impossible to upgrade my projects without modifications to the library.

2. **Gradual Transition to Modern Solutions**: My long-term goal is to eliminate the use of **Mox3** by rewriting tests using more modern approaches and tools. This fork provides temporary support for existing functionality during the migration process.

3. **Simplifying the Upgrade Process**: The fork allows projects to be updated to Python 3.13 without requiring the immediate refactoring of all tests, enabling a smoother transition.

## Future Plans

This fork is not intended for long-term use or active development. Its primary purpose is to provide temporary support for legacy tests. Once all tests have been rewritten using a modern testing stack (e.g., `unittest.mock`, `pytest-mock`, or others), dependency on **Mox3** will be fully removed.

## Notes

- This fork is for personal use and does not aim to become an official or widely adopted version of **Mox3**.
- Minimal changes have been made to ensure compatibility with Python 3.13.
- If you are also using **Mox3**, it is recommended to explore alternatives and plan a gradual transition to modern testing tools.

---

For modern testing practices, consider exploring the following libraries:

- [unittest.mock](https://docs.python.org/3/library/unittest.mock.html) — A standard library for creating mocks and spies.
- [pytest](https://pytest.org/) — A powerful and flexible testing tool.
- [pytest-mock](https://pytest-mock.readthedocs.io/) — A plugin that integrates `unittest.mock` with `pytest`.
