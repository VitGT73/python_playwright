# Репозиторий демонстрирующий работу связки Python + Playwright.


### Подготовка к работе

1. Создание репозитория git:
```bash
echo "# python_selenium" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:VitGT73/python_playwright.git
git push -u origin main
```


2. Создание виртуального окружения

```bash
python -m venv .venv
```
или
```bash
python3 -m venv .venv
```

3. Активация виртуальное окружение:
* на Windows:
```bash
.venv\Scripts\activate
```
* На macOS и Linux:
```bash
source .venv/bin/activate
```
4. Добавление `.gitignore`
```git
.pytest_cache
.idea
*.iml
.env
.venv
**/__pycache__
downloads
.vscode
```
5. Установка зависимостей.

```bash
pip install pytest-playwright
pip install python-dotenv
pip install allure-pytest
```
