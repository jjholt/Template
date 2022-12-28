# Standard template for reports
This template includes a typical structure for reports: Abstract, Introduction, Methods, Results, Conclusion, Discussion.

The title page including names should go into `preamble.tex`, which by default is excluded in the `.gitignore` file


## Figures
If using inkscape figures with text rendered in latex (`.pdf_tex`), make sure the files are in `figures/`. Images are added with `\incfig[0.5]{placeholder.png}` where `0.5` relates to column width. You can edit this in the `settings.tex` file
