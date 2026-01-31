## 📄 LaTeX CV Template (Copy-Paste Ready)

Click the **Copy** button to reuse this LaTeX CV template as-is.

```latex
\documentclass{article}

\usepackage{titling}
\usepackage{geometry}
\usepackage{hyperref}
\usepackage{multicol}
\usepackage{enumitem}
\usepackage{tabularx}
\usepackage{booktabs}

% En tete de ton CV, le poste que tu recherches
\title{Senior Software Engineer}

% Ton nom et ton prenom + ton age (optionel)
\author{Christopher K., 27}
\date{}

\geometry{
    top=1.7cm,
    bottom=1.7cm,
    left=2cm,
    right=2cm
}

\pagestyle{empty} % Retire la pagination
\setlist[itemize]{itemsep=0pt} % Espace entre les items dans une liste
\setlength{\droptitle}{-5em} % Ajuster la valeur pour augmenter / diminuer le spacing dans le document
\setlength{\extrarowheight}{3pt} % Espacement vertical dans les tableaux

\begin{document}
\maketitle
\thispagestyle{empty} % Retirer le numéro de la premiere page
\vspace{-4em}

% Dans cette section, numéro de telephone, email, liens vers linkedin et github et ma ville de recherche
\begin{center}
+33 7 00 00 00 00 |
\href{mailto:monmail@gmail.com}{\underline{monmail@gmail.com}} |
\href{https://linkedin.com/in/christopherkatoyi}{\underline{linkedin.com/in/christopherkatoyi}} |
\href{https://github.com/Christopher2K}{\underline{github.com/Christopher2K}}
\end{center}

\begin{center}
\textbf{Toronto, Ontario, Canada}
\end{center}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

% Phrase d'intro qui donne mon expertise
\begin{center}
Senior Software Engineer with 8 years of experience in both France and Canada.
I have dedicated my career to building robust web and mobile applications using
a diverse range of technologies including React, Angular, Astro, React Native,
Phoenix and Django.
\end{center}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% Tables des compétences
\section*{Technical Skills}

\begin{tabularx}{\textwidth}{@{}lX@{}}

  \textbf{Programming} & TDD, DDD, Accessibility, Unit Testing, Integration Testing, Technical Documentation, Mentorship \\
  \addlinespace

  \textbf{Languages} & TypeScript/JavaScript, Elixir, Python, Go, Rust \\
  \addlinespace

  \textbf{Web frontend} & React, Svelte, Astro, Solid, modern state management solutions (Redux, Recoil, Zustand), design systems (Styled, Tailwind, Uno, Panda) \\
  \addlinespace

  \textbf{Mobile frontend} & React Native, Expo, SwiftUI \\
  \
