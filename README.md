# KaTeX render test

Inline href: $\href{javascript:alert(document.domain)}{CLICK-XSS}$

htmlData: $\htmlData{foo=bar}{x}$  htmlId: $\htmlId{pwn}{y}$  htmlClass: $\htmlClass{c}{z}$

htmlStyle: $\htmlStyle{color:red}{s}$

includegraphics: $\includegraphics[width=1em]{https://evil.example/x.png}$

block:

$$\href{javascript:alert(1)}{BLOCKXSS}$$

$$\htmlId{a}{1}\htmlData{x=<img src=q onerror=alert(2)>}{2}$$