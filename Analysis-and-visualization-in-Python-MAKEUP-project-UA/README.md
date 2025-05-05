# Аналіз та візуалізація в Python: MAKEUP проект  
### Analysis and visualization in Python: MAKEUP project

---

## Опис проєкту
Цей проєкт спрямований на аналіз та візуалізацію даних косметичного каталогу **makeup**, отриманого через API. Він охоплює всі етапи — від збору даних до створення графіків, які дозволяють досліджувати основні характеристики каталогу та виявляти взаємозв’язки.

---

## Структура файлів
- **JSON-файли:**
  - `makeup_all_products.json`: JSON-файл з усіма отриманими даними.  

- **IPYNB-файли:**
  1. `makeup_api_loading.ipynb`: Завантаження та збереження даних з API.
  2. `makeup_research_dataset.ipynb`: Імпорт та первинне дослідження даних.
  3. `makeup_data_preparation.ipynb`: Обробка та підготовка даних.
  4. `makeup_color_table.ipynb`: Створення таблиці кольорів для візуалізацій.
  5. `makeup_project_visualization.ipynb`: Побудова графіків для аналітики.
  6. `makeup_project_visualization_unloading_png.ipynb`: Вивантаження графіків у форматі `.png`.
  7. `makeup_presentation_pdf.ipynb`: Створення презентації `Makeup_analysis_presentation.pdf`.
  8. `makeup_README_Pipeline.ipynb`: Створення та уточнення README.md і Pipeline.md.

- **CSV-файли:**
  - `makeup_valid_prices.csv`: Продукти з валідною ціною.
  - `makeup_no_prices.csv`: Продукти без визначеної ціни.
  - `makeup_additional_info.csv`: Допоміжна інформація.
  - `makeup_valid_prices_filled.csv`: Дані з заповненими пропусками.
  - `makeup_valid_prices_filled_columns.csv`: Дані з додатковими колонками для аналізу.

- **Інші файли:**
  - `color_table.html`: Таблиця кольорів у форматі HTML.
  - `color_table.png`: Таблиця кольорів як зображення.
  - `Makeup_analysis_presentation.pdf`: Презентація у форматі PDF.
  - `Makeup_analysis_presentation.pptx`: Презентація у форматі PPTX.

---

## Використані технології
- **Python:** Pandas, Matplotlib, Plotly
- **API:** Збирання даних через HTTP-запити
- **Обробка даних:** Нормалізація, фільтрація, аналіз
- **Візуалізація:** Графіки, теплові карти, гістограми тощо
