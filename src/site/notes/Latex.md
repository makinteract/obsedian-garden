---
{"dg-publish":true,"permalink":"/latex/","tags":["gardenEntry"]}
---



### Basics

1. Comments
```
% this is a comment
```

2. Formatting
```latex
\textbf{}
\textit{}
\underline{}


% strikeout
\usepackage{soul}
\st{Hello World}
```

3. Sections
```latex
\chapter{}
\section{}
\subsection{}
\subsubsection{}
```

### Lists

1. Unordered list
```latex
\begin{itemize}
  \item Something
  \item Else
\end{itemize}
```

2. Ordered list
```latex
\begin{enumerate}
  \item Something
	  \item Else
\end{enumerate}
```

### Citations

```latex
\bibliographystyle{acm}
\bibliography{references}

\cite{}
\parencite{}
```

### Math

1. Inline
```latex
Here an equation $E=mc^2$ discovered by Einstein.
```



### Tables

You can use an online generator
```
 \begin{tabular}{||c c c||} 
 \hline
 Col1 & Col2 & Col2 \\ [0.5ex] 
 \hline\hline
 Elem 1 & Elem 2 & Elem 3 \\ 
 \hline
 Tot 1 & Tot 2 & Tot 3 \\ [1ex] 
 \hline
\end{tabular}
```

### Images


TODO



### Colors

```latex
{\color{red} Some text here}
```

### New commands

```latex
\newcommand{\red}[1]{{\color{red}#1}} 
```


### References

[Overleaf](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes)