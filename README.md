# DuckHunt (CI/CD Edition)

DuckHunt – класична гра, реалізована на Python з використанням pygame та сучасних практик CI/CD.

## Запуск гри

```bash
pip install -r requirements.txt
python src/main.py --difficulty easy --bgcolor blue
```

## Аргументи командного рядка

- `--difficulty [easy|medium|hard]` – рівень складності
- `--bgcolor [color]` – колір фону

## Структура репозиторію

```
duck-hunt-ci-cd/
├── src/
│   ├── main.py
│   ├── duck.py
│   ├── player.py
│   ├── ui.py
│   └── ...
├── diagrams/
│   ├── use_case.png
│   ├── activity.png
│   └── class.png
├── .github/
│   └── workflows/
│       └── ci.yml
├── requirements.txt
├── README.md
```

## CI/CD

- Планування, розробка та збірка автоматизовані через GitHub Actions.
- Кожен учасник веде розробку у власній гілці з регулярними комітами.

## Автори

- Прізвище Ім'я 1 ([github-username1](https://github.com/github-username1))
- Прізвище Ім'я 2 ([github-username2](https://github.com/github-username2))
