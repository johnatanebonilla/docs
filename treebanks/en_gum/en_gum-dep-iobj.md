---
layout: base
title:  'Statistics of iobj in UD_English-GUM'
udver: '2'
---

## Treebank Statistics: UD_English-GUM: Relations: `iobj`

This relation is universal.

326 nodes (0%) are attached to their parents as `iobj`.

326 instances of `iobj` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.3159509202454.

The following 4 pairs of parts of speech are connected with `iobj`: <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-PRON.html">PRON</a></tt> (212; 65% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-NOUN.html">NOUN</a></tt> (88; 27% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-PROPN.html">PROPN</a></tt> (25; 8% instances), <tt><a href="en_gum-pos-VERB.html">VERB</a></tt>-<tt><a href="en_gum-pos-DET.html">DET</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 8 iobj	color:blue
1	I	I	PRON	PRP	Case=Nom|Number=Sing|Person=1|PronType=Prs	2	nsubj	2:nsubj|7:nsubj	Discourse=joint-other_m:14->2:3|Entity=(4-person-giv:act-cf1*-1-ana)
2	came	come	VERB	VBD	Mood=Ind|Number=Sing|Person=1|Tense=Past|VerbForm=Fin	0	root	0:root	_
3	home	home	ADV	RB	Degree=Pos	2	advmod	2:advmod	_
4	last	last	ADJ	JJ	Degree=Pos	5	amod	5:amod	Entity=(7-time-giv:act-cf3-2-coref
5	night	night	NOUN	NN	Number=Sing	2	obl:tmod	2:obl:tmod	Entity=7)
6	and	and	CCONJ	CC	_	7	cc	7:cc	Discourse=joint-sequence_m:15->14:0
7	told	tell	VERB	VBD	Mood=Ind|Number=Sing|Person=1|Tense=Past|VerbForm=Fin	2	conj	2:conj:and	_
8	you	you	PRON	PRP	Case=Acc|Number=Sing|Person=2|PronType=Prs	7	iobj	7:iobj	Entity=(12-person-giv:act-cf2-1-ana)|SpaceAfter=No
9	.	.	PUNCT	.	_	2	punct	2:punct	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 8 iobj	color:blue
1	Is	be	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	4	cop	4:cop	Discourse=topic-question:130->138:1
2	n't	not	PART	RB	Polarity=Neg	4	advmod	4:advmod	_
3	that	that	PRON	DT	Number=Sing|PronType=Dem	4	nsubj	4:nsubj	Entity=(49-plant-giv:inact-cf2-1-ana)
4	what	what	PRON	WP	PronType=Rel	0	root	0:root	Entity=(58-plant-new-cf5-1-coref
5	you	you	PRON	PRP	Case=Nom|Number=Sing|Person=2|PronType=Prs	6	nsubj	6:nsubj	Entity=(48-person-giv:act-cf1*-1-ana)
6	gave	give	VERB	VBD	Mood=Ind|Number=Sing|Person=2|Tense=Past|VerbForm=Fin	4	acl:relcl	4:acl:relcl	_
7	the	the	DET	DT	Definite=Def|PronType=Art	8	det	8:det	Entity=(59-person-new-cf3-2-coref
8	neighbor	neighbor	NOUN	NN	Number=Sing	6	iobj	6:iobj	Entity=59)
9	one	one	NUM	CD	NumForm=Word|NumType=Card	10	nummod	10:nummod	Entity=(60-time-new-cf4-2-sgl
10	time	time	NOUN	NN	Number=Sing	6	obl:tmod	6:obl:tmod	Entity=60)58)|SpaceAfter=No
11	?	?	PUNCT	.	_	4	punct	4:punct	_

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 10 iobj	color:blue
1	Do	do	AUX	VB	VerbForm=Inf	3	aux	3:aux	Discourse=adversative-antithesis:160->153:2
2	n't	not	PART	RB	Polarity=Neg	3	advmod	3:advmod	_
3	tell	tell	VERB	VB	Mood=Imp|Person=2|VerbForm=Fin	0	root	0:root	_
4	him	he	PRON	PRP	Case=Acc|Gender=Masc|Number=Sing|Person=3|PronType=Prs	3	iobj	3:iobj	Entity=(64-person-giv:inact-cf1-1-ana)|SpaceAfter=No
5	,	,	PUNCT	,	_	9	punct	9:punct	_
6	or	or	CCONJ	CC	_	9	cc	9:cc	Discourse=joint-disjunction_m:161->160:0
7	do	do	AUX	VB	VerbForm=Inf	9	aux	9:aux	_
8	n't	not	PART	RB	Polarity=Neg	9	advmod	9:advmod	_
9	tell	tell	VERB	VB	Mood=Imp|Person=2|VerbForm=Fin	3	conj	3:conj:or	_
10	Carolyn	Carolyn	PROPN	NNP	Number=Sing	9	iobj	9:iobj	Entity=(66-person-new-cf2-1-coref)|SpaceAfter=No
11	.	.	PUNCT	.	_	3	punct	3:punct	_

~~~


