# Creating a reveal.js presentation inside a wrapper web site


A test of an idea - putting a reveal presentation inside a standard
C-shaped web site (header, left sidebar nav, footer; with main being
the slide deck).


    +---------------------------+
    |    header                 |
    |                           |
    |  s   +--------------------+
    |  i   |                    |
    |  d   |                    |
    |  e   |                    |
    |  b   |   SLIDES           |
    |  a   |                    |
    |  r   |                    |
    |      |                    |
    |      |                    |
    |      +--------------------+
    |                           |
    |    footer                 |
    +---------------------------+

basic idea, sorta works.

- create the slide show as you would
- create the wrapper, and put the slideshow in an `iframe`


Sorta works. Sorts. I don't think I'd recommend it though.
