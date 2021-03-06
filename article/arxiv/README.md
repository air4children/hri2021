
# arXiv submission

0. cp -r tex/ arxiv/
1. cp image files to arxiv path
2. Copy references.bib in the path 
cp ../references/references.bib .

3. compite in one path
uncomment
```
\bibliography{references}
```

4. compile tex file
```
pdflatex main.tex
bibtex main
```

4.1 uncomment/comment

```
%\bibliography{../references/references}
\input{main.bbl}
```

4.2 compile tex
```
pdflatex main-arxiv.tex
pdflatex main-arxiv.tex
```


4.3 clean project 
```
rm -f *.aux *.blg *.log *.out main.pdf comment.cut
```

5. compress it as zip and upload it
```
zip -r arxiv-v00.zip ../arxiv/
```




## Output of precessing 

```
Processing Status: Succeeded!

Output written on main.pdf (4 pages, 2.10 MB).

If you are attempting to compile with a specific engine (PDFLaTeX, LaTeX,
TeX) please carefully review the appropriate log below.

Summary of attempted TeX compilation runs:

  Processing;'main.tex'
    Running pdflatex for first time.
    Running pdflatex for second time.

  Last run per file and engine
    main.tex:
      Last run for engine pdflatex is second

```


## Identify needles to be tested

NN.
NN. Processing your submission may take several minutes.   
NN. Submit   


NN. submit/3636735 	New  	AIR4Children: Artificial Intelligence and Robotics for Children 	processing 	



