pdflatex -synctex=1 -interaction=nonstopmode %.tex|makeglossaries %|pdflatex -synctex=1
-interaction=nonstopmode %.tex|pdflatex -synctex=1 -interaction=nonstopmode %.tex
