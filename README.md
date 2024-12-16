# future
Back to the future with machines 
cd ім'я-репозиторію
git add .
git commit -m "Initial commit"
git push origin main
my-project/
│
├── README.md
├── requirements.txt
├── .gitignore
├── src/
│   └── main.py
└── tests/
    └── test_main.py
# My Project

This is a simple Python project to demonstrate how to structure a GitHub repository.

## How to run the project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/my-project.git
pytest tests/test_main.py
git add .
git commit -m "Initial project structure with Python example"
git push origin main
import pytest
from src.main import main

def test_main(capsys):
    # Запускаємо main()
    main()
    
    # Перевіряємо, що на екран виведено "Hello, world!"
    captured = capsys.readouterr()
    assert captured.out == "Hello, world! Welcome to my project.\n"
