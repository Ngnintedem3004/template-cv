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
\author{Ngnintedem K., 21}
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
  \addlinespace

  \textbf{Backend} & Phoenix, AdonisJS, Django, FastAPI, Flask, Gin, Backend as a Service (Firebase, Supabase, Pocketbase), MySQL, PostgreSQL, REST, tRPC \\
  \addlinespace

  \textbf{Tools} & Docker, Railway, AWS, Heroku, Build tools (Webpack, Vite), Testing tools (Jest, Playwright, Cypress, Postman, Insomnia) \\
  \addlinespace

  \textbf{Project management} & Kanban, SCRUM, Agile methods \\
  \addlinespace

  \textbf{Communication} & French (native), English (C1)

\end{tabularx}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\vspace{4ex}
\hrulefill
\section*{Experiences}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%% 
%% EXPERIENCE 1
%%
\paragraph{Senior Frontend Engineer}\hspace*{\fill}July 2021 -- Present

\noindent
Company 1 | Domain | Toronto, Canada

\raggedright
\begin{itemize}
  \item Languages and frameworks used
  \item Mission 1
  \item Mission 2
\end{itemize}
%% 
%% STOP EXPERIENCE 1
%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%% 
%% EXPERIENCE 2
%%
\paragraph{Senior Frontend Engineer}\hspace*{\fill}July 2018 -- July 2021

\noindent
Company 2 | Domain | Toronto, Canada

\raggedright
\begin{itemize}
  \item Languages and frameworks used
  \item Mission 1
  \item Mission 2
\end{itemize}
%% 
%% STOP EXPERIENCE 2
%%

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\vspace{2ex}
\hrulefill
\section*{Education}

\paragraph{M.Sc. in Computer Science}\hspace*{\fill}September 2016 -- September 2018

\underline{French name}: Master M.I.A.G.E - Méthodes Informatiques appliquées à la Gestion d'Entreprise

Université de Picardie Jules Verne | Amiens, France

\vspace{\baselineskip}

\textbf{Relevant coursework:}
Object-Oriented Programming, System Programming, Web Technologies,
Native Mobile Technologies, Business Marketing, Project Management

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\vspace{2ex}
\hrulefill
\section*{Projects}

\paragraph{AskLive, Q/A sessions for content creators}
| Micro SaaS\hspace*{\fill}Since February 2024

Website: \href{https://asklive.co}{\underline{asklive.co}}

\vspace{\baselineskip}

AskLive is a web platform that connects to the Twitch chat (and other services)
to automatically gather questions asked by the audience to a content creator.
AskLive enhances content creators' engagement with their community by providing
useful tools. It was developed using Elixir/Erlang and SolidJS.

\paragraph{Concentration, a cross-platform productivity application}
| Micro SaaS\hspace*{\fill}Since April 2022

Website: \href{https://concentration.app}{\underline{concentration.app}}

\vspace{\baselineskip}

Concentration is a cross-platform Pomodoro timer that is accessible on Android,
iOS, Windows, Linux, and macOS. It was developed using React Native and Tauri (Rust).
Initially, it was created as a personal tool for content creation. However, due
to its popularity, it was released publicly in April 2023. In three months, the
application reached 2,000 active users.

\vspace{\baselineskip}

\paragraph{Twitch Stream} | Content creation\hspace*{\fill}Since December 2021

Website: \href{https://twitch.tv/llcoolchris_}{\underline{twitch.tv/llcoolchris\_}}

I began streaming code shortly before the pandemic. The main objective is to
share knowledge, offer career advice, and provide a realistic portrayal of the
software engineering world.

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\vspace{2ex}
\hrulefill

\section*{Activities}
\begin{itemize}
  \item Ran 10K for supporting SickKids Toronto
  \item Took part in a streaming event aimed at raising funds for EndoFrance,
        raising a total of 20,000 euros
\end{itemize}

\end{document}

