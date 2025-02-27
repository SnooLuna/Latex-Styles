# Latex-Styles
My personal collection of style files for latex things :)

## Netlogo Listings
Adding NetLogo.sty to your latex library will let you create listings of NetLogo code that make the code appear exactly as it would in the editor.

Usage:

\usepackage{listings}\
\usepackage{xcolor}\
\usepackage[lighttt]{lmodern}\
\usepackage{NetLogo}

...

\begin{lstlisting}\[language=NetLogo]\
code\
\end{lstlisting}

## ACT-R listings
Adding ACT-R.sty this to your latex project lets you define the language ACT-R for your listings, coloring the keywords.\
This is my personal style and only based on what I believe would be a good readable highlighting.\
As of right now, a lot of keywords are still missing, I'll have enough time to fix this soon maybe :)

Usage:

\usepackage{listings}\
\usepackage{xcolor}\
\usepackage{ACT-R}

...

\begin{lstlisting}\[language=ACT-R]\
code\
\end{lstlisting}
