---
layout: base
title:  'Statistics of obl:agent in UD_English-GENTLE'
udver: '2'
---

## Treebank Statistics: UD_English-GENTLE: Relations: `obl:agent`

This relation is a language-specific subtype of <tt><a href="en_gentle-dep-obl.html">obl</a></tt>.
There are also 2 other language-specific subtypes of `obl`: <tt><a href="en_gentle-dep-obl-npmod.html">obl:npmod</a></tt>, <tt><a href="en_gentle-dep-obl-tmod.html">obl:tmod</a></tt>.

27 nodes (0%) are attached to their parents as `obl:agent`.

26 instances of `obl:agent` (96%) are left-to-right (parent precedes child).
Average distance between parent and child is 4.44444444444444.

The following 5 pairs of parts of speech are connected with `obl:agent`: <tt><a href="en_gentle-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gentle-pos-NOUN.html">NOUN</a></tt> (20; 74% instances), <tt><a href="en_gentle-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gentle-pos-PROPN.html">PROPN</a></tt> (4; 15% instances), <tt><a href="en_gentle-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gentle-pos-ADP.html">ADP</a></tt> (1; 4% instances), <tt><a href="en_gentle-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gentle-pos-PRON.html">PRON</a></tt> (1; 4% instances), <tt><a href="en_gentle-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gentle-pos-X.html">X</a></tt> (1; 4% instances).


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 10 obl:agent	color:blue
1	Labs	lab	NOUN	NNS	Number=Plur	6	nsubj:pass	6:nsubj:pass|8:nsubj:pass	Discourse=joint-other_m:165->13:4|Entity=(77-event-giv:inact-cf1-1-coref)
2	and	and	CCONJ	CC	_	3	cc	3:cc	_
3	Quizzes	quiz	NOUN	NNS	Number=Plur	1	conj	1:conj:and|6:nsubj:pass	Entity=(164-abstract-giv:inact-cf2-1-coref)
4	should	should	AUX	MD	VerbForm=Fin	6	aux	6:aux|8:aux	_
5	be	be	AUX	VB	VerbForm=Inf	6	aux:pass	6:aux:pass|8:aux:pass	_
6	solved	solve	VERB	VBN	Tense=Past|VerbForm=Part|Voice=Pass	0	root	0:root	_
7	and	and	CCONJ	CC	_	8	cc	8:cc	_
8	written	write	VERB	VBN	Tense=Past|VerbForm=Part	6	conj	6:conj:and	_
9	by	by	ADP	IN	_	10	case	10:case	_
10	individuals	individual	NOUN	NNS	Number=Plur	6	obl:agent	6:obl:agent	Entity=(245-person-new-cf3-1-sgl)
11	alone	alone	ADV	RB	Degree=Pos	6	advmod	6:advmod	SpaceAfter=No
12	.	.	PUNCT	.	_	6	punct	6:punct	_

~~~


~~~ conllu
# visual-style 18	bgColor:blue
# visual-style 18	fgColor:white
# visual-style 16	bgColor:blue
# visual-style 16	fgColor:white
# visual-style 16 18 obl:agent	color:blue
1	Then	then	ADV	RB	PronType=Dem	4	advmod	4:advmod	Discourse=context-circumstance:135->147:3|SpaceAfter=No
2	,	,	PUNCT	,	_	1	punct	1:punct	_
3	me	I	PRON	PRP	Case=Nom|Number=Sing|Person=1|PronType=Prs	4	nsubj	4:nsubj	Discourse=attribution-positive:136->137:0|Entity=(3-person-giv:inact-cf1-1-ana)
4	thought	think	VERB	VBD	Mood=Ind|Number=Sing|Person=1|Tense=Past|VerbForm=Fin	0	root	0:root	SpaceAfter=No
5	,	,	PUNCT	,	_	8	punct	8:punct	_
6	the	the	DET	DT	Definite=Def|PronType=Art	7	det	7:det	Discourse=same-unit_m:137->135:0|Entity=(98-substance-new-cf3-2-sgl
7	air	air	NOUN	NN	Number=Sing	8	nsubj	8:nsubj|9:nsubj:xsubj	Entity=98)
8	grew	grow	VERB	VBD	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	4	ccomp	4:ccomp	_
9	denser	dense	ADJ	JJR	Degree=Cmp	8	xcomp	8:xcomp	SpaceAfter=No
10	,	,	PUNCT	,	_	11	punct	11:punct	_
11	perfumed	perfume	VERB	VBN	Tense=Past|VerbForm=Part	8	advcl	8:advcl	Discourse=causal-cause:138->135:1
12	from	from	ADP	IN	_	15	case	15:case	_
13	an	a	DET	DT	Definite=Ind|PronType=Art	15	det	15:det	Entity=(99-object-new-cf6-3-sgl
14	unseen	unseen	ADJ	JJ	Degree=Pos|Polarity=Neg	15	amod	15:amod	_
15	censer	censer	NOUN	NN	Number=Sing	11	obl	11:obl:from	Entity=99)
16	Swung	swing	VERB	VBN	Tense=Past|VerbForm=Part	15	acl	15:acl	Discourse=elaboration-attribute:139->138:0
17	by	by	ADP	IN	_	18	case	18:case	_
18	Seraphim	Seraphim	PROPN	NNPS	Number=Plur	16	obl:agent	16:obl:agent	Entity=(19-person-giv:inact-cf2-1-coref
19	whose	whose	PRON	WP$	Poss=Yes|PronType=Rel	22	nmod:poss	22:nmod:poss	Discourse=elaboration-attribute:140->139:0
20	foot	foot	NOUN	NN	Number=Sing	22	compound	22:compound	Entity=(100-abstract-new-cf4-3-sgl
21	-	-	PUNCT	:	_	20	punct	20:punct	_
22	falls	fall	NOUN	NNS	Number=Plur	23	nsubj	23:nsubj	Entity=100)
23	tinkled	tinkle	VERB	VBD	Mood=Ind|Number=Plur|Person=3|Tense=Past|VerbForm=Fin	18	acl:relcl	18:acl:relcl	_
24	on	on	ADP	IN	_	27	case	27:case	_
25	the	the	DET	DT	Definite=Def|PronType=Art	27	det	27:det	Entity=(101-object-new-cf5-3-sgl
26	tufted	tufted	ADJ	JJ	Degree=Pos	27	amod	27:amod	_
27	floor	floor	NOUN	NN	Number=Sing	23	obl	23:obl:on	Entity=101)19)|SpaceAfter=No
28	.	.	PUNCT	.	_	4	punct	4:punct	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 5 obl:agent	color:blue
1	(	(	PUNCT	-LRB-	_	2	punct	2:punct	Discourse=context-background:140->141:1|SpaceAfter=No
2	intransitive	intransitive	ADJ	JJ	Degree=Pos	0	root	0:root	XML=<ref target:::"https://en.wiktionary.org/wiki/Appendix:Glossary#intransitive"></ref>
3	followed	follow	VERB	VBN	Tense=Past|VerbForm=Part	2	parataxis	2:parataxis	_
4	by	by	ADP	IN	_	5	case	5:case	_
5	to	to	ADP	IN	_	3	obl:agent	3:obl:agent	XML=<ref target:::"https://en.wiktionary.org/wiki/to#English"></ref>

~~~


