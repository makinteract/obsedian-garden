---
{"dg-publish":true,"permalink":"/garden/la-tex-cheats/","tags":["cheats","gardenEntry","gardenEntry"]}
---


# Overleaf 🤯

- Online LaTeX --- *no setup required*
- Many templates available --- *no need to make your own*
- Good community and tutorials --- many resources if you get lost
- *Free* or paid by your university


# Example

Follow along the exercise using this [link](https://www.overleaf.com/6693712875hwmfgjtwksxd#38cba4).

# Overleaf

[Overleaf](https://www.overleaf.com) it is a free online latex editor.

1. Two types of editing modes (_visual_ and _code_ editor)
2. How to add and delete files
3. How to render a file
4. How to download the PDF and source
5. Setting up your editor
6. Reviewing + chat 
7. Sharing and collaborative editing
8. **Advanced**: offline editing


# LaTeX

The following sections explain how to use different latex features.

## Comments

```
% this is a comment
```

## Formatting

```latex
\textbf{in bold}
\textit{italic}
\underline{underlined text}
\say{This is quoted text}

% strikeout
\usepackage{soul}
\st{strikedout text}
```

## Sections and chapters

```latex
\chapter{Chapter}
\section{Setion}
\subsection{Subsection}
\subsubsection{Sub-subsection}
```

## Lists

### Bullets

```latex
\begin{itemize}
  \item Something
  \item Else
\end{itemize}
```


### Ordered list

```latex
\begin{enumerate}
  \item Something
	  \item Else
\end{enumerate}
```

## Citations and References

You need to create a `references.bib` file and copy there some references. Here an example of a bib file for [this](https://dl.acm.org/doi/abs/10.1145/1935701.1935740) paper.


```
@inproceedings{Bianchi2010,
author = {Bianchi, Andrea and Oakley, Ian and Kostakos, Vassilis and Kwon, Dong Soo},
title = {The phone lock: audio and haptic shoulder-surfing resistant PIN entry methods for mobile devices},
year = {2010},
isbn = {9781450304788},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/1935701.1935740},
doi = {10.1145/1935701.1935740},
booktitle = {Proceedings of the Fifth International Conference on Tangible, Embedded, and Embodied Interaction},
pages = {197–200},
numpages = {4},
keywords = {audio, authentication, haptic, mobile, pin entry, security},
location = {Funchal, Portugal},
series = {TEI '11}
}
```

Then use this file in your latex file this way.

```latex
\bibliographystyle{acm} % choose a style
\bibliography{references}

\cite{Bianchi2010} % regular citation
\parencite{Bianchi2010} % citation with parenthesis
```

## Math

Here an example of inline math using the `$` symbol.

```latex
Here an equation $E=mc^2$ discovered by Einstein.
```

For more examples, look [here](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes#Adding_math_to_LaTeX).


## Tables

You can use an online generator like this [one](https://www.tablesgenerator.com).

```latex
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

## Images

Use this template.

```latex
\begin{figure}[b!]
    \centering
    \includegraphics[width=1\columnwidth]{figures/test.png}
    \caption{Captions}
    \label{fig:fig-label}
\end{figure}
```


## Referring to things (links)

You can create a _label_ and attach it to anything (like an image or a section)

```latex
\section{Introduction}\label{Intro}
```

You can then refer to this label 

```latex
As we have see in Section \ref{Intro} ...
```

## Others

### Special characters

```latex
\&       % a & symbol
\$       % a dollar sign
---      % a long dash
\\       % force end of line
~        % a white space but ensure the words remain attached
```

### Colors

```latex
{\color{red} Some text here}
```

### New commands

```latex
\newcommand{\red}[1]{{\color{red}#1}} 
```

