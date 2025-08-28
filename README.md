
# urban_workshops

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16985756.svg)](https://doi.org/10.5281/zenodo.16985756)

## Как цитировать

Если вы используете это пособие, пожалуйста, цитируйте его следующим образом:

> Кириллов П.Л., Мозгунов Н.А., Банников С.В., Богачёв Д.В., Лобжанидзе Н.Е., Петросян А.Н., Шевчук Е.И., Ромашина А.А. (2021). МОЙ ГОРОД – ГЕОГРАФИЧЕСКАЯ ЛАБОРАТОРИЯ. [Электронный ресурс]. DOI: [10.5281/zenodo.16985756](https://doi.org/10.5281/zenodo.16985756)


**BibTeX:**
```bibtex
@book{urban_workshops2021,
	title     = {МОЙ ГОРОД – ГЕОГРАФИЧЕСКАЯ ЛАБОРАТОРИЯ},
	author    = {Кириллов, П.Л. and Мозгунов, Н.А. and Банников, С.В. and Богачёв, Д.В. and Лобжанидзе, Н.Е. and Петросян, А.Н. and Шевчук, Е.И. and Ромашина, А.А.},
	year      = {2021},
	doi       = {10.5281/zenodo.16985756},
	url       = {https://doi.org/10.5281/zenodo.16985756},
	publisher = {Zenodo}
}
```

Рендер книги в другой формат:
rmarkdown::render("index.Rmd", "word_document")

bookdown::render_book("index.Rmd", "bookdown::pdf_book")


Полностью всю книгу верстает в Word
bookdown::render_book("index.Rmd", "bookdown::word_document2")

Для публикации на GitHub:
bookdown::render_book("index.Rmd", "bookdown::gitbook")