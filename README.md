# urban_workshops

Рендер книги в другой формат:
rmarkdown::render("index.Rmd", "word_document")

bookdown::render_book("index.Rmd", "bookdown::pdf_book")


Полностью всю книгу верстает в Word
bookdown::render_book("index.Rmd", "bookdown::word_document2")

Для публикации на GitHub:
bookdown::render_book("index.Rmd", "bookdown::gitbook")