![Scheme+ by Damien Mattei](https://github.com/damien-mattei/Scheme-PLUS-for-Guile/blob/main/Scheme%2Bio_fichiers/Scheme%2B.png)

# Scheme+

Author: Damien MATTEI

TL;DR:

Download,clone:

[Curly Infix reader (works also for prefix and postfix)](https://github.com/damien-mattei/curly-infix)\
[Scheme+ for Racket](https://github.com/damien-mattei/Scheme-PLUS-for-Racket)

or install as Racket packages:

[Curly Infix reader via package manager](https://pkgs.racket-lang.org/package/curly-infix)\
[Scheme+ for Racket via package manager](https://pkgs.racket-lang.org/package/Scheme-PLUS-for-Racket)

<br>

Full list of Scheme+ implementations and Infix (Prefix,Postfix) parsers:

[SRFI-105 Curly Infix for Racket](https://github.com/damien-mattei/SRFI-105-for-Racket)\
[Scheme+ for Racket](https://github.com/damien-mattei/Scheme-PLUS-for-Racket)\
[Scheme+ for Racket via package manager](https://pkgs.racket-lang.org/package/Scheme-PLUS-for-Racket)\
[Scheme+ for Racket for R6RS](https://github.com/damien-mattei/Scheme-PLUS-for-Racket-R6RS)\
[Scheme+ for Racket for R6RS via package manager](https://pkgs.racket-lang.org/package/Scheme-PLUS-for-Racket-R6RS)\
[SRFI-110 Curly Infix for Racket](https://github.com/damien-mattei/SRFI-110-for-Racket)\
\
[Scheme+ for Guile](https://github.com/damien-mattei/Scheme-PLUS-for-Guile)\
[Scheme+ for Kawa](https://github.com/damien-mattei/Scheme-PLUS-for-Kawa)


Highlight syntax for Emacs and Aquamacs, add this to your config file:

```lisp
(font-lock-add-keywords 'scheme-mode
  '(("\\<\\(todo\\)" 1 font-lock-warning-face prepend)
    ("\\<\\(define\\|define+\\|def\\|def+\\|return\\|return-rec\\|<-\\|condx\\|then\\|else\\)\\>" . font-lock-keyword-face)))
```


![Scheme+ schema](https://github.com/damien-mattei/Scheme-PLUS/blob/main/doc/images/schema-scheme%2B.jpg "Scheme+ schema")

<br>
<br>

![Scheme+ schema](https://github.com/damien-mattei/Scheme-PLUS/blob/main/doc/images/infix-with-precedence-to-prefix-V7.jpg "Scheme+ infix with precedence to prefix schema")



