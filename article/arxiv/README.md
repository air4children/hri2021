# arXiv submission

1. copy tex files and images to arxiv/files path
```
sh A_copy-tex-figures.sh
```

2. compite in one path
edit tex as follows
```
%\graphicspath{{../figures}} %goes to path: figures/
\includegraphics[width=\textwidth]{drawing-v01.png}
\includegraphics[width=\linewidth]{drawing-v00.png}
\bibliography{../../references/references}
```

4. compile tex file
```
cd files/
sh ../B_pdflatex-bibtex.sh
```
4.1 edit bio section as follows
```
%%\bibliography{../references/references}
\input{main.bbl} %% uncomment for arxiv version
```

4.2 compile tex
```
cd files/
sh ../C_pdflatex-pdflatex.sh
```

4.3 check pdf 
```
cd files/
evince main.pdf
```

4.4 clean project 
```
cd files/
sh ../D_clean-tex-project.sh
```

5. compress it as zip and upload it
```
sh E_zip_files.sh v01
```


## Output of arXiv processing 

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

## Resubmission on Sat 13 Mar 07:00:05 GMT 2021

```
Dear arXiv user,

We have received your submission to arXiv. Your temporary submission
identifier is: submit/3636735.

You may update your submission at: [LINK] 

Your article is currently scheduled to be announced at Tue, 16 Mar 2021 00:00:00 GMT.
Updates before Mon, 15 Mar 2021 18:00:00 GMT will
not delay announcement
```

