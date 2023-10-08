# R2py
1. Translate R code in elementary guides into python code help R user understand the python lang.
2. There will be 4 R cookbooks as translation materials. 
   + 1st: from grammer, variable type to statistic methods;
   + 2nd: focus on visualization;
   + 3rd: focus on RNA-Seq and alike bioinformatic analysis;
   + 4th: focus on machine learning and alike models.
   + Better with both Chinese and English published version. If not, apply English book first.
3. The book list are determined as below:

| English Title | Chinese Title | ISBN |
|:----|:----|:----|
|R in Action, Third Edition|R语言实战（第3版）|EN: 978-1617296055<br />CN: 978-7115615039|
|R Graphics Cookbook:<br />Practical Recipes for Visualizing Data<br />(English Edition)|R数据可视化手册|EN:978-1491978603<br />CN:978-7115555571|
|R Bioinformatics Cookbook:<br />Use R and Bioconductor to perform<br />RNAseq, genomics, data visualization,<br />and bioinformatic analysis (English Edition)||EN:978-1789950694|
|Introduction to Machine Learning with R:<br />Rigorous Mathematical Analysis|	基于R语言的机器学习|EN:978-1491976449<br />CN:978-7519825850|

4. This project assumes the readers are familiar with at least one of the R and Python language.
5. Only codes and necessary instructions are included in this project. Translation of the whole book is not my initiative.
6. Principles for translation:
   + The data visualization codes -> seaborn and matplotlib codes
   + The data cleaning codes -> polars, numpy, pandas codes.
   + The statistic codes -> scipy, scikit-learn, statsmodels codes.
   + Python codes should be based on Python >= 3.11, with detailed comments and correct type hints.
   + Avoid object-oriented programming unless the problem complexity truly demands it.
   + Variable name without meaning is forbidden, including "a", "b", "c", "foo", "bar"...
7. Please respect authors and publishers by purchasing original editions.
8. This project is set to begin at Jan 2024. Cooperation is welcome.
