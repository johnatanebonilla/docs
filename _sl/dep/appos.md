---
layout: relation
title: 'appos'
shortdef: 'appositional modifier'
udver: '2'
---

An appositional modifier of a noun is a nominal immediately following the first noun that serves to define, modify, name, or describe that noun. In Slovenian treebanks, the `appos` relation is only used for appositions which are separated from the phrase they refer to by a comma, parentheses or other types of punctuation.

~~~ sdparse
Območje medenice je središče telesa , glavna peč , ki greje in uravnava vse telo \n Pelvis area is center of-body , central furnace , that warms and regulates whole body
appos(središče,peč)
appos(center,furnace)
~~~

~~~ sdparse
Dianne se je sprla z Liso , svojo prijateljico , in se je odločila, da gre domov \n Dianne REFLEX she-aux-PAST fought with Lisa , her firend , and REFLEX she-aux-PAST decided , to go home
appos(Liso,prijateljico)
appos(Lisa,friend)
~~~
<!-- Interlanguage links updated Út 9. května 2023, 20:03:59 CEST -->
