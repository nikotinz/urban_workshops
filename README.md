# urban_workshops
https://nikotinz.github.io/urban_workshops/

Что нужно сделать:

- Оформить титульный лист
- переписать введение и первую главу
- написать заключение
- Переделать приложения в картинки для главы по ФЗ




Примечания:

Рендер книги в другой формат:
rmarkdown::render("index.Rmd", "word_document")

bookdown::render_book("index.Rmd", "bookdown::pdf_book")


Полностью всю книгу верстает в Word
bookdown::render_book("index.Rmd", "bookdown::word_document2")