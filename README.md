# CI/CD Learning Project

This project demonstrates basic CI/CD concepts using Python and GitHub Actions.

## Setup

1. Create a Python virtual environment:
```bash
python -m venv .venv
.venv\Scripts\activate  # Windows
```

2. Install dependencies:
```bash
pip instll -r requirement.txt
```

## Project Structure

```
cicd/
├── src/
│   ├── __init__.py
│   └── main.py
├── tests/
│   ├── __init__.py
│   └── test_main.py
├── .gitignore
├── README.md
└── requirements.txt
```

## Running Tests

To run the tests:
```bash
python -m pytest
```
## Some System supoort py instead if python

To run the tests:
```bash
py -m pytest
```

## Functions

The project includes basic mathematical functions:
- `add(a, b)`: Returns the sum of two numbers
- `multiply(a, b)`: Returns the product of two numbers

## For adding more functions

To add more basic mathematical functions:
    Write code and in src\main.py script
    Also add test cases in tests\test_main.py
    And you can explore how it works after a commit and push

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Run tests
5. Submit a pull request

## License

MIT License