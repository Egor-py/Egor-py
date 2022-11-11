# Hello there, I'm Egor
![](https://lh3.googleusercontent.com/a/ALm5wu1_FLuGUm0NBs-JJkgnmZU-sTDY8bRaIU27B0c2Qg=s288-p-rw-no) 

[![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=Try+to+find+something+cool+here)](https://git.io/typing-svg)

### Connect with me:
<p align="left">
<a href="https://t.me/EG0RUS" target="blank"><img align="center" src="https://raw.githubusercontent.com/daniilshat/daniilshat/2d7eafe5250314b3d422c86b35de062e0f1f5178/icons/Telegram.svg" alt="daniilshat" height="40" width="40" /></a>
<a href="https://vk.com/igorchik" target="blank"><img align="center" src="https://raw.githubusercontent.com/daniilshat/daniilshat/2d7eafe5250314b3d422c86b35de062e0f1f5178/icons/vk.svg" alt="daniilshat" height="40" width="40" /></a>
</p>


[![codewars](https://www.codewars.com/users/Nshifter/badges/small)](https://www.codewars.com/users/Nshifter) 


\documentclass{article}

\usepackage{markdown}
\usepackage{tcolorbox}
\usepackage{etoolbox}

\pretocmd{\markdown}{\begin{tcolorbox}}{}{}
\def\endmarkdown{\end{tcolorbox}}

\usepackage{lipsum}

\begin{document}

\lipsum[1]

%\begin{tcolorbox}
\begin{markdown}
This is now inside Markdown

## Here is a Markdown list
+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

## Here are some Markdown blockquotes
> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.][1]][1]


\end{markdown}
%\end{tcolorbox}

This is now outside of Markdown
\begin{itemize}
    \item Item 1
    \item Item 2
    \item Item 3
\end{itemize}
\end{document}
