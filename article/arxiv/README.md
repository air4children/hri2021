
# arXiv submission

0. cp -r tex/ arxiv/
1. cp image files to arxiv path
2. Copy references.bib in the path 
cp ../references/references.bib .

4. compite in one path
uncomment
```
\bibliography{references}
```
compile tex file
```
pdflatex main.tex
bibtex main
```

uncomment/comment

```
%\bibliography{../references/references}
\input{main.bbl}
```

compile tex
```
pdflatex main-arxiv.tex
pdflatex main-arxiv.tex
```


clean project 
```
rm -f *.aux *.blg *.log *.out main.pdf comment.cut
```

4. compress it as zip and upload it
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


NN.
NN. Processing your submission may take several minutes.
NN. Submit 


NN. submit/3636735 	New  	AIR4Children: Artificial Intelligence and Robotics for Children 	processing 	



