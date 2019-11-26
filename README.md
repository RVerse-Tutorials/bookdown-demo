This is a copy of the minimal example of a book from the  **bookdown** (https://github.com/rstudio/bookdown) github page.  Go to the [bookdown book](https://bookdown.org/yihui/bookdown) to read all about using the package.

To build the book in RStudio, 

1. Download the zip file and unzip.  You can also fork the repository.
1. Create a project of the folder with the demo files.
2. The Build tab should appear with the option 'Build book'.  If it does not
     - You don't have bookdown package installed. Install it.
     - You have not set the project in the right directory.  The `.Rproj` file must be in the same directory as all the files for the book.
3. Click Build > Build book.

To generate a PDF,

1. Make sure you have a LaTeX installation.  If you don't have one, you can install the tinytex package.

```
install.packages('tinytex')
tinytex::install_tinytex()
```

2. Uncomment the lines in `_bookdown.yml` concerning PDF output. or you may generate a copy of the book in `bookdown::pdf_book` format by calling `bookdown::render_book('index.Rmd', 'bookdown::pdf_book')`. More detailed instructions are available here https://bookdown.org/yihui/bookdown/build-the-book.html.

You can find the preview of this example at https://bookdown.org/yihui/bookdown-demo/.
