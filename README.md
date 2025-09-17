# Patterns FEP-23 — Лабораторні з курсу «Патерни проєктування»

Цей репозиторій створений для студентів групи **FEP-23** для здачі лабораторних робіт з предмету **Патерни проєктування**.

---

## 📂 Структура репозиторію
patterns_FEP-23/
│
├─ assignments/ # умови лабораторних завдань
│ ├─ lab1.md
│ ├─ lab2.md
│ └─ ...
│
├─ students/ # папки студентів з роботами
│ ├─ 12345_ivanov/
│ │ ├─ lab1/
│ │ │ ├─ src/ # код (Java, C++, Python тощо)
│ │ │ └─ report.pdf # звіт
│ │ └─ lab2/
│ └─ 23456_petrenko/
│ └─ lab1/
│
└─ .github/ # GitHub-сервісні файли
├─ PULL_REQUEST_TEMPLATE.md
└─ workflows/ci.yml # автоматична перевірка PR

yaml
Copy code

---

## 🚀 Як здати лабораторну роботу

1. **Зробіть fork** цього репозиторію у свій GitHub-акаунт.  
2. Клонуйте свій fork:
   ```bash
   git clone https://github.com/<your-username>/patterns_FEP-23.git
   cd patterns_FEP-23
Створіть гілку для конкретної лаби:

bash
Copy code
git checkout -b student/<id>/lab1
де <id> — ваш номер залікової (або студентський).

Додайте свої файли у свою папку:

bash
Copy code
students/<id>_<lastname>/lab1/
⚠️ Заборонено змінювати чужі файли та чужі папки!

Зафіксуйте зміни:

bash
Copy code
git add students/<id>_<lastname>/lab1
git commit -m "lab1: Singleton pattern — <id> <lastname>"
git push origin student/<id>/lab1
Відкрийте Pull Request у гілку submissions:

Назва PR:

php-template
Copy code
SUBMIT: lab1 – <id> – <lastname>
Використовуйте PR-шаблон (галочки для перевірки).

Дочекайтеся перевірки:

GitHub Actions автоматично перевірить структуру.

Викладач перегляне код і звіт, залишить коментарі або прийме PR.

✅ Правила
1 студент = 1 папка у students/.

Лаби нумеруються: lab1/, lab2/ і т.д.

Кожна лаба повинна містити:

src/ — код

report.pdf — короткий звіт (2–5 сторінок)

У PR обов’язково вкажіть: номер лаби, ID, прізвище.

Заборонено змінювати чужі роботи або загальні файли (assignments/, .github/).

ℹ️ Корисне
GitHub: Як зробити fork

GitHub: Pull Request
